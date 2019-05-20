+++
title = "A superposition free method for protein conformational ensemble analyses and local clustering based on a differential geometry representation of backbone"
date = 2019-02-01
authors = ["Antonio Marinho Silva Neto", "Samuel Reghim Silva", "Michele Vendruscolo", "Carlo Camilloni", "Rinaldo Wander Montalvão"]
publication_types = ["2"]
abstract = ""
selected = true
publication = "*Proteins: Structure, Function, and Bioinformatics*"
url_pdf = "https://onlinelibrary.wiley.com/doi/abs/10.1002/prot.25652"
doi = "10.1002/prot.25652"
+++


---

## Em poucas palavras

Nesse trabalho, nós propomos um método para análise conformacional de proteínas baseado em geometria diferencial (DG) do *backbone* de estruturas proteicas. Essa representação possui as principais vantagens das alternativas populares como coordenadas atômicas, ângulos $\phi-\psi$ e variáveis coletivas e evitam as principais desvantagens. Em termos práticos, as principais vantagens são:

  1. evitar o problema da sobreposição de estruturas
    * a necessidade de sobrepor estruturas é a maior limitação imposta pelo uso de coordenadas atômicas;
  2. evitar topologias "non-flat"
    * a natureza periódica dos ângulos $\phi-\psi$ impõe uma topologia ao espaço conformacional que pode dificultar algumas análise, especialmente para agrupamento de conformações;
  3. ser intuitiva e geral
    * a noção de mudanças de curvatura e torção é intuitiva, como ocorre com algumas variáveis coletivas, e aplicável para todas as proteínas, o que não ocorre para variáveis coletivas mais intuitivas.

Baseado na representação baseada em DG, nós propomos:

  * Uma nova métrica para flexibilidade de proteínas, $d_{max}$
  * Um novo método para *clustering* global baseado em características locais
  * Um novo método para comparar conformações de proteínas

Ao comparar com outras técnicas populares de análise e aplicar a dois casos extremos do espectro de flexibilidade de proteínas (*ensembles* conformacionais de proteínas globulares rígidas e não estruturadas), nós demonstramos que os métodos propostos permitem obter resultados superiores ou similares ás alternativas mais populares. Os resultados também ilustram como os novos métodos podem substituir e/ou complementar outros métodos de análise de flexibilidade de proteínas.

---

## Software

O  FleXgeo, protótipo desenvolvido para as análises apresentadas neste artigo, está disponível [aqui](https://github.com/AMarinhoSN/FleXgeo) gratuitamente para uso acadêmico. Um site com tutoriais estará disponível em breve, mas um guia rápido de como utiliza-lo pode ser encontrado no Github. Esse protótipo não está otimizado para performance, mas o baixo custo computacional associado ao cálculo dos descritores de geometria diferencial permite obter resultados em poucos minutos em computador pessoal médio de 2018.

---

## E serve para que?

Os métodos propostos e os resultados apresentados neste artigo são interessantes para:

  * **Análise de proteínas não-estruturadas**
    * Nesse cenário extremo de flexibilidade obter um boa solução de sobreposição costuma ser difícil ou mesmo impossível. Ao evitar o problema da sobreposição de estruturas, a representação por DG pode ser uma excelente ferramenta de análise;
  * **Análise do papel de resíduos individuais na dinâmica global**
    * Pessoalmente desconheço qualquer método de agrupamento conformacional que relacione intuitivamente movimentos individuais de resíduos com a dinâmica global e acredito que o método proposto é uma ferramenta completamente nova para a caixa de ferramentas de um biólogo estrutural computacional;
  * **Análises que envolvam medidas de flexibilidade de proteínas**
    * É essencial ter uma boa métrica ao comparar a flexibilidade de proteínas, especialmente uma cujo resultado não dependa exclusivamente da solução de sobreposição espacial. A $d_{max}$ pode ser uma métrica interessante quando for necessário comparar a flexibilidade de diferentes proteínas, como, por exemplo, em estudos da relação entre sequência, estrutura e dinâmica em uma mesma família de proteínas
  * **Representação matemática do espaço conformacional de proteínas**
    * A representação do *backbone* da proteínas por DG gera um epaço conformacional universal no qual aspectos estruturais podem ser analisados
por uma nova perspectiva, a qual pode permite explorar novos caminhos para responder e criar novas perguntas.

---
