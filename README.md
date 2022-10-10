Alô meus queridos, bem vindos ao meu mundo!
O primeiro passo é criar uma pasta para armazenar um repositório local (mkdir "nome da Pasta");
O segundo passo é acessar essa pasta (cd "nome da Pasta")
O terceiro passo é ter uma pasta versionada e criar uma estrutura inicial (git init)
O quarto passo é criar uma branch nova (git checkout -b "nome da branch")
O quinto passo é adicionar os arquivos que forem criados e/ou modificados e selecionados ao que será a próxima versão (git add . ou git add "nomeDoArquivo")
O sexto passo é comitar as mudanças, ou seja, uma nova versão do repositório local é criada com uma descrição do que essa versão muda em relação a antiga (git commit -m "Mensagem desejada")
O último passo é voltar a branch principal (main) e realizar a mescla (merge) das alterações realizadas nas branchs alternativas na branch principal (git merge "nome da branch que se queira mesclar")
Esse processo se repetirá até a conclusão do projeto.
