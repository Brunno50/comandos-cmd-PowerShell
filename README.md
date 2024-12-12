# comandos-cmd-PowerShell
Comandos-cmd- PowerShell

Guia de Comandos CMD
 Listar Arquivos e Diretórios- Comando: dir
 Exibe a lista de arquivos e diretórios no diretório atual.
 Navegação entre Diretórios- Comando: cd (Change Directory)
 Usado para navegar entre diretórios no sistema de arquivos.
 Exemplos:
 cd Downloads
 cd Downloads\pasta teste- Voltar para o Diretório Pai:
 Comando: cd ..
 Exemplo:
 Diretório atual: C:\Users\Julian\Desktop
 Comando: cd ..
 Resultado: C:\Users\Julian
 Criar Diretórios- Comando: mkdir (Make Directory)
 Cria um novo diretório. Se o nome contiver espaços, use aspas.
 Exemplos:
 mkdir "Nova Pasta"
 mkdir pastatestes
Excluir Diretórios- Comando: rmdir /S [nomepasta]
 Remove um diretório e todo o seu conteúdo. O sistema pedirá confirmação.
 Exemplo:
 rmdir /S "Desktop\Minha Pasta"
 Mover Arquivos- Comando: move [arquivo] [destino]
 Move um arquivo para um diretório especificado.
 Exemplo:
 move Cats.txt Cats- Mover Arquivo para o Diretório Pai:
 Comando: move [arquivo] ..
 Exemplo:
 Diretório atual: C:\Users\Brunno 480\Desktop\pcgamer
 Comando: move mause.txt ..
 Resultado: C:\Users\Brunno 480\Desktop\
 Copiar Arquivos- Comando: copy [arquivo] [destino]
 Copia um arquivo para o destino especificado.
 Exemplos:
 copy gabinete.txt pcgamer
 copy *.txt pcgamer
Renomear Arquivos- Comando: ren [arquivo_atual] [novo_nome]
 Renomeia um arquivo.
 Exemplo:
 ren arquivo.txt arquivo2.txt
 Deletar Arquivos- Comando: del
 Exclui arquivos especificados.
 Exemplos:
 del arquivo.txt
 del *.txt
 del "meu arquivo.txt"
 Criar Arquivos- Criar um Arquivo e Adicionar Texto:
 Comando: echo [texto] > [arquivo.txt]
 Exemplo:
 echo Hello World > File.txt- Adicionar Texto a um Arquivo Existente:
 Comando: echo [texto] >> [arquivo.txt]
 Exemplo:
 echo Goodbye World >> File.txt- Exibir Conteúdo de um Arquivo:
Comando: type [arquivo.txt]
 Combinação de Comandos- Operadores:
 &&: Executa o segundo comando apenas se o primeiro for bem-sucedido.
 &: Executa ambos os comandos, independentemente do resultado do primeiro.
 ||: Executa o segundo comando apenas se o primeiro falhar.
 |: Redireciona a saída de um comando como entrada para outro.
 Inicializar Programas no CMD
 1. Comandos Internos:
 Usam funções já embutidas no CMD, como echo ou cd.
 2. Invocação Direta:
 Para programas externos, navegue até o diretório do executável e inicie-o.
 Exemplo:
 cd "C:\Program Files\Google\Chrome\Application"
 chrome.exe
 3. Comando start:
 Inicia diretamente um programa.
 Exemplos:
 start "" "C:\Program Files\Google\Chrome\Application\chrome.exe"
 set Chrome="C:\Program Files\Google\Chrome\Application\chrome.exe"
 start Chrom
