# Git-ao-GitHub 🤓

Minhas anotações pessoais são do curso "Introdução ao Git e ao GitHub" ministrado pelo Otávio Reis - real e o do futuro 🤭

Todas as instruções são feitas com base Windows.


## Git Bash

O Git Bash é um terminal estendido para otimizar o uso do Git.
[Link para download] (https://git-scm.com/downloads)

### Entendendo como o GIT funciona por baixo dos panos

Vamos ver abaixo como é a lógica do GIT para um melhor entendimento:

#### SHA1 [Segure Hash Algorithm]  

 É um conjunto de função hash criptográfica desenvolvido pela NASA [Agência de Segurança Nacional dos E.U.A.] onde gera 40 caracteres quando alterado informações. 

 #### Objetos Internos do GIT

 São eles:

* BLOBS [Bolhas] - Armazena metadados (palavras, imagens, números, etc). 
 
* TREES [Árvores] - Armazenam blobs e outras trees. 
 
* COMMITS [Comprometer-se] - Objeto que junta todas as informações para localização dos dados.



Imagem 2



**Chaves SSH** - Estabelece conexão segura e criptografada entre duas maquinas.

Pública - Mais pessoas podem acessar.

Privada - Só acessa o usuário.



**Token de acesso pessoal** - Solicita usuário e senha sempre que fizer um commit. Salvar, pois não tem como recuperar o mesmo token.





# Criando um Repositório

#### **Mão na massa** :muscle:



* No GitHub > Your repositorie > New > 

  Repository name: *Meu livro de Receitas*

  PublicAnyone on the internet can see this repository. You choose who can commit.

  *(Para outras pessoas terem acesso.)*

  Add a README fileThis is where you can write a long description for your project. [Learn more.](https://docs.github.com/github/creating-cloning-and-archiving-repositories/about-readmes)

  *(Dessa forma o próprio GitHub vai criar a "Home Page" para darmos uma introdução ao nosso projeto.)*

  Create repository

   

* Depois de criado, clicar em *Code* e copiar o link em  HTTPS

* Criar uma pasta 'workpace'  e dentro dela 'livro-de-receitas' no 'C' do seu computador:

  exemplo: 

  */c/workspace/livro-de-receitas*

* Clonar seu repositório já criado no GitHub pelo Git Bash

  Abrir o **Git Bash** com botão direito dentro da pasta 'livro-de-receitas' 

  Digitar *git clone* enter

  

  **NOTE**

  *Se não der erro está tudo certo!

  *Normalmente está oculta.

  *De preferência usar um programa markdown (Typora)

  

* Alimentar seu material no seu terminar para depois empurrar para GitHub.

* Como enviar essa atualização feita para o GitHub 

  No Git bash dar o comando *git status*

  Será identificado a criação de novos itens dentro arquivo clonado e em vermelho apresentará uma mensagem.

  Digitar o comando * git add .* para o git entenda que voce está querendo enviar essa atualização feita para o repositório GitHub e ao digitar o comando *git status* novamente em verde será apresentado uma mensagem. 

* Agora precisamos realizar um Commit 

  Comando *git commit -m "Incluir livro-de-receitas"* 

  *Comentários em " " devem ser coerentes que façam sentido para o que voces querem enviar.

  Após esse comando o git ja esta preparado para empurrar essa atualização feita para o GitHub.

   

* Como enviar, comando *git push origin (branch)*

  Pronto! Ao atualizar sua pagina no GitHub você ja consegue ver todas as atualizações feitas no seu terminal. 

  Como descobrir a sua *branch*?

  No GitHub > clicar no repositório criado > Editar seu texto no 'lápis' que fica a direita da dela > No rodapé dessa tela contem  *Commit directly to the **main** branch*.

  

 
Obrigada!


 





