<h1> Navegação pelo sistema de arquivo </h1>

<h2> Comandos </h2>

<div align="center">
    <table>
        <tr>
            <th> Comandos </th>
            <th> Descrições </th>
        </tr>
        <tr>
            <td> date </td>
            <td> Verificar a data e hora atual. </td>
        </tr>
        <tr>
            <td> clear </td>
            <td> Limpa o console por completo. </td>
        </tr>
        <tr>
            <td> ctrl + l </td>
            <td> Apaga a última página de comandos no terminal. </td>
        </tr>
        <tr>
            <td> pwd </td>
            <td> Específica o caminho do diretório onde você está atualmente. </td>
        </tr>
        <tr>
            <td> cd + nome da pasta </td>
            <td> Entra no diretório que foi informado. 
        </td>
        <tr>
            <td> ls </td>
            <td> Lista o que você possui no diretório: nada, diretório/s, arquivos. </td>
        </tr>
        <tr>
            <td> cd + .. </td>
            <td> Volta para uma pasta anterior da atual.
        </tr>
        <tr>
            <td> cd + letras inicias do diretório + tab </td>
            <td> Autocomplete para entrar na pasta de forma rápida ou sugerir diretórios correspondente as letras informadas. </td>
        </tr>
   </table>
</div>

<h2> Filtrando a exibição de arquivos - parte 1 </h2>

<div align="center">
    <table>
        <tr>
            <th> Comandos </th>
            <th> Descrições </th>
            <th> Exemplos </th>
        </tr>
        <tr>
            <td> ls | more </td>
            <td> Filtra mais informações sobre o diretório que você está. </td>
            <td> ls | more </td>
        </tr>
        <tr>
            <td> ctrl + c </td>
            <td> Comando usado para sair da listagem de informações. </td>
            <td> ctrl c </td>
        <tr>
            <td> ls + nome do diretório </td>
            <td> Lista todas as informações contidas na pasta. </td>
            <td> ls workspace/ </td>
        </tr>
        <tr>
            <td> ls + letra ou letras + * </td>
            <td> Mostra todos os conteúdos começando com a letra desejada. </td>
            <td> ls p*, ls ss* e ls exp* </td>
        </tr>
        <tr>
            <td> ls + letra + ? + letra + * </td>
            <td> Apresenta dados com o primeiro e terceiro caractere, <br> na interrogração, será feito por uma busca seja uma letra/número entre os caracteres. </td>
            <td> ls e??o* </td>
        </tr>
    </table>
</div>

<h2> Filtrando a exibição de arquivos - parte 2 </h2>

<div align="center">
    <table>
        <tr>
            <th> Comandos </th>
            <th> Descrições </th>
            <th> Exemplos </th>
        </tr>
        <tr>
            <td> touch + nome do arquivo + extensão </td>
            <td> O comando touch é usado para gera um ou mais arquivos vazios simultaneamente. </td>
            <td> touch teste1.txt </td>
        </tr>
        <tr>
            <td> ls + nome do arquivo + intervalo entre colchetes + extensão </td>
            <td> Mostra os arquivos que estão entre o intervalo requisitado. </td>
            <td> ls teste[2-4].txt </td>
            </td>
        </tr>
        <tr>
            <td> ls + nome do arquivo + intervalo entre colchetes com vírgula + extensão </td>
            <td> Faz a listagem dos arquivos referente as numerações. </td>
            <td> ls teste[2,4].txt </td>
        </tr>
        <tr>
            <td> ls + nome do arquivo + intevalo entre parênteses + acento circunflexo + vírgula + extensão </td>
            <td> Ignora as numerações dentro do intervalo e mostra todos os outros arquivos restantes. </td>
            <td> ls teste[^2,4].txt </td>
        </tr>
    </table>
</div>

<h2> Localizando arquivo </h2>

<div align="center">
    <table>
        <tr>
            <th> Comandos </th>
            <th> Descrições </th>
            <th> Exemplos </th>
        </tr>
        <tr>
            <td> ls + nome do diretório + letra </td>
            <td> Procurando arquivos com determinada letra sem estar presente no diretório que esteja buscando. </td>
            <td> ls workspace/t* </td>
        </tr>
        <tr>
            <td> find -name + nome do arquivo </td> 
            <td> Vasculha o arquivo na raíz do seu sistema e mostra o caminho localizado, caso você simplesmente não lembra. </td>
            <td> find -name passwd, find -name teste* e find -name a??c*. </td>
        </tr>
    </table>
</div>

<h2> Criando diretórios </h2>

