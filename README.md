<h1> Navegação pelo sistema de arquivo </h1>

<h2> Comandos </h2>

<div align="center">
    <table>
        <tr>
            <th> Comando </th>
            <th> Descrição </th>
            <th> Resultado</th>
        </tr>
        <tr>
            <td> date </td>
            <td> Verificar a data e hora atual. </td>
            <td> qui 27 jan 2022 18:01:39 -03
        </td>
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
            <td> /home/dev-alexandre </td>
        </tr>
        <tr>
            <td> cd + nome da pasta </td>
            <td> Entra no diretório que foi informado. 
            <td> /home/dev-alexandre/workspace </td>
        </td>
        <tr>
            <td> ls </td>
            <td> Lista o que você possui no diretório: nada, diretório/s, arquivos. </td>
            <td> linux-commands  Marketsoft_StartLatam </td>
        </tr>
        <tr>
            <td> cd .. </td>
            <td> Volta para uma pasta anterior da atual.
            <td> /home/dev-alexandre/ </td>
        </tr>
        <tr>
            <td> cd + letras inicias do diretório + tab </td>
            <td> Autocomplete para entrar na pasta de forma rápida ou sugerir diretórios correspondente as letras informadas. </td>
            <td> Desktop/ Documents/ Downloads/ </td>
        </tr>
   </table>
</div>

<h2> Filtrando a exibição de arquivos - parte 1 </h2>

<div align="center">
    <table>
        <tr>
            <th> Comando </th>
            <th> Descrição </th>
            <th> Resultado </th>
        </tr>
        <tr>
            <td> ls | more </td>
            <td> Filtra mais informações sobre o diretório que você está, aperte enter continuar visualizando mais dados e use ctrl + c para sair da lista. </td>
            <td> 2to3 <br> --more-- </td>
        </tr>
        <tr>
            <td> ls + nome do diretório </td>
            <td> Lista todas as informações contidas na pasta. </td>
            <td> linux-commands  Marketsoft_StartLatam </td>
        </tr>
        <tr>
            <td> ls + letra ou letras + * </td>
            <td> Mostra todos os conteúdos começando com a letra desejada. </td>
            <td> brave-bin-1.34.81.zip  </td>
        </tr>
        <tr>
            <td> ls + letra + ? + letra + * </td>
            <td> Apresenta dados com o primeiro e terceiro caractere, <br> na interrogração, será feito por uma busca seja uma letra/número entre os caracteres.               </td>
            <td> brave-bin-1.34.81.zip </td>
        </tr>
    </table>
</div>

<h2> Filtrando a exibição de arquivos - parte 2 </h2>

<div align="center">
    <table>
        <tr>
            <th> Comando </th>
            <th> Descrição </th>
            <th> Resultado </th>
        </tr>
        <tr>
            <td> touch + nome do arquivo + extensão </td>
            <td> O comando touch é usado para gera um ou mais arquivos vazios simultaneamente. </td>
            <td> touch arquivo.txt </td>
        </tr>
        <tr>
            <td> ls + nome do arquivo + intervalo entre colchetes + extensão </td>
            <td> Mostra os arquivos que estão entre o intervalo requisitado. </td>
            <td> arquivo2.txt arquivo3.txt arquivo4.txt </td>
            </td>
        </tr>
        <tr>
            <td> ls + nome do arquivo + intervalo entre colchetes com vírgula + extensão </td>
            <td> Faz a listagem dos arquivos referente as numerações. </td>
            <td> arquivo2.txt arquivo4.txt </td>
        </tr>
        <tr>
            <td> ls + nome do arquivo + intevalo entre parênteses usando acento circunflexo e vírgula + extensão </td>
            <td> Ignora as numerações dentro do intervalo e mostra todos os outros arquivos restantes. </td>
            <td> arquivo3.txt </td>
        </tr>
    </table>
</div>

<h2> Localizando arquivo </h2>

<div align="center">
    <table>
        <tr>
            <th> Comando </th>
            <th> Descrição </th>
            <th> Resultado </th>
        </tr>
        <tr>
            <td> ls + nome do diretório + letra </td>
            <td> Procurando arquivos com determinada letra sem estar presente no diretório que esteja buscando. </td>
            <td> README.md </td>
        </tr>
        <tr>
            <td> find -name + nome do arquivo </td> 
            <td> Vasculha o arquivo na raíz do seu sistema e mostra o caminho localizado, caso você simplesmente não lembra. </td>
            <td> ./brave-bin/src/brave/brave </td>
        </tr>
    </table>
</div>

<h2> Criando diretórios </h2>

<div>
    <table>
        <tr>
            <th> Comando </th>
            <th> Descrição </th>
            <th> Resultado </th>
        </tr>
        <tr>
            <td> cd ~ </td>
            <td> Direciona para a home do seu perfil. </td>
            <td> /home/dev-alexandre </td>
        </tr>
        <tr>
            <td> mkdir + nome da pasta </td>
            <td> Cria uma pasta. </td>
            <td> workspace </td>
        </tr>
        <tr>
            <td> mkdir + caminho do diretório + nome da pasta </td>
            <td> Indica onde será criada a pasta. </td>
            <td> workspace </td>
        </tr>
        <tr>
            <td> mkdir + "nome da pasta" </td>
            <td> Cria uma pasta com o nome separado. </td>
            <td> receita de bolo </td>
        </tr>
    </table>
</div>

<p> Em caso de dúvidas, faça uma issue neste repositório :) <p>
<p> Gostou dos comandos? Deixe seu ⭐ para contribuir! </p>
