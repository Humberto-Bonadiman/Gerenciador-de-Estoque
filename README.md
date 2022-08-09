# Boas vindas ao repositório do Gerenciador de Estoque!

---

## Descrição do projeto

Neste projeto eu fui responsável por finalizar as configurações do docker-compose e Dockerfile presentes no projeto e depois testar a aplicação.

---

## Instalação do projeto localmente

Após cada um dos passos, haverá um exemplo do comando a ser digitado para fazer o que está sendo pedido.

1.Realize o clone do projeto no diretório de sua preferência:
```javascript
git clone git@github.com:Humberto-Bonadiman/Gerenciador-de-Estoque.git
```

2.Acesse o diretório do projeto e depois utilize o comando mvn install para instalar todas as dependências necessárias:
```javascript
cd Gerenciador-de-Estoque
mvn install
```

---

# Requisitos do desafio

## Gerenciando o estoque 

Você, pessoa desenvolvedora, faz parte do time de tecnologia de uma empresa que está construindo um gerenciador de estoque. Sua tarefa, dentro do projeto, é finalizar algumas configurações e testes para depois disponibilizá-los.


Realizando a lista de tarefas abaixo, você completará o projeto. Vamos lá? 🚀

1 - Escreva o Dockerfile dessa aplicação que foi desenvolvida em Java 11;
**Atenção⚠:**Precisa ser em multi-stage. 

2 - No arquivo docker-compose.yml, configure a aplicação para subir na porta 8888 e estar linkada com o mongo db( que deve usar a versão mais recente e subir na porta 27017).

3 - Na classe dos testes, está faltando realizar algumas configurações do TestContainers. Adicione as annotations necessárias para que os testes sejam executados e passem :relieved: 

De olho na dica👀: Para validar se está tudo funcionando, tente fazer algumas requisições para a aplicação utilizando o Postman e caso dê algum erro valide se o contâiner foi inicializado corretamente ou se por exemplo já tem alguma outra aplicação na porta que configuramos.
 Caso tenha encerre essas aplicações para liberar a porta :)

---
