#Curso-HTML5
<html>
<body>
  
<h1>HTML5 - Linguagem de Marcação de Hipertexto</h1>
<p><q>HyperText Markup Language</q>  - <a href="">Timothy John Berners-Lee</a></p>
<p>Os hipertextos são a junção de vários elementos — palavras, vídeos e conteúdos —, que, quando conectados, estabelecem uma rede de dados que permite a comunicação, o armazenamento e o compartilhamento de informações</p>
<p>Por exemplo, ao visitar um website, você encontra diversas informações com formatações diferentes, como parágrafos, bullets e fontes distintas. Pois então, essa estruturação é realizada por meio do HTML.</p>
<h1>ATRIBUTOS GLOBAIS</h1>
<p>São os atributos comuns a todos os elementos HTML; não tem efeitos em alguns elementos.</p>
<p>Devem ser colocados dentro das tags de abertura</p>
<h2>NOMENCLATURA</h2>
<p>Veja a aplicação no repositório GitHub</p>

<ul>
    <li><a href="https://developer.mozilla.org/pt-BR/docs/Web/HTML/Global_attributes/accesskey">acceskey</a></li>  
    <li><a href="https://developer.mozilla.org/pt-BR/docs/Web/HTML/Global_attributes/class">class</a></li>
    <li><a href="https://developer.mozilla.org/pt-BR/docs/Web/HTML/Global_attributes/contenteditable">contenteditable</a></li>
    <li><a href="https://developer.mozilla.org/pt-BR/docs/Learn/HTML/Howto/Use_data_attributes">data</a></li>
    <li><a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/dir">dir</a></li>
    <li><a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/draggable">dragabble</a></li>
    <li><a href="https://pt.stackoverflow.com/questions/119025/utilidade-do-novo-atributo-global-dropzone-no-html5">dropzone</a></li>
    <li><a href="https://developer.mozilla.org/pt-BR/docs/Web/HTML/Global_attributes/hidden">hidden</a></li>
    <li><a href="https://developer.mozilla.org/pt-BR/docs/Web/HTML/Global_attributes/id">id</a></li>
    <li><a href="https://developer.mozilla.org/pt-BR/docs/Web/HTML/Global_attributes/lang">lang</a></li>
    <li><a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/spellcheck">spellcheck</a></li>
    <li><a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/style">style</a></li>
    <li><a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/tabindex">tabindex</a></li>
    <li><a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/title">title</a></li>
    <li><a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/translate"></a>translate</li>

</ul>

<h1>Eventos</h1>
<p>São gatilhos disparados devido alguma interação do Usuário</p>
<p>Exemplo de Eventos: Janela, Formulário, Teclado, Mouse, Arrasto, Transferência, Mídia e etc...</p>
<p>Deve ter o prefixo <q>on</q></p>

<h2>Evento Janela</h2>
<ul>
    <li>afterprint - Disparado depois da página ser impressa</li>
    <li>beforeprint - Disparado antes da página ser impressa</li>
    <li>beforeunload - Disparado quando antes do navegador carregar outra página</li>
    <li>error - Disparado quando ocorre um erro</li>
    <li>hashchange - Disparado quando o hash da url da página é alterado</li>
    <li>load - Disparado quando toda página for carregada.</li>
    <li>message - Disparado quando ocorre uma mensagem</li>
    <li>offline - Disparado quando o navegador é desconectado da internet</li>
    <li>online - Disparado quando o navegador é conectado a internet</li>
    <li>pagehide - Disparado quando a página é ocultada</li>
    <li>pageshow - Disparado quando a página é mostrada</li>
    <li>popstate - Disparado quando a ocorrência no histórico do navegador é alterada</li>
    <li>resize - Disparado quando a janela é redimensionada</li>
    <li>storage - Disparado quando o armazenamento do navegador é alterado</li>
    <li>unload - Disparado quando o usuário atualiza a página ou fecha a Janela</li>
</ul>

<h2>Evento Formulário</h2>
<ul>
    <li>blur - Disparado quando o foco do elemento é removido</li>
    <li>change - Disparado quando termina de alterar o valor do elemento</li>
    <li>contextmenu - Disparado quando o usuário abre o menu de contexto</li>
    <li>focus - Disparado quando o elemento é focado</li>
    <li>input - Disparado quando o elemento recebe uma entrada de valor</li>
    <li>invalid - Disparado quando o valor do elemento é invalido</li>
    <li>reset - Disparado quando o valor do elemento é redefinido ao estado inicial</li>
    <li>search - Disparado quando o elemento input do tipo search é enviado</li>
    <li>select - Disparado quando o valor do elemento é selecionado</li>
    <li>submit - Disparado quando o formulário é enviado</li>
