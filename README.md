# <img src="https://odin.qconcursos.com/packs/images/logo/qc-47196578.svg" alt="qcx" width="24" /> Desafio Qconcursos

O Qconcursos é plataforma online de resolução de questões de concursos e cursos, voltada para apoiar os estudantes a alcançarem a aprovação em concursos públicos e a evoluírem na sua vida profissional por meio da educação.
Estamos em constante evolução e justamente por isso queremos evoluir o nosso serviço de buscas

## Desafio

O desafio consiste em desenvolver um aplicativo nativo Android nas linguagens Java ou Kotlin ou um aplicativo iOS na linguagem Swift que mostra citações sobre programação e os detalhes de cada uma delas.

O app consiste basicamente em 2 telas. A principal é uma lista de citações e ao clicar em uma delas, deve-se abrir outra tela com os detalhes daquela citação.
Os dados virão de uma api externa que tem sua documentação no link:

https://github.com/skolakoda/programming-quotes-api.

#### Tela principal
- Ela deve conter a lista de citações com o texto do campo “en” que contém a citação em inglês
- A lista deve ter um “scroll” para poder visualizar todos os itens
- Insira um divisor entre cada um dos itens da lista para melhor visualização

##### Bônus 1
> usar a rota /quotes/page para pegar os dados paginados e tratar essa paginação no app. Ela pode ser feita através do clique de um botão que busca a página seguinte (próximos itens) e concatena com a lista atual ou uma ideia de scroll infinito, onde a nova página é carregada conforme o usuário vai chegando no final da lista.

#### Tela de detalhes
- Mostra as informações dos campos “en”, “author” e “rating”
- Deve haver algum meio para navegar de volta para a tela inicial

##### Bônus 2
> usar a rota /quotes/vote para dar nota à uma citação passando o id dela e o voto que o usuário pode dar pelo app


#### Geral
Sinta-se livre para definir o layout, cores e elementos de visualização que exibam melhor essas informações.

Descreva o que foi feito em cada commit com uma mensagem clara.

Sugerimos o uso das bibliotecas Retrofit no Android e Alamofire no iOS para fazer as requisições, porém não é obrigatório.

##### Bônus 3
> splash screen ao abrir o app enquanto os dados da lista são carregados.

##### Bônus 4
> tratar possível erro de alguma requisição com uma mensagem para o usuário, ex.: toast no Android ou SVProgressHUD no iOS.
Outras possíveis melhorias não descritas também podem ser avaliadas como bônus.

### Como submeter o projeto

O projeto deve ser criado com o nome do `desafio-qcx`.

Lembre-se de deixar o repositório público e adicione um README.md explicando como rodar o projeto caso tenha alguma peculiaridade nessa instalação e, caso implemente algum bônus, também o descreva.

### Avaliação

- Boas práticas de programação
- Domínio da linguagem e ferramentas
- Cumprimento do escopo pedido
