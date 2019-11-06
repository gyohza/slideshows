<!--
    http://deckdown.org/
-->

# Processamento de Imagem

# Técnicas de Meio-Tom

* Daniel Nagaoka
* Elen Caroline Perigo
* Vanderlei Paixão

## Definição

**Meio-tom** é a técnica reprográfica que simula gradientes por meio do uso de **pontos**.

Os pontos podem variar em **tamanho** e **espaçamento**.

---

A imagem criada pela técnica também pode ser referida pelo nome "meio-tom".

---

<img alt="Exemplo_1" src="http://www.leftcoast.com/images/guidelines_halftone_printed.jpg" />

---

Ao passo que imagens de tom contínuo possuem uma gama infinita de tons de cinza (**não, não são cinquenta**), o processo de meio-tom reduz a reprodução a uma imagem que pode ser impressa com apenas um tom de tinta.

---

<img alt="Exemplo_2" height="600" src="https://media.istockphoto.com/vectors/bighorn-sheep-halftone-vector-id500018045" />

---

Esse tipo de reprodução apoia-se em uma ilusão ótica simples:

Quando os pontos são pequenos, o olho humano interpreta os padrões como se fossem tons graduais.

## História

Historicamente, figuras em jornais eram cravadas em blocos de madeira - à mão.

Apesar de copiadas de diretamente de fotos, inevitavelmente possuíam aparência de arte manual.

---

Com o passar do tempo, impressoras comerciais procuravam uma maneira prática de reproduzir fotos de forma realística em suas impressões.

No entanto, os processos mais comuns apenas imprimiam em blocos com tinta ou os deixavam em branco, incapazes de reproduzir um efeito gradiente.

---

<img alt="William_Talbot" src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/39/William_Henry_Fox_Talbot%2C_by_John_Moffat%2C_1864.jpg/220px-William_Henry_Fox_Talbot%2C_by_John_Moffat%2C_1864.jpg" />

Eis que, em 1852, o inglês _William Fox Talbot_ patenteou uma ideia em que sugeria o uso de telas ou véus fotográficos em conjunto com entalhamento.

Vários tipos de tela foram propostos nas décadas seguintes, mas com pouco sucesso.

---

<img alt="Frederic_Ives" height="400" src="http://scihi.org/wp-content/uploads/2015/02/Frederic_Eugene_Ives_001-662x1024.jpg" />

O primeiro método bem sucedido foi o de **Frederic Ives**.

Apesar de não ter usado telas, ele inventou uma maneira acessível de produzir os pontos para o efeito meio-tom.

---

<img alt="Kromogram" height="500" src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/86/Kromogram_No_1_Vase_of_flowers_circa_1896_large.jpg/1024px-Kromogram_No_1_Vase_of_flowers_circa_1896_large.jpg" />

Ives também foi pioneiro na produção de fotografias coloridas.

## Técnicas

### Screening

Consiste na utilização de tecidos espessos, suspensos à frente da placa da câmera a ser exposta, no intuito de quebrar a luz em um padrão de pontos via uma combinação de padrões de interrupção e difração.

### _Halftoning_ Tradicional

Utiliza telas com aglomeração de pontos.

A **resolução** é determinante na quantidade de detalhes que podem ser reproduzidos.

Várias telas podem ser empregadas para, por exemplo, impressões coloridas.

---

Quando diferentes telas são combinadas, alguns efeitos visuais poluentes podem ocorrer, como padrões **_moiré_**:

<img alt="Metodo_Tradicional" src="https://pacificgraphicdesign.files.wordpress.com/2012/03/moire-example-1.jpg" />

---

O problema pode ser reduzido rotacionando-se as telas, uma em relação à outra:

<img alt="Camadas_rotacionadas" src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ef/Halftoningcolor.svg/450px-Halftoningcolor.svg.png" />

### _Halftoning_ Digital

