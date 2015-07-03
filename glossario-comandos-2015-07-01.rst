======================
Glossário de comandos
======================

:Disciplina: Fundamentos de Sistemas Operacionais
:Professor: Jurandy Soares
:Nome: Ícaro Luiz de Souza Lino
:Matrícula: 20121144010486
:Data: 01/07/2015

cat
  Mostra o conteúdo de um arquivo binário ou texto.

  cat [opções] [diretório/arquivo] [diretório1/arquivo1]

  opções
  -n, --number
  Mostra o número das linhas enquanto o conteúdo do arquivo é mostrado.

  -s, --squeeze-blank
  Não mostra mais que uma linha em branco entre um parágrafo e outro.
  

cd
  Entra em um diretório.
  
  cd [diretório]


cowsay
  cowsay -f - Mostra a saída do comando cowsay (vaca) personalizado.


echo
  Mostra mensagens.
  
  echo [mensagem]
  
  opção
  -n,
  não ocorra o salto de linha após a mensagem ser mostrada.


env
  Imprime lista de variáveis de ambiente.


exit
  Fecha um processo ou aplicação.


help
  Ajuda rápida, útil para saber que opções podem ser usadas com os comandos internos do interpretador de comandos.

  help [comando]
  

HISTTIMEFORMAT="%d/%m/%y
  Muda o formato em que a horário é exibido.


hostname
  Mostra ou muda o nome de seu computador na rede.


ifconfig
  Interfaces de redes.


last
  Mostra uma listagem de entrada e saída de usuários no sistema.
  
  last [opções]
  
  opções
  -n [num]
  Mostra [num] linhas. Caso não seja usada, todas as linhas são mostradas.

  -R
  Não mostra o campo HostName.

  -a
  Mostra o hostname na última coluna. Será muito útil se combinada com a opção -d.

  -d
  Usa o DNS para resolver o IP de sistemas remotos para nomes DNS.

  -x
  Mostra as entradas de desligamento do sistema e alterações do nível de execução do sistema.


lastb
  Descrição do comando


ls
  Lista os arquivos de um diretório.

  ls [opções] [caminho/arquivo] [caminho1/arquivo1] ...


mkdir
  Cria um diretório no sistema.

  mkdir [opções] [caminho/diretório] [caminho1/diretório1]
  

nome="fulano"
  Cria uma variável "nome" e com valor "fulano".


passswd
  Modifica a parametros e senha de usuário.
  
  passwd [usuário] [opções]


pwd
  Mostra o nome e caminho do diretório atual.


set
  As variáveis de ambiente são visualizadas/criadas através do comando set.


tree
  Mostra a árvore de diretórios.


tty
  Imprime o nome do arquivo atrelado ao terminal vinculado à saída padrão.


vim
  Abre um arquivo usando o editor vim.


wait
  Espera um determinado processo ou periodo de tempo terminar.


wall
  Envia uma mensagem ou conteúdo de arquivo para todos os usuarios logados.


which
  Localiza um programa na estrutura de diretórios do path,somente são mostrados arquivos executáveis.

  which [programa/comando]


while
  A  mesmo estrutura de repetição de linguagens de programação.


who
  Mostra quem está atualmente conectado no computador. Este comando lista os nomes de usuários que estão conectados em seu computador, o terminal e data da conexão.

  who [opções]


whoami
  Mostra o nome que usou para se conectar ao sistema.


write
  Envia uma mensagem ou conteúdo de arquivo para determinado usuário logado.
  
  write [usuario]