</ul>

<h2>Evento Teclado</h2>
<ul>
    <li>keydown - Disparado quando a tecla vai para baixo</li>
    <li>keypress - Disparado quando a tecla é pressionada</li>
    <li>keyup - Disparado quando a tecla é solta</li>
</ul>

<h2>Evento Mouse</h2>
<ul>
    <li>click - Disparado quando o elemento recebe um clique</li>
    <li>dbclick - Disparado quando o elemento recebe um click duplo</li>
    <li>mousedown - Disparado quando o botão do clique vai para baixo</li>
    <li>mousemove - Disparado quando o cursor do mouse se move sobre o elemento</li>
    <li>mouseout - Disparado quando o cursor do mouse não está em cima do elemento.</li>
    <li>mouseover - Disparado quando o cursor do mouse está em cima do elemento</li>
    <li>mouseup - Disparado quando o botão do clique é solto</li>
    <li>wheel - Disparado quando a roda do mouse é rodada</li>
    <li>mouseenter - Disparado quando o cursor do mouse entra em cima do elemento</li>
    <li>mouseleave - Disparado quando o cursor do mouse sai de cima do elemento.</li>
</ul>

<h2>Evento Arrasto</h2>
<ul>
    <li>drag - Disparado quando o elemento é arrastado</li>
    <li>dragend - Disparado quando o elemento para de ser arrastado</li>
    <li>dragenter - Disparado quando o elemento arrastado entra em um elemento que permite soltar</li>
    <li>dragleave - Disparado quando o elemento arrastado sai de cima de um elemento que permite soltar</li>
    <li>dragover - Disparado quando o elemento arrastado passa em um elemento que permite soltar</li>
    <li>dragstart - Disparado quando o elemento começa a ser arrastado</li>
    <li>drop - Disparado quando o elemento é solto</li>
    <li>scroll - Disparado quando o scroll é rolado</li>
</ul>

<h2>Evento Transferência</h2>
<ul>
    <li>Copy - Disparado quando o conteúdo é copiado.</li>
    <li>Cut - Disparado quando o conteúdo do elemento é recortado</li>
    <li>Paste - Disparado quando o conteúdo é colado.</li>
</ul>

<h2>Evento Mídia</h2>
<ul>
<li>abort - Disparado quando o carregamento de mídia é disparado</li>
<li>canplay - Disparado quando a mídia carregou o suficiente para começar</li>
<li>canplaythrough - Disparado quando a midia carregou e pode ser produzida até o final</li>
<li>cuechange - Disparado quando o texto de uma trila é alterado</li>
<li>durationchange - Disparado quando o tamanho total da mídia é alterado</li>
<li>emptied - Disparado quando acontece algum problema e a mídia fica indisponível</li>
<li>ended - Disparado quando mídia foi consumida até o fim</li>
<li>error - Disparado quando um erro acontece</li>
<li>loadeddata - Disparado quando os dados da mídia são carregados</li>
<li>loadedmetadata - Disparado quando os metadados da mídia são carregados</li>
<li>loadstart - Disparado quando os dados da mídia começam a serem carregados</li>
<li>pause - Disparado quando a mídia é pausada</li>
<li>play - Disparado quando a mídia é começada</li>
<li>playing - Disparado depois que a mídia realmente começou</li>
<li>progress - Disparado enquanto o navegador obtém os dados da mídia</li>
<li>ratechange - Disparado quando a taxa de reprodução é alterada</li>
<li>seeked - Disparado quando a busca de dados terminou</li>
<li>seeking - Disparado quando a busca de dados da mídia está acontecendo</li>
<li>stalled - Disparado quando o navegador não pode buscar os dados de mídia por qualquer motivo</li>
<li>suspend - Disparado antes de ser completamente carregado</li>
<li>timeupdate - Disparado quando a posição da reprodução é alterado</li>
<li>volumechange - Disparado quando o volume do áudio da mídia é alterado</li>
<li>waiting - Disparado quando a mídia é pausada para armazenar mais dados em buffler</li>
</ul>

<h2>Outros eventos</h2>
<ul><li>toggle - Disparado quando o usuário abre ou fecha o elemento Details</li></ul>

</body>
</html>