<div>
    <table>
        <tr>
            <th> Comandos </th>
            <th> Descrições </th>
            <th> Exemplos </th>
        </tr>
        <tr>
            <td> cd + ~ </td>
            <td> Direciona para a home do seu perfil. </td>
            <td> cd ~ </td>
        </tr>
        <tr>
            <td> mkdir + nome da pasta </td>
            <td> Cria uma pasta. </td>
            <td> mkdir Textos </td>
        </tr>
        <tr>
            <td> mkdir + caminho do diretório + nome da pasta </td>
            <td> Indica onde será criada a pasta. </td>
            <td> mkdir /home/usuario/Planilhas </td>
        </tr>
        <tr>
            <td> mkdir + "nome da pasta" </td>
            <td> Cria uma pasta com o nome separado. </td>
            <td> mkdir 'Meus Arquivos' </td>
        </tr>
    </table>
</div>

<h2> Excluindo arquivos e diretórios </h2>

<div align="center">
    <table>
        <tr>
            <th> Comandos </th>
            <th> Descrições </th>
            <th> Exemplos </th>
        </tr>
        <tr>
            <td> rmdir + nome da pasta </td>
            <td> Remove diretório vazio. </td>
            <td> rmdir Textos </td>
        </tr>
        <tr>
            <td> mkdir + nome da pasta + nome da pasta </td>
            <td> Será criada duas pastas simultaneamente. </td>
            <td> mkdir Textos1 Textos2 Textos3 </td>
        </tr>
        <tr>
            <td> rm + arquivo </td>
            <td> Remove o arquivo informado. </td>
            <td> rm texto.txt </td>
        </tr>
        <tr>
            <td> rm + * + extensão </td>
            <td> Deleta todos os arquivos do mesmo formato. </td>
            <td> rm *.txt </td>
        </tr>
        <tr>
            <td> rm + letra + * </td>
            <td> Exclui arquivos iniciandos com determinada letra e o restante dos caracteres são ignorados. </td>
            <td> rm a??c* </td>
        </tr>
        <tr>
            <td> rm -rf + nome da pasta </td>
            <td> Será deletado tudo dentro desta pasta, incluíndo outros diretórios e arquivos. </td>
            <td> rm -rf Dir1 </td>
        </tr>
    </table>
</div>

<h2> Obtendo ajuda </h2>

<div align="center">
    <table>
        <tr>
            <th> Comandos </th>
            <th> Descrições </th>
            <th> Exemplos </th>
        </tr>
        <tr>
            <td> comando + --help </td>
            <td> Informa mais informações sobre o comando, suas flags e de que maneira usar. </td>
            <td> ls --help </td>
        </tr>
        <tr>
            <td> ls + -l </td>
            <td> Mostra uma visualização formatada de diretórios e arquivos. </td>
            <td> ls -l </td>
        </tr>
        <tr>
            <td> ls + -lh </td>
            <td> Ilustra as informações formatadas de diretórios e arquivos porém identificando os tamanhos em MB, GB e afins. </td>
            <td> ls -lh </td>
        </tr>
        <tr>
            <td> man + ls </td>
            <td> Descreve informações sobre o comando na língua inglesa. </td>
            <td> man ls </td>
        </tr>
    </table>
</div>

<h2> Executando tarefas administrativas como superusuário (root) </h2>

<div align="center">
    <table>
        <tr>
            <th> Comandos </th>
            <th> Descrições </th>
            <th> Exemplos </th>
        </tr>
        <tr>
            <td> sudo </td>
            <td> Permissão para realizar atividades em distribuições linux. </td>
            <td> sudo apt update </td>
        </tr>
        <tr>
            <td> su </td>
            <td> Entra em modo root para fazer tarefas de administrador. </td>
            <td> su </td>
        </tr>
        <tr>
            <td> su + nome do usuário </td>
            <td> Após ser o root da máquina, para trocar de usuário utilize su e o nome do usuário que deseja. </td>
            <td> su dev-alexandre17 </td>
        </tr>
    </table>
</div>

<h2> Histórico de comandos </h2>

<div>
    <table>
        <tr>
            <th> Comandos </th>
            <th> Descrições </th>
            <th> Exemplos </th>
        </tr>
        <tr>
            <td> seta para cima ou para baixo </td>
            <td> Visualiza comandos usados anteriormente. </td>
            <td> ↑ ou ↓ </td>
        </tr>
        <tr>
            <td> history </td>
            <td> Listagem de comandos usados até o momento. </td>
            <td> history </td>
        </tr>
        <tr>
            <td> history + número </td>
            <td> Mostra a quantidade dos últimos comandos que deseja visualizar. </td>
            <td> history 10 </td>
        </tr>
        <tr>
            <td> ! + número </td>
            <td> Executa o comando correspondente ao seu número no histórico de comandos. </td>
            <td> !459 </td>
        </tr>
        <tr>
            <td> !! </td>
            <td> Faz a execução do último comando registrado. </td>
            <td> !! </td>
        </tr>
        <tr>
            <td> ! + ? + letras do comando + ? </td>
            <td> Procura o comando similar de acordo com as letras informadas. </td>
            <td> !?dat? </td>
        </tr>
    </table>
