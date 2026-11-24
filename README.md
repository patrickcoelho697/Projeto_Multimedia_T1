# Projeto_Multimedia_T1
# STUDIO OM — Dashboard Oficina Multimédia

## 0. Identificação do projeto

**Nome da Aplicação:** STUDIO OM — Dashboard Oficina Multimédia

**Disciplina:** Oficina de Multimédia — 12.º Ano — CRSI

**Ano Letivo:** 2026/2027

**Autor:** Patrick Coelho

**Turma:** 12ºB

**Link da Aplicação Web:** [Link do GitHub Pages]

**Proposta Escolhida:** [Proposta 1 ou Proposta 2 — confirmar com o enunciado]


## 1. Visão Geral do Projeto

O STUDIO OM é um dashboard web interativo que reúne três programas diferentes numa única página: um gerador de nuvens de palavras, um analisador de formatos e cores e um jogo do número secreto.

O objetivo foi adaptar exercícios de programação para uma aplicação web mais moderna, intuitiva e visualmente apelativa, acrescentando novas funcionalidades com a ajuda da Inteligência Artificial.

O utilizador pode selecionar cada programa através de cartões interativos, sendo a ferramenta apresentada imediatamente abaixo, sem necessidade de abrir outras páginas.

## 2. Estrutura do Código e Funcionalidades Integradas

Para desenvolver este projeto, parti de três exercícios de programação em Python, que foram adaptados para HTML, CSS e JavaScript. A lógica dos programas foi recriada em JavaScript, tendo sido acrescentadas novas funcionalidades com o apoio da IA.

### Programa 1 — Gerador de Nuvens de Palavras

Este programa permite transformar um texto ou poema numa nuvem de palavras, destacando as palavras mais frequentes.

**Funcionalidades:**

- Introduzir ou colar um texto personalizado.
- Identificar e contar as palavras mais utilizadas.
- Escolher palavras que devem ser ignoradas.
- Personalizar a quantidade de palavras apresentada.
- Alterar a paleta de cores e a cor de fundo.
- Receber sugestões de sinónimos para algumas palavras.
- Escolher o formato do cartaz, como A4, A3, quadrado ou formatos para redes sociais.
- Definir dimensões personalizadas.
- Guardar a nuvem de palavras como imagem PNG.

### Programa 2 — Formatos e Cores

Este programa permite analisar resoluções de imagem e explorar combinações de cores.

**Funcionalidades:**

- Introduzir a largura e a altura de uma imagem.
- Identificar categorias como HD, Full HD, QHD e 4K.
- Calcular a proporção da imagem (*aspect ratio*).
- Calcular o número total de megapíxeis.
- Visualizar graficamente o formato da imagem.
- Criar paletas de cinco cores a partir de uma cor base.
- Selecionar uma cor e descobrir os respetivos códigos HEX, RGB e HSL.
- Copiar os códigos de cores.
- Criar novas paletas com cores personalizadas.

### Programa 3 — Jogo do Número Secreto

Este programa consiste num jogo em que o computador escolhe um número aleatório entre 1 e 100 e o jogador tem de o descobrir.

**Funcionalidades:**

- Introduzir números e verificar se correspondem ao número secreto.
- Escolher entre três níveis de dificuldade.
- Fácil: 30 tentativas, com dicas.
- Médio: 10 tentativas, com dicas.
- Difícil: 10 tentativas, sem dicas.
- Acompanhar o número de tentativas utilizadas.
- Consultar o histórico dos números introduzidos.
- Guardar o melhor resultado de cada dificuldade no navegador.
- Reiniciar o jogo sempre que necessário.

### Tecnologias Utilizadas

O projeto foi desenvolvido com:

- **HTML5:** estrutura e organização das aplicações.
- **CSS3:** design, cores, botões, cartões, espaçamentos e adaptação a diferentes ecrãs.
- **JavaScript:** funcionamento dos programas, cálculos, validações e interação com o utilizador.

Toda a aplicação funciona no navegador, sem necessidade de instalar bibliotecas externas.


## 3. Registo de Utilização da Inteligência Artificial

