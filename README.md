# Projeto Gama

Esse será um projeto realizado em conjunto. Seu principal objetivo é o aprendizado das linguagens e tecnologias a serem descritas.

Esse readme será atualizado com frequência a medida que os autores decidirem.

## Desenvolvedores:

* [Evelyn Fernandes](https://github.com/yoruwitch);
* [Isadora Gonçalves Ferreira](https://github.com/isa56);

## Linguagens e Tecnologias usadas:::

### Front-end:

* HTML; 
* CSS;
* JavaScript;
* React.

### Back-end:

* Node.js;
* Mais alguma outra coisa que decidirmos.

## Arquitetura do Projeto:

* Não sei.


## Mini tutorial de GIT:
### Começar um projeto

Abra uma pasta, clique com o botão direito e selecione "Git Bash Here" para abrir o terminal do git\
Clone o repositório
```
git clone https://github.com/isa56/projetogama
```
Entre na pasta criada pelo comando clone
```
cd projetogama
```
Crie sua branch usando como o padrão o nome da funcionalidade que você vai desenvolver
```
git checkout -b controller.js
```
Após criada a branch você será redirecionado automaticamente a ela, já podendo começar o desenvolvimento\

### Rotina

Adicionar uma alteração específica
```
git add nomeDoArquivo
```
Adicionar todas as alterações
```
git add .
```
Conferir em qual branch está e quais alterações foram adicionadas
```
git status
```
Dê um commit com uma mensagem especificando as alterações realizadas
```
git commit -m "mensagem"
```
Envie o commit feito para sua branch
```
git push origin nomeDaBranch
```

### Quando terminar a funcionalidade - *com autorização do SCRUM Master*

Volte para a main
```
git checkout main
```
Atualize a main
```
git pull
```
Volte pra sua branch
```
git checkout nomeDaBranch
```
Mescle a main com a sua branch <sub>(estando dentro da sua branch)<sub/>
```
git merge main
```
Confirme o merge <sub>(quando solicitado pelo Scrum Master)<sub/>
```
git push origin nomeDaBranch
```
Espere a confirmação do seu Scrum Master\
Volte para a main
```
git checkout main
```
Mescle a main com as alterações enviadas para sua branch <sub>(quando solicitado pelo Scrum Master)<sub/> 
```
git merge nomeDaBranch
```
Confirme o merge <sub>(quando solicitado pelo Scrum Master)<sub/>
```
git push origin main
```
