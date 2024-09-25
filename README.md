#Flexbox

<p align="center">O que vamos aprender sobre flexbox? </p>
<p align="center">
  <a>Noções Básicas de Flexbox e </a>
  <a>Suas Principais Propriedades :rocket: </a>
</p>

  ##  O que é Flexbox?

  Flexbox é um modelo de layout introduzido no CSS que permite organizar os elementos em um contêiner de forma flexível, adaptável e eficiente. Ele foi projetado para alinhar e distribuir o espaço entre os itens dentro de um contêiner, mesmo quando o tamanho dos itens é dinâmico ou desconhecido.

  ## Noções Básicas:  :memo:

  O Flexbox é ativado ao definir a propriedade display: flex em um contêiner. Os itens dentro desse contêiner se tornam flex items, e a disposição deles pode ser controlada usando várias propriedades associadas ao Flexbox.

Aqui está uma representação visual de um layout utilizando Flexbox. A imagem mostra três caixas coloridas (azul, verde e vermelha) alinhadas horizontalmente com espaçamento uniforme entre elas, ilustrando o uso da propriedade justify-content: space-between. Isso demonstra como o Flexbox facilita o alinhamento de itens em um contêiner de forma eficiente.

w
     "![fotogit](https://github.com/user-attachments/assets/c94b5849-12bd-4f20-97f4-85136c1559cf)"
     
### Termos Importantes :computer: :

Flex Container: O elemento que tem display: flex ou display: inline-flex. Este elemento contém os itens flexíveis.

Flex Items: São os elementos filhos diretos de um contêiner flexível. Eles se ajustam de acordo com as propriedades aplicadas ao contêiner ou a eles mesmos.

#### Principais Propriedades do Flex Conteiner  :fire: :

* display:

  Ativa o Flexbox no contêiner.
  Exemplo: display: flex; ou display: inline-flex;

* flex-direction: Define a direção principal do layout.

   Opções:
   row (padrão): Alinha os itens em uma linha horizontal.
   row-reverse: Inverte a ordem dos itens em uma linha horizontal.
   column: Alinha os itens em uma coluna vertical.
   column-reverse: Inverte a ordem dos itens em uma coluna vertical.
   Exemplo: flex-direction: row;

* justify-content: Controla o alinhamento dos itens ao longo do eixo principal.

   Opções:
  flex-start: Alinha os itens no início.
  flex-end: Alinha os itens no final.
  center: Centraliza os itens.
  space-between: Espaçamento igual entre os itens.
  space-around: Espaçamento igual ao redor dos itens.
  Exemplo: justify-content: center;

* align-items: Controla o alinhamento dos itens ao longo do eixo perpendicular (vertical, se flex-direction: row).

  Opções:
  flex-start: Alinha os itens no topo.
  flex-end: Alinha os itens no final.
  center: Centraliza os itens.
  stretch: Faz com que os itens estiquem para preencher o contêiner.
  baseline: Alinha os itens com base na linha de base do texto.
  Exemplo: align-items: center;

* flex-wrap: Define se os itens devem quebrar a linha quando o espaço do contêiner acabar.

   Opções:
   nowrap (padrão): Não permite quebra de linha.
   wrap: Quebra os itens em múltiplas linhas se necessário.
   wrap-reverse: Mesma funcionalidade de wrap, mas com a ordem reversa.
   Exemplo: flex-wrap: wrap;

* align-content: Alinha as linhas flexíveis quando há espaço extra no eixo cruzado (somente aplicável quando o conteúdo está quebrado em múltiplas linhas).

    Opções: flex-start, flex-end, center, space-between, space-around, stretch.
    Exemplo: align-content: space-between;

#### Propiedades dos Flex Items  :fire: :

* flex-grow:

  Define a capacidade de um item crescer para preencher o espaço disponível.
  Valor: Número que define a proporção de crescimento.
  Exemplo: flex-grow: 1;

* flex-shrink:

  Define a capacidade de um item encolher quando o espaço é limitado.
  Valor: Número que define a proporção de encolhimento.
  Exemplo: flex-shrink: 0;

* flex-basis:

  Define o tamanho inicial de um item antes de qualquer espaço extra ser distribuído.
  Valor: Pode ser um valor em pixels, porcentagem ou auto.
  Exemplo: flex-basis: 200px;

* align-self:

  Alinha um item individualmente ao longo do eixo cruzado, ignorando o valor de align-items do contêiner.
  Opções: auto, flex-start, flex-end, center, baseline, stretch.
  Exemplo: align-self: flex-end;










  
