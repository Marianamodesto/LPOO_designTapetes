
Setor de Educação Profissional e TecnológicaTecnologia em Análise e Desenvolvimento de Sistemas
- DS-131 –Linguagem de Programação Orientada a Objeto
- Prof. Rafael Romualdo Wandresen
- Valor: 100% da terceira nota
- Data de entregae defesa: **13/06/2019**
- Equipes: Máximo 4 pessoas.

A empresa DesignTapetes vende tapetes sob medida e de formatos diferentes para os clientes. 
O seu portfóliode produtos é formado por tapetes em forma de: Círculos, Retângulos e Triângulo. 
Os tapetes são vendidos em três materiais diferentes: Comum, Luxo e Premium.
A empresa deseja informatizar a venda e o cadastro de clientes. 
Para isso contratou você para implementar um sistema que possua:
 1. Uma tela para cadastro de clientes (Nome, SobreNome e CPF) 
   a. Nesta tela deve ser possível listar todos os clientes (Use AbstractTableModel)
   b. Nesta tela deve ser possível atualizar os dados de um cliente existente;
   c. Nesta  tela  deve  ser  possível  excluir  um  cliente  (tomar  cuidado  para  excluir também os produtos que ele possui)
   d.Listar os clientes com filtro pelo sobrenome ou parte do sobrenome
  2. Uma tela para realizaçãodo pedido dos produtos para o clientea.O cliente deve estar previamente cadastrado para realizar a venda (tela anterior)b.O usuário escolhe um cliente (O filtro do cliente deve ser por CPF). Ao escolher o cliente, se o cliente já tiver pedido, os itens do pedido do cliente são listados e poderão  ser  atualizados.  Se  o  cliente  não  possuir  pedido,  o  usuário  poderá adicionar  itens  ao  pedido  do  cliente.Por  motivo  de  simplificação  um  cliente possui somente um pedido.c.O usuário escolhe:i.Tapetes a serem vendidos, com suas formas, e seus tamanhosii.Dependendo da forma o usuário informa: raio, lados do retângulo (altura e largura) ou base e altura do triânguloiii.Ou  o  usuário  pode  também  informar  a  quantidade  em  metros^2.  O sistema deve calcular e mostrar: O raio no caso de um circulo, o valor do lado (quadrado) no caso de um retângulo ou o valor da base e altura 
no caso do triângulo (considere que neste caso a base a altura terão o mesmo valor)d.Durante o processo o sistema deve informar o preço da venda.e.O preço do item écalculado por metro quadrado, conforme o tipo do material.f.O  sistema  deve  armazenar  para  cada  pedido:  Os  tapetes  adquiridos,  um identificador para o pedido e o preço total do pedido.Figura 2–Sugestãopara a tela de Clientes3.Uma tela para atualizar o preço do metro quadrado de cada material: Comum, Luxo e Premium.Figura 3–Sugestão para tela de atualização de preçosO programa acima deve ser feito utilizando as seguintes tecnologias:Utilizar herança para definir as classes Forma, Retângulo, Triângulo e CírculoJava SwingItens para serem entregues:1.Diagrama de classes2.Projeto na IDE Eclipse ou Netbeans com código fonte
Avaliação:Material entregueQualidade do software (bugs encontrados na defesa)Defesa do código e anota será individual, considerando a defesa
