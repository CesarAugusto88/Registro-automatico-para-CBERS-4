<h1>Registro-automatico-para-CBERS-4</h1>
<h3>Projeto da Disciplina: Introdução à Programação com Dados Geoespaciais (INPE)</h3>

<p align="justify">O objetivo do projeto foi construir um script em Python para estimar o deslocamento existente entre imagens PAN10 e PAN5 (nível L2). Foi realizada a reamostragem da imagem PAN5. Além de estimar, o script altera as informações de box das imagens PAN10 para a mesma posição da PAN5.

Com o script é possível realizar uma fusão das imagens antes e após os registro. As imagens de teste do satélite CBERS-4 possui o sensor PAN, com 3 bandas PAN10 (green B2, red B3, nir B4) e 1 banda pancromática (PAN5 B1).

Para cumprir o objetivo do trabalho, pode-se assumir que as bandas B2, B3 e B4 estão co-registradas, mas estão deslocadas em relação à B1 (referência). No script foi usado bibliotecas que realizam o registro obtendo pontos homólogos entre as imagens de referência e alvo, gerando uma nova matriz da imagem corrigida. Por meio de deslocamentos é encontrado as distâncias a serem corrigidas nos eixos x e/ou y, a posição que obtive a maior semelhança pode ser indicada como o deslocamento necessário para alinhar B2/B3/B4 com a referência B1.
</p>
<br>

Obs:
O relatório produzido foi escrito conforme o template disponível para o (GEOINFO)[https://www.overleaf.com/read/xtnkjtmtzrwt].

<h2>Fluxograma de funcionamento</h2>

<p align="center"><img src="https://github.com/CesarAugusto88/Registro-automatico-para-CBERS-4/blob/main/Fluxograma2.png">

<p align="center"><img src="https://upload.wikimedia.org/wikipedia/commons/1/1f/Python_logo_01.svg" width="150" 
     height="150"> <img src="https://upload.wikimedia.org/wikipedia/commons/5/5a/Satellite_icon1.png" width="150" 
     height="150"> </p>
     
   <p>&copy; 2023 Barbara Marie Van Sebroeck Lutiis S. Martins, Cesar Augusto de Moraes Costa, Júlio Cesar Pimenta dos Santos, Pedro Ferrini Manh ̃aes Bacellar, Tassio Koiti Igawa</p>