Durante o desenvolvimento utilizei o ChatGPT como ferramenta de apoio para converter os exercícios, experimentar ideias de design, criar funcionalidades e corrigir problemas.

Fui fazendo vários pedidos para melhorar o projeto progressivamente, analisando os resultados apresentados e escolhendo as alterações que considerava mais adequadas.

Os prompts seguintes são exemplos reconstituídos dos pedidos feitos durante o desenvolvimento.

### 3.1. Prompt para Conversão Web/HTML

> Tenho três exercícios de Python: um gerador de nuvens de palavras, um programa que analisa formatos de imagem e um jogo do número secreto. Quero transformar estes exercícios num dashboard web utilizando HTML, CSS e JavaScript. Junta os três programas numa única aplicação, com um design moderno e funcionalidades interativas.

Este pedido serviu como ponto de partida para transformar os exercícios numa aplicação web.

### 3.2. Prompts para Ampliação e Construção de Funcionalidades

**Prompt 1 — Melhorar a nuvem de palavras**

> Quero melhorar o gerador de nuvens de palavras. Acrescenta opções para personalizar as cores, escolher as palavras a ignorar, alterar a quantidade de palavras apresentadas e guardar o resultado como imagem PNG.

**Prompt 2 — Formatos de cartaz**

> No gerador de nuvens de palavras, acrescenta a possibilidade de escolher o formato do cartaz. Quero opções como A4 vertical, A4 horizontal, A3, quadrado e formatos personalizados. A nuvem deve adaptar-se automaticamente às dimensões escolhidas.

**Prompt 3 — Identificador de cores**

> No programa de cores, quero conseguir selecionar qualquer cor de uma paleta e descobrir o código correspondente. Mostra os códigos HEX, RGB e HSL, permite copiá-los e acrescenta um seletor de cores personalizado.

**Prompt 4 — Dificuldades do jogo**

> No jogo do número secreto, mantém o modo Fácil com 30 tentativas. No Médio coloca apenas 10 tentativas com dicas. No Difícil coloca também 10 tentativas, mas sem revelar se o número é maior ou menor, sem mostrar intervalos mais pequenos e sem outras dicas.

**Prompt 5 — Melhorias de navegação**

> Quero que os três programas apareçam lado a lado em cartões na página inicial. Ao clicar num cartão, o respetivo programa deve aparecer logo por baixo, ocupando a largura disponível no computador. Mantém tudo na mesma página.

### 3.3. Dificuldades e Erros Corrigidos com a IA

Ao longo do desenvolvimento surgiram algumas dificuldades, principalmente na organização dos três programas dentro da mesma página.

Uma das primeiras dificuldades foi adaptar a lógica dos exercícios para JavaScript e garantir que todas as ferramentas funcionavam corretamente.

No gerador de nuvens de palavras, foi necessário melhorar a distribuição das palavras, pois algumas podiam ficar demasiado próximas ou sobrepostas. Também foi preciso adaptar a nuvem aos diferentes formatos de cartaz.

No jogo do número secreto, tive de ajustar as condições dos níveis de dificuldade para garantir que o modo Difícil não apresentava dicas ao jogador.

Outro desafio foi a adaptação do layout aos diferentes tamanhos de ecrã, principalmente para evitar que alguns elementos ficassem demasiado grandes ou desorganizados.

Com o apoio da IA, fui revendo o código, corrigindo os problemas encontrados e melhorando progressivamente o funcionamento das ferramentas.

### 3.4. Otimização do Layout e Design

A parte visual foi uma das áreas em que mais utilizei a Inteligência Artificial.

Inicialmente, experimentei diferentes designs, com o objetivo de criar uma interface moderna e organizada.

**Prompt 1 — Experimentação de designs**

> Quero que experimentes diferentes estilos e estruturas para o meu dashboard. Não quero apenas mudar as cores, quero ver ideias diferentes de organização, navegação, cartões e apresentação das ferramentas.

**Prompt 2 — Interface inspirada num sistema operativo**

> Experimenta criar uma interface semelhante a um pequeno sistema operativo, com três aplicações independentes, ícones coloridos e janelas com um aspeto moderno.