</div>

<h2> Criando e excluindo usuários </h2>

<div>
   <table>
        <tr>
            <th> Comandos </th>
            <th> Descrições </th>
            <th> Exemplos </th>
        </tr>
        <tr>
            <td> useradd + nome do usuário </td>
            <td> Cria um usuário. </td>
            <td> useradd joao </td>
        </tr>
        <tr>
            <td> passwd + nome do usuário </td>
            <td> Adiciona uma senha para o usuário criado. </td>
            <td> passwd joao </td>
        </tr>
        <tr>
            <td> useradd + --help </td>
            <td> Buscando ajuda referente na criação de usuários. </td>
            <td> useradd --help </td>
        </tr>
        <tr>    
            <td> userdel + -f + nome do usuário </td>
            <td> Forçar a exclusão do usuário. </td>
            <td> userdel -f joao </td>
        </tr>
        <tr>
            <td> userdel + nome do usuário </td>
            <td> Deletar o usuário da máquina. </td>
            <td> userdel joao </td>
        </tr>
        <tr>
            <td> useradd + -m + nome de usuário + -c + nome da pessoa </td> 
            <td> Criando diretório do usuário e informando o nome da pessoa. </td>
            <td> useradd -m joao -c 'João da Silva' </td>
        </tr>
        <tr>
            <td> userdel + -r + -f + nome </td>
            <td> Deleta tudo do usuário, diretórios, arquivos e afins. </td>
            <td> userdel -r -f joao </td>
        </tr>
    </table>
</div>

<h2> Bloqueando e editando usuários </h2>

<div>
   <table>
       <tr>
           <th> Comandos </th>
           <th> Descrições </th>
           <th> Exemplos </th>
       </tr>
       <tr>
           <td> useradd + -e + data </td>
           <td> Definindo a data de expieração de uso para o usuário. </td>
           <td> useradd -e 29/12/2022 </td>
       </tr>
       <tr>
           <td> useradd + -e + data </td>
           <td> Alterando a data de expiração. </td>
           <td> usermod -e 30/12/2022 </td>
       </tr>
       <tr>
           <td> passwd + nome do usuário + -e </td>
           <td> Troca a senha toda vez que o usuário fazer o login na máquina. </td>
           <td> passwd joao -e </td>
       </tr>
       <tr>
           <td> passwd + nome do usuário + -l </td>
           <td> Bloqueando a conta do usuário. </td>
           <td> passwd aline -l </td>
       </tr>
       <tr>
           <td> passwd + nome do usuário + -u </td>
           <td> Desbloquea a conta do usuário. </td>
           <td> passwd samuel -u </td>
       </tr>
       <tr>
           <td> cat + / + etc/ + passwd/ </td>
           <td> Descobrindo quais usuários foram criados. </td>
           <td> cat /etc/passwd </td>
       </tr>
    </table>
</div>

<h2> Arquivos de senhas (passwd) </h2>

<div>
    <table>
        <tr>
            <th> Comandos </th>
            <th> Descrições </th>
            <th> Exemplos </th>
        </tr>
        <tr>
            <td> grep + -i + 'usuario' + /etc/ + passwd </td>
            <td> Encontrando usuário requisitado. </td>
            <td> grep -i 'dev-alexandre17' /etc/passwd </td>
        </tr>
        <tr>
            <td> cat + /etc/ + shadow </td>
            <td> Visualizar informações sobre o usuário. </td>
            <td> cat /etc/shadow
        </tr>
        <tr>
            <td> stat + /etc/ + passwd
            <td> Informações sobre o arquivo de senhas. </td>
            <td> stat /etc/passwd </td>
        </tr>
    </table>
</div>

<h2> Grupos de usuários </h2>

<div>
    <table>
        <tr>
            <th> Comandos </th>
            <th> Descrições </th>
            <th> Exemplos </th>
        </tr>
        <tr>
            <td> cat + /etc/ + group </td>
            <td> Listagem de grupos no sistema. </td>
            <td> cat /etc/group </td>
        </tr>
        <tr>
            <td> groupadd + nome do grupo </td>
            <td> Criando o grupo de usuários. </td>
            <td> groupadd + GRP_ADM </td>
        </tr>
        <tr>
            <td> useradd + nome do usuário + -c + 'Nome da pessoa' + -G + nome do grupo </td>
            <td> Adicionando um usuário (a) inexistente no sistema ao grupo. </td>
            <td> useradd fernanda -c 'Fernanda da Silva' -G GRP_ADM </td>
        </tr>
        <tr>
            <td> usermod + nome do usuário + -G + nome do grupo </td>
            <td> Adicionando um usuário existente no sistema ao grupo. </td>
            <td> usermod denilson -G GRP_ADM </td>
        </tr>
        <tr>
            <td> groupdel + nome do grupo </td>
            <td> Deletando o grupo. </td>
            <td> groupdel GRP_ADM </td>
        </tr>
    </table>
