# GIT-Pojeto Reversão

# Tarefa

## Tarefa 2: Git Reversão

Aluno: Brenno Elimar


1. # Inicializar o repositório e preparar o projeto:**:

   git init "Projeto Reversão" cria uma nova pasta chamada "Projeto Reversão" e a inicializa como um repositório Git.

 cd "Projeto Reversão" entra na pasta do projeto.

2.## Criar o arquivo e fazer o primeiro commit:

  echo "Conteúdo inicial do experimento" > experimento.txt cria o arquivo experimento.txt e adiciona o texto inicial.

 git add experimento.txt prepara o arquivo para o commit.

  git commit -m "alteração" salva as alterações com a mensagem "alteração".

3.**Modificar o arquivo e restaurar a alteração com git restore**:

  echo "nova linha de teste" >> experimento.txt adiciona uma nova linha ao arquivo.

  git restore experimento.txt desfaz as alterações não comitadas, revertendo o arquivo para o estado anterior.

4.Adicionar outra modificação e preparar para o commit**:

  echo "alteração 2" >> experimento.txt adiciona mais uma linha ao arquivo.

  git add experimento.txt prepara o arquivo modificado para um novo commit.

5.Reverter o último commit com git reset --hard"**:

  git log --oneline exibe o histórico de commits, mostrando uma lista de commits com seus códigos de identificação e mensagens.

  git reset --hard HEAD~1 remove o último commit e quaisquer alterações desde então, voltando para o estado do commit anterior.

  git log --oneline verifica novamente o histórico, confirmando que o commit foi removido.
