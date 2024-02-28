Hoje realizei a segunda atividade prática tive algumas dificuldades em relação a primeira mas consegui realizar.

     1-Contar o número de registros existentes
db.usuarios.count()
16

     3-Encontrar o usuário com o nome "Bruce Wayne":
     
{
_id: "65df3a1137d2b65a807c5d50",

nome: "Bruce Wayne",

email: "brucewayne@gothan.com",


},
];

     4-Encontrar o usuário com o e-mail "ghost_silva@fantasma.com":
     
[
{
_id: "65df398437d2b65a807c5cf4",

nome: "Ghost Silva",

email: "ghost_silva@fantasma.com",


},
];

     5-Deletar o usuário com e-mail "peterparker@marvel.com":
     
[
{
acknowledged: true,
deletedCount: 1,
},
];

Produtos

     1-Apresentar produtos com descrição vazia:
[
{
_id: "65df36e637d2b65a807c5aed",

nome: "caneca chopp",

categoria: "utilitários",

preco: 25.5,

descricao: "",


},
{
_id: "65df36e637d2b65a807c5aee",

nome: "copo grande térmico",

categoria: "utilitários",

preco: 35.9,

descricao: "",
},


     2-Apresentar produtos com a categoria "games":
     
[
{
_id: "65df376e2cb48dd753931883",

nome: "mouse gamer",

categoria: "games",

preco: 101,

descricao: "Mouse com leds.",


},
{
_id: "65df376e2cb48dd753931884",

nome: "teclado gamer",

categoria: "games",

preco: 99,

descricao: "Teclado com leds.",


},
{
_id: "65df376e2cb48dd753931885",

nome: "monitor gamer",

categoria: "games",

preco: 1500,

descricao:

  "Monitor grande para jogar.",


},
{
_id: "65df376e2cb48dd753931886",

nome: "jogo batman",

categoria: "games",

preco: 150,

descricao:

  "Jogo do Batman para PC.",


},
{
_id: "65df376e2cb48dd753931887",

nome: "jogo tomb raider",

categoria: "games",

preco: 100,

descricao:

  "Jogo Tomb Raider para PC.",


},
{
_id: "65df376e2cb48dd753931888",

nome: "jogo spider-man",

categoria: "games",

preco: 200,

descricao:

  "Jogo Spider-man para PS4.",


},
{
_id: "65df376e2cb48dd753931889",

nome: "jogo pac-man",

categoria: "games",

preco: 180,

descricao:

  "Jogo Pac-man para Xbox One.",


},
];

     3-Apresentar produtos com preço "0":
     
[
{
_id: "65df37d037d2b65a807c5b29",

nome: "adesivo",

categoria: "utilitários",

preco: 0,

descricao:

  "desivo com precificação para produtos.",


},
{
_id: "65df37d037d2b65a807c5b2a",

nome: "caneca",

categoria: "utilitários",

preco: 0,

descricao: "Caneca para café.",


},
];

     4-Apresentar produtos com preço maior que "100.00":
     
[
{
_id: "65df38182cb48dd7539318a5",

nome: "mouse gamer",

categoria: "games",

preco: 101,

descricao: "Mouse com leds.",


},
{
_id: "65df38182cb48dd7539318a7",

nome: "monitor gamer",

categoria: "games",

preco: 1500,

descricao:

  "Monitor grande para jogar.",


},
{
_id: "65df38182cb48dd7539318a8",

nome: "jogo batman",

categoria: "games",

preco: 150,

descricao:

  "Jogo do Batman para PC.",


},
{
_id: "65df38182cb48dd7539318aa",

nome: "jogo spider-man",

categoria: "games",

preco: 200,

descricao:

  "Jogo Spider-man para PS4.",


},
{
_id: "65df38182cb48dd7539318ab",

nome: "jogo pac-man",

categoria: "games",

preco: 180,

descricao:

  "Jogo Pac-man para Xbox One.",


},
{
_id: "65df38182cb48dd7539318ac",

nome: "guarda-roupas lady bug",

categoria: "casa",

preco: 2500,

descricao:

  "Guarda-roupas gigante da Lady Bug.",


},
{
_id: "65df38182cb48dd7539318ad",

nome: "cama solteiro",

categoria: "casa",

preco: 1800,

descricao: "Cama box solteiro.",


},
];

     5-Apresentar produtos com preço entre "1000.00" e "2000.00":
     
[
{
_id: "65df385a37d2b65a807c5b5f",

nome: "monitor gamer",

categoria: "games",

preco: 1500,

descricao:

  "Monitor grande para jogar.",


},
{
_id: "65df385a37d2b65a807c5b65",

nome: "cama solteiro",

categoria: "casa",

preco: 1800,

descricao: "Cama box solteiro.",


},
];

     6-Apresentar produtos em que o nome contenha a palavra "jogo":
     
[
{
_id: "65df38a72cb48dd753931928",

nome: "jogo batman",

categoria: "games",

preco: 150,

descricao:

  "Jogo do Batman para PC.",


},
{
_id: "65df38a72cb48dd753931929",

nome: "jogo tomb raider",

categoria: "games",

preco: 100,

descricao:

  "Jogo Tomb Raider para PC.",


},
{
_id: "65df38a72cb48dd75393192a",

nome: "jogo spider-man",

categoria: "games",

preco: 200,

descricao:

  "Jogo Spider-man para PS4.",


},
{
_id: "65df38a72cb48dd75393192b",

nome: "jogo pac-man",

categoria: "games",

preco: 180,

descricao:

  "Jogo Pac-man para Xbox One.",
