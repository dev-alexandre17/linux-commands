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

<p> Em caso de dúvidas, faça uma issue neste repositório :) <p>
<p> Gostou dos comandos? Deixe seu ⭐ para contribuir! </p>