</div>

<h2> Gerenciamento de pacotes (UBUNTU / DEBIAN) </h2>

<div>
    <table>
        <tr>
            <th> Comandos </th>
            <th> Descrições </th>
            <th> Exemplos </th>
        </tr>
        <tr>
            <td> apt + list </td>
            <td> Listagem de pacotes disponíveis para instalação. </td>
            <td> apt list </td>
        </tr>
        <tr>
            <td> apt + list + nome do pacote </td>
            <td> Procurando pacotes sobre certo programa. </td>
            <td> apt list vlc </td>
        </tr>
        <tr>
            <td> apt + install + nome do pacote </td>
            <td> Instalando o programa no sistema. </td>
            <td> apt install vlc </td>
        </tr>
        <tr>
            <td> apt + install + vlc + -y </td>
            <td> Instalando o programa sem perguntar. </td>
            <td> apt install vlc -y </td>
        </tr>
        <tr>
            <td> apt + remove + nome do pacote </td>
            <td> Remove apenas o programa. </td>
            <td> apt remove vlc </td>
        </tr>
        <tr>
            <td> apt + update </td>
            <td> Atualiza os pacotes do sistema. </td>
            <td> apt update </td>
        </tr>
        <tr>
            <td> apt + upgrade </td>
            <td> Atualiza o sistema operacional. </td>
            <td> apt upgrade </td>
        </tr>
    </table>
</div>

<h2> Gerenciamento de pacotes (FEDORA / RED HAT / CenTOS) </h2>

<div>
    <table>
        <tr>
            <th> Comandos </th>
            <th> Descrições </th>
            <th> Exemplos </th>
        </tr>
        <tr>
            <td> dnf + list </td>
            <td> Listagem de pacotes disponíveis para download. </td>
            <td> dfn list </td>
        </tr>
        <tr>
            <td> dnf + search + pacote </td>
            <td> Procurar determinado pacote. </td>
            <td> dnf search vlc </td>
        </tr>
        <tr>
            <td> dnf + install + pacote </td>
            <td> Instalação do pacote. </td>
            <td> dnf install nano  </td>
        </tr>
        <tr>
            <td> dnf + update </td>
            <td> Atualização de pacotes. </td>
            <td> dnf update </td>
        </tr>
    </table>
</div>

<h2> Realizando instalações via SNAP (FEDORA) </h2>

<div>
    <table>
        <tr> 
            <th> Comandos </th>
            <th> Descrições </th>
            <th> Exemplos </th>
        </tr>
        <tr>
            <td> dnf + install + snapd </td>
            <td> Instalando suporte aos pacotes snap. </td>
            <td> dnf install snapd </td>
        </tr>
        <tr>
            <td> snap + install + gimp </td>
            <td> Instalando gimp do pacote snap. </td>
            <td> snap install gimp </td>
        <tr>
    </table>
</div>

<h2>  Renoemando / Movendo arquivos </h2>

<div>
    <table>
        <tr>
            <th> Comandos </th>
            <th> Descrições </th>
            <th> Exemplos </th>
        </tr>
        <tr>
            <td> cp + arquivo local + arquivo clone </td>
            <td> Criando uma cópia de um arquivo. </td>
            <td> cp arquivo.txt arquivo2.txt </td>
        </tr>
        <tr>
            <td> mv + arquivo local + novo nome do arquivo. </td>
            <td> Renoemando o arquivo original para outro. </td>
            <td> mv arquivo.txt teste.txt </td>
        </tr>
        <tr>
            <td> mv + caminho atual + caminho destino. </td>
            <td> Movendo arquivo do caminho atual para outro. </td>
            <td> mv /home/dev-alexandre17/teste.txt /lib </td>
        </tr>
        <tr>
            <td> mv + caminho com barra e * + caminho destino </td>
            <td> Movendo tudo de um diretório para o caminho destino. </td>
            <td> mv /home/dev-alexandre17/* /lib </td>
        </tr>
    </table>
</div>

<h2> Copiando arquivos </h2>

<div>
</div>

<p> Em caso de dúvidas, faça uma issue neste repositório :) </p>
<p> Gostou dos comandos? Deixe seu ⭐ para contribuir! </p>