**Prompt 3 — Adaptação para computador**

> Gosto do estilo apresentado, mas quero uma estrutura mais adequada ao computador. Coloca os três programas em cartões na parte superior e faz com que, ao clicar num deles, o programa apareça por baixo. Não quero janelas flutuantes.

**Prompt 4 — Melhorias visuais**

> Mantém o fundo azul-escuro, mas melhora os cartões, as fontes, os botões, as margens e os espaçamentos. Quero um aspeto mais profissional e uniforme.

**Prompt 5 — Personalização da identidade**

> Altera o nome da aplicação para STUDIO OM e utiliza a designação Dashboard Oficina Multimédia. Retira também as setas diagonais dos botões dos programas.

**Prompt 6 — Design do jogo**

> Experimenta outro design para o jogo do número secreto, mas não mudes a estrutura nem a forma de jogar. Quero apenas melhorar o aspeto visual, com cores mais harmoniosas, botões modernos e uma apresentação mais cuidada.

Depois de experimentar várias versões, escolhi uma estrutura simples, com fundo azul-escuro, cartões coloridos e áreas de trabalho brancas.

Como referência visual e funcional, também considerei a plataforma **Adobe Express** (https://www.adobe.com/express), especialmente pela forma como reúne várias ferramentas criativas numa única interface.


## 4. Estrutura de Ficheiros do Repositório

A estrutura do projeto é simples, pois toda a aplicação está desenvolvida num único ficheiro HTML, que inclui os estilos CSS e o código JavaScript.

**Descrição dos ficheiros:**

- **index.html:** contém a estrutura do dashboard, os estilos e todas as funcionalidades das três aplicações.
- **README.md:** contém a apresentação, a descrição, o registo da utilização da IA e a reflexão sobre o projeto.

Não foi necessário utilizar um ficheiro `app.py`, porque o projeto funciona diretamente em JavaScript e não utiliza Streamlit.

Também não foi necessário criar um ficheiro `style.css` separado, uma vez que os estilos estão integrados no `index.html`.

Caso sejam adicionadas imagens ou capturas de ecrã ao repositório, estas poderão ser organizadas numa pasta `assets/`.

Para executar a aplicação, basta abrir o ficheiro `index.html` num navegador, como o Google Chrome, Microsoft Edge ou Firefox.

---

## 5. Reflexão Crítica e Aprendizagem

O desenvolvimento deste projeto foi uma experiência interessante, porque me permitiu transformar três exercícios de programação numa aplicação web mais completa e visualmente apelativa.

O que correu melhor foi a integração dos três programas num único dashboard e a possibilidade de acrescentar novas funcionalidades que não existiam nos exercícios iniciais. Gostei especialmente de personalizar as ferramentas e de experimentar diferentes designs até encontrar um resultado de que gostasse.

A maior dificuldade foi encontrar uma estrutura que fosse moderna, mas ao mesmo tempo simples de utilizar. Durante o desenvolvimento experimentei várias ideias, incluindo dashboards tradicionais, interfaces semelhantes a sistemas operativos e designs inspirados em aplicações móveis.

Com estas experiências percebi que nem sempre um design mais complexo é o melhor. Por exemplo, no jogo do número secreto, cheguei a experimentar uma estrutura completamente diferente, mas acabei por preferir manter a organização original e melhorar apenas as cores, os botões e a apresentação.

A utilização da Inteligência Artificial ajudou-me bastante, principalmente porque permitiu experimentar diferentes ideias, compreender partes do código e encontrar soluções para os problemas que iam surgindo.

No entanto, também percebi que não basta pedir código à IA e utilizá-lo imediatamente. É importante testar, verificar se tudo funciona corretamente e explicar de forma clara o que se pretende alterar.

Com este trabalho aprendi mais sobre a utilização de HTML, CSS e JavaScript em conjunto, sobre a organização de uma aplicação web e sobre a importância de melhorar continuamente um projeto até atingir o resultado pretendido.

Considero que o resultado final corresponde ao objetivo inicial: criar um dashboard que reúne diferentes ferramentas multimédia de forma funcional, organizada e com uma identidade visual própria.
