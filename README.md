# revisao.git.comandos
Revisão git

## O que é markdown?

O **markdown** é uma linguagem 
bem *legal*! 

Comando do markdown 

Comando do ~~markdown~~ 

Documentação do markdown [Markdown](https://docs.github.com/pt/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

1. Abacate
2. Melancia
3. Abacaxi 

- Games
- Filmes
- Músicas

como colocar uma imagem 

![Isso é uma imagem](./img/GitHub.jpg)

```
    git clone link_do_repositório

```    

Codigo Html

```html
<html>
    ....
</html>    
```

Codigo javascript
```javascript
const nome = "maria";
```


# Revisão dos comandos 


# Branchs 
São ramificações do projeto, o qual o permite vários desenvolvedores
, trabalharem em diferentes funcionalidades, sem bugar a versão principal

## Principais Branchs

Branch Main -> que é a Branch principal, ou seja, a branch 
estável da aplicação. Versão que é disponibilizada aos clientes

Branch developer -> é a Branch utilizada pelos testers. Os quais vão testar as novas funcionalidades, correções de bugs, etc. 

## Outras Branchs 

Para cada nova funcionalidade ou correção de bugs é criada uma nova branch 

### Padrões para criar nomes de branchs 

!IMPORTANTE! Nomes de branchs não tem acento nem Ç.

Para correção de bugs: fix_identificacao_do_bug
Exemplo: fix_botao_de_login, fix_cor_do_cabecalho

Para novas funcionalidades:
feat_identificacao_da_nova_funcionalidade
Exemplo: feat_integracao_com_google, feat_nova_tela_de_contato

Para atualizar documentações: doc_identificacao_da alteracao
Exemplo: doc_adicionado_nova_imagem

Para criação/alteração de tarefas que não interfere no código
chore_identificao_da_modificacao
Exemplo: chore_atualizado_a_versao_do_banco


## Comandos para trabalhar com branchs
### Criação de novas branchs
git checkout -b nome_da_nova_branch
Exemplo: got checkout -b fix_botao_da_tela_login
Obs: O ideal é sempre criar as branchs a partir da main.

## Listar as branchs existentes
git branch list

### Trocar de branch 
git switch nome_da_branch_que_deseja_entrar
Exemplo 01: git switch fix_botao_da_tela_login
Exemplo 02: git switch main

### Excluir uma branch
git branch -D nome_da_branch_que_deseja_exluir
Exemplo: git branch -D fix botao_da_tela_de_login