Técnicas de meio-tom digital utilizam imagens matriciais (raster/bitmap).

Em cada ponto cromático uma determinada cor pode estar ativa (1) ou inativa (0) - isto é, imagens são formadas a partir de dados binários.

<img alt="Halftoning_Digital" height="400" src="https://nullprogram.com/img/halftone/halftone-eye-thumb.png" />

### _Halftoning_ Inverso

Técnicas de inversão de meio-tom procuram desfazer o efeito pontilhado causado pelo meio-tom, convertendo a imagem em uma imagem de tom contínuo.

<img alt="Halftoning_Inverso" height="400" src="https://ai2-s2-public.s3.amazonaws.com/figures/2017-08-08/7aa98713e83a4b9dd5f1bccc3db39a3956d91e46/3-Figure4-1.png" />

---

A proposta apresenta evidentes problemas:

* Vários detalhes são inconversivelmente perdidos no processo de conversão a meio-tom;
* Duas imagens distintas poderiam hipoteticamente produzir uma mesma imagem meio-tom;
* A imagem produzida, então, poderia ter mais do que uma possível reconstrução;
* Como há vários padrões de meio-tom, não fica sempre evidente o algoritmo mais indicado para alcançar a melhor qualidade de reconstrução.

### `BÔNUS`

<img alt="CAGI_Folks" height="500" src="https://cdn.fstoppers.com/styles/large-16-9/s3/lead/2019/08/eb7ff9947f527a2e84d7f06e79138b82.png" />

<br/>
<br/>

### _Color Assimilation Grid Illusion_

<img alt="CAGI_Folks" height="500" src="https://cdn.fstoppers.com/styles/large-16-9/s3/lead/2019/08/eb7ff9947f527a2e84d7f06e79138b82.png" />

_A foto acima é em preto e branco_ - apenas a grade que a sobrepõe possui cores.

---

A ilusão é causada pelas cores super-saturadas da grade sobre a imagem completamente dessaturada (em outras palavras, em preto e branco).

<img alt="CAGI_Classroom" height="300" src="https://cdn.fstoppers.com/styles/full/s3/media/2019/08/01/screen_shot_2019-08-01_at_14.52.22.png" />

A imagem foi criada pelo artista e desenvolvedor do projeto GIMP, Øyvind Kolås. GIMP é um editor de imagens gratuito distribuído sob a licença GNU.

Kolås também experimentou com outros padrões como, por exemplo...

---

... pontos.

<img alt="CAGI_dots" height="500" src="https://www.sciencealert.com/images/2019-07/015-colour-grid-optical-illusion-3.jpg" />

Kolås abertamente empregou os pontos em uma evidente analogia a técnicas de meio-tom.

---

E também não tinha ninguém para impedi-lo de tentar com listras...

<img alt="CAGI_stripes" height="500" src="https://pbs.twimg.com/media/EAVgouGWwAMBfcF?format=jpg&name=small" />

Sei lá.

---

E tem isso, também:

(juro que só tem 30 segundos)

<iframe width="800" height="450" src="https://www.youtube.com/embed/7jJ10OZH2SU" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Obs.: O vídeo original foi produzido pelo Instituto Blender, usando a ferramenta de mesmo nome.

# Fin

## Referências

* CAMPBELL, Alastair. **The Designer's Lexicon.** Chronicle, San Francisco, 2000.
* TWYMAN, Michael. **Printing 1770-1970: an illustrated history of its development and uses in England.** Eyre & Spottiswoode, London, 1970.
* MEGGS, Philip B. **A History of Graphic Design.** John Wiley & Sons, 1998.
* ALEXANDER, Jack. **These Grid Lines on Black-And-White Photos Trick Your Brain Into Seeing Colors**. Fstoppers, 2019.
* DOCKRILL, Peter. **This Photo Is Black And White. Here's The Science That Makes Your Brain See Colour**. Science Alert, 2019.
