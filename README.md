Pequeno script feito para achar pessoas de algum evento no facebook, para utilizá-lo é super simples.

1) Vá até o evento que deseja achar  a pessoa (seja pra adicionar ou confirmar se ela está lá mesmo).

2) Clique nos convidados até abrir o pop-up dos "Interessados", "Confirmaram presença" e "Convidados", clique com o scroll do mouse e role até em baixo  para ele carregar a lista de todas as pessoas.

3) Inspecione o elemento, F12 ou botão direito > Inspecionar elemento.

4) Vá até a div com classe "_4-i2 _50f4" (<div class="_4-i2 _50f4"> ela é igual para todos os eventos. e edite o bloco como HTML, botão direito > Editar como HTML

5) Cole o conteúdo do script getGuests.js ou simplesmente instancie-o (<script src="getGuests.js"> </script>). Se for instanciar, salve o conteudo em um .html na mesma pasta, para não dar erro, ou instancia o caminho da pasta zzz. Caso queira só colar o código, salve todo o bloco em um .html somente.

6) Feito isso, só abrir seu arquivo .html e com o CTRL + F achar a pessoa querida =) ENJOOOY
