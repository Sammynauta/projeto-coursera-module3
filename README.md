# projeto-coursera-module3

## REVISAO

Como estamos usando o Bootstrap para esta tarefa, em vez de especificar intervalos de pixels, definirei nossas visualizações de desktop, tablet e móvel em termos de prefixos de classe CSS do Bootstrap, ou seja, md, sm e xs.

    A ilustração da maquete da área de trabalho deve corresponder às classes baseadas em Bootstrap MD
    A ilustração da maquete do tablet deve corresponder às classes baseadas em Bootstrap sm
    A ilustração da maquete móvel deve corresponder às classes baseadas em Bootstrap xs

    Navbar: Crie uma barra de navegação que rola junto com a página (a barra de navegação deve se tornar invisível e não é fixada no topo quando você rola a página para baixo). O navbar deve ter um nome de empresa (ou seja, classe de marca navbar) chamado "Food, LLC" que está alinhado ao lado esquerdo da navbar. (Consulte https://getbootstrap.com/docs/3.3/components/#navbar. Torne a janela do navegador mais estreita para ver o botão de menu móvel aparecer no primeiro exemplo mostrado no link fornecido.)

    Para visualização em desktop e tablet, a barra de navegação não deve conter mais nada. Nenhum outro botão deve estar visível. (Dica: use a classe 'visible-xs'.)

    Navbar - Visualização Móvel: Crie um botão de menu simples (3 barras horizontais). Quando o usuário clica nesse botão, um menu suspenso deve aparecer (conforme ilustrado na ilustração do Mobile Open Menu abaixo). O menu suspenso deve conter 3 itens: frango, carne e sushi.

    O menu suspenso deve ocupar toda a largura da janela do navegador. Certifique-se de que o menu suspenso tenha um conjunto de cores de fundo que o diferencie do resto do conteúdo.

    (Dica: consulte https://getbootstrap.com/docs/3.3/components/#navbar e Aula 31 para exemplos de como fazer isso.)

    Título da página. O título da página que diz Nosso Menu deve estar centralizado na janela do navegador. Você deve usar uma classe Bootstrap para fazer isso.

    (Dica: procure uma classe Bootstrap que centre o texto, consulte https://getbootstrap.com/docs/3.3/css/#type-alignment.)

    Crie uma única seção realmente alta que usará o Bootstrap Grid e ocupará toda a largura da janela do navegador (sem algumas margens, é claro) para todas as visualizações: desktop, tablet e celular. Para tornar a seção realmente alta, você pode preenchê-la com MUITO texto ou simplesmente definir sua altura para algo como 1000px. Ele precisa ser alto o suficiente para que seja necessário rolar para baixo para visualizar a parte inferior da seção. Certifique-se de que a cor de fundo esteja definida para distingui-lo do resto do conteúdo. (Dica: não se esqueça de ter um elemento com class = 'container' ou class = 'container-fluid' envolvendo sua grade. Lembre-se de que para que a grade faça algo "sempre", ou seja, não importa o tamanho da janela do navegador , use as classes col-xs -.... Nesse caso, como queremos que a seção ocupe toda a linha, use col-xs-12.)