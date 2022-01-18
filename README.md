# Projeto-Git-Github 📚
Organizando meu conhecimento em Git/ GitHub 

### O que é Git? <h3> 💻
  
  Git é um sistema de controle de versão open-source. Ele é utilizado para a criação de um histórico de alterações em código-fonte de projetos de desenvolvimento de software. Foi desenvolvido por Linus Torvalds, o criador do sistema operacional Linux.

Por meio de sua utilização, podemos saber quais foram as alterações realizadas, quem fez cada uma das alterações e baixar essas mudanças em nossa máquina. Se necessário, revertê-las para uma versão anterior.
  
*Link para download do Git: <https://git-scm.com/downloads>
  
  
### O que é GitHub? <h3> 🖥
  
  O Github é um serviço web que oferece diversas funcionalidades extras aplicadas ao git. Você poderá usar gratuitamente o github para hospedar seus projetos pessoais. Além disso, quase todos os projetos/frameworks/bibliotecas sobre desenvolvimento open source estão no github, e você pode acompanhá-los através de novas versões, contribuir informando bugs ou até mesmo enviando código e correções. Se você é desenvolvedor e ainda não tem github, você está atrasado e essa é a hora de correr atrás do prejuízo.

  
  
### Primeiros comandos do Git <h3>
  
  * git init: Isso criará alguns arquivos próprios do git, entre eles o mais importante é o gitignore, pois nele está tudo o que se deve ignorar ao realizar o commit. É aqui onde vamos colocar diretórios e arquivos grandes, que podemos gerar facilmente, ou arquivos que não queremos que fiquem visíveis no repositório.
  
  * git status: Com ele podemos verificar quais arquivos ainda não adicionamos no repositório local da máquina. Como mostrado na imagem abaixo, são os arquivos marcados em vermelho:
  
  ![Status vermelho](https://blog.cod3r.com.br/wp-content/uploads/2021/01/status_vermelho.png)
  
  
  
  
  * git add . : Esse comando fará com que todos os arquivos fiquem prontos para o Github, por isso ele é indispensável. É importante observar que usei o git add . porque quero adicionar todos os arquivos do projeto, mas caso você queira adicionar apenas algum arquivo específico, basta usar git add <nome_do_arquivo>.
  Ao digitar novamente o git status, vamos ver o seguinte:
  
  ![Status verde](https://blog.cod3r.com.br/wp-content/uploads/2021/01/status_verde.png)
  
  
  #### Primeiro Commit <h4>
  
  **Basta utilizar o seguinte comando:**
  
  * git commit -m "meu primeiro commit": A flag -m indica que vamos adicionar uma mensagem para aquele commit. Dessa forma conseguiremos identificar o que foi feito naquele commit. Por exemplo, você acabou de adicionar um Header na aplicação, então na mensagem você sinaliza que criou o header para a aplicação.
  
  
  * git branch -M main: Aqui vamos criar a branch main, que é a principal branch do repositório. Mas como falei anteriormente, você não precisa se preocupar com esse detalhe.
  
  Agora vamos linkar os 2 repositórios, ou seja, o repositório do Github com o da nossa máquina. Use o comando:
  
  * git remote add origin <link_para_o_seu_repositorio>
  
  
  No final vamos enviar o projeto com o comando:
  
  * git push -u origin main.
  
  
  **Pronto, agora você já sabe fazer commit no GitHub. Espero que você consiga realizar os seus commits e aproveitar mais desse mundo de versionamento de códigos**

  
  
  
  
  
  
