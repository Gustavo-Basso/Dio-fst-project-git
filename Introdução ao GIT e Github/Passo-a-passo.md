### Passo-a-Passo
1. [Baixar o GIT](https://git-scm.com/downloads) e realizar a instalacao;

2. Fica pressuposto que voce ja possua uma conta no GitHub;

3. [Criar uma chave SSH;](https://docs.github.com/articles/generating-an-ssh-key/) 

4. Abrir a pasta de usuarios, entrar no usuario local e criar uma pasta onde sera realizados suas funcoes no GIT/GitHub;

5. Na pasta criada, aperte com o botao direito do mouse e clique na opcao "git bash here";

6. Com o git bash aberto, registre seu usuario com os comandos, respectivamente em ordem: git config --global user.email "seu e-mail" e git config --global user.name "seu nome" * sempre importante cadastrar o e-mail utilizado no seu GitHub;

7. Alocar o repositorio do GitHub para o seu computador atraves do comando git clone "link do ssh aqui";

### Assim entao voce consegue realizar as operacoes requeridas e apos isso, conseguira enviar novamente seu repositorio ao GitHub com o passo-a-passo a seguir

1. Abra o Git Bash no diretorio atual das alteracoes *pelo "git bash here" ou atraves do comando cd;

2. Cheque o status do arquivo atraves do comando "git status" * note que mostrara os arquivos alterados em um comentario de cor vermelha;

3. Para validar essas adicoes, use o comando "git add ." e apos isso, use o comando "git commit"* caso queira adicionar um comentario, use o comando "git commit -m 'seu comentario'";

4. Finalmente digite o comando "git push origin main" para enviar o repositorio para o GitHub; 

5. De um refresh na pagina e pronto!

