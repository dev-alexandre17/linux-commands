<h1> Navegação pelo sistema de arquivo </h1>

<h2> Comandos </h2>

<div align="center">
    <table>
        <tr>
            <th> Comando </th>
            <th> Descrição </th>
            <th> Exemplo </th>
        </tr>
        <tr>
            <td> date </td>
            <td> Verificar a data e hora atual. </td>
            <td> ... </td>
        </tr>
        <tr>
            <td> clear </td>
            <td> Limpa o console por completo. </td>
        <td> ... </td>
        </tr>
        <tr>
            <td> ctrl + l </td>
            <td> Apaga a última página de comandos no terminal. </td>
            <td> ... </td>
        </tr>
        <tr>
            <td> pwd </td>
            <td> Específica o caminho do diretório onde você está atualmente. </td>
            <td> ... </td>
        </tr>
        <tr>
            <td> cd + nome da pasta </td>
            <td> Entra no diretório. 
            <td> ... </td>
        </td>
        <tr>
            <td> ls </td>
            <td> Lista o que você possui no diretório: nada, diretório/s, arquivos. </td>
            <td> ... </td>
        </tr>
        <tr>
            <td> cd .. </td>
            <td> Volta para uma pasta anterior da atual.
            <td> ... </td>
        </tr>
        <tr>
            <td> cd + letras inicias do diretório + tab </td>
            <td> Autocomplete para entrar na pasta de forma rápida ou sugerir diretórios correspondente as letras informadas. </td>
            <td> ... </td>
        </tr>
   </table>
</div>

<h2> Filtrando a exibição de arquivos - parte 1 </h2>

<div align="center">
    <table>
        <tr>
            <th> Comando </th>
            <th> Descrição </th>
            <th> Exemplo </th>
        </tr>
        <tr>
            <td> ls | more </td>
            <td> Filtra mais informações, use ctrl + c para sair da listagem. </td>
            <td> ... </td>
        </tr>
        <tr>
            <td> ls + nome do diretório </td>
            <td> Lista todas as informações contidas na pasta, mesmo você estando dentro ou fora do diretório. </td>
            <td> ... </td>
        </tr>
        <tr>
            <td> ls + letra ou letras + * </td>
            <td> Mostra todos os conteúdos começando com a letra desejada. </td>
            <td> ... </td>
        </tr>
        <tr>
            <td> ls + letra + ? + letra + * </td>
            <td> Apresenta dados com o primeiro e terceiro caractere, <br> na interrogração, será feito por uma busca seja uma letra/número entre os caracteres. </td>
            <td> ... </td>
        </tr>
    </table>
</div>

<h2> Filtrando a exibição de arquivos - parte 2 </h2>

<div align="center">
    <table>
        <tr>
            <th> Comando </th>
            <th> Descrição </th>
            <th> Exemplo </th>
        </tr>
        <tr>
            <td> touch + nome do arquivo + extensão </td>
            <td> O comando touch é usado para gera um ou mais arquivos vazios simultaneamente, independente da extensão. </td>
            <td> touch arquivo.txt ou touch arquivo.txt arquivo1.txt </td>
        </tr>
        <tr>
            <td> ls + nome do arquivo + intervalo entre colchetes + extensão </td>
            <td> Mostra os arquivos que estão entre o intervalo requisitado. </td>
            <td> Comando 1 - touch arquivo2.txt arquivo3.txt arquivo4.txt <br>
            Comando 2 - ls arquivo[2-4].txt <br>
            Resultado: arquivo2.txt arquivo3.txt arquivo4.txt </td>
            </td>
        </tr>
        <tr>
            <td> ls + nome do arquivo + intervalo entre colchetes com vírgula + extensão </td>
            <td> Faz a listagem dos arquivos referente as numerações. </td>
            <td> Comando 1 - touch arquivo2.txt arquivo3.txt arquivo4.txt <br>
            Comando 2 - ls arquivo[2,4].txt <br>
            Resultado: arquivo2.txt arquivo4.txt </td>
        </tr>
        <tr>
            <td> ls + nome do arquivo + intevalo entre parênteses usando acento circunflexo e vírgula + extensão </td>
            <td> Ignora as numerações dentro do intervalo e mostra todos os outros arquivos restantes. </td>
            <td> Comando 1 - touch arquivo2.txt arquivo3.txt arquivo4.txt <br>
            Comando 2 - ls arquivo[^2,4].txt <br>
            Resultado: arquivo3.txt </td>
        </tr>
    </table>
</div>

<h2> Localizando arquivo </h2>

<div align="center">
    <table>
        <tr>
            <th> Comando </th>
            <th> Descrição </th>
            <th> Exemplo </th>
        </tr>
        <tr>
            <td> ls + nome do diretório + letra </td>
            <td> Procurando arquivos com determinada letra sem estar presente no diretório que esteja buscando. </td>
            <td> ... </td>
        </tr>
        <tr>
            <td> find -name + nome do arquivo </td> 
            <td> Vasculha o arquivo na raíz do seu sistema, caso você simplesmente não lembra. </td>
            <td> ... </td>
        </tr>
    </table>
</div>

<h2> Criando diretórios </h2>

<div align="center">
    <table>
        <tr>
            <th> Comando </th>
            <th> Descrição </th>
            <th> Exemplo </th>
        </tr>
    </table>
</div>
