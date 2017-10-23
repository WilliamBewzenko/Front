## FRONT
A muito tempo já estávamos em constantes debates, a fim de melhorar nosso front-end, que veio já herdado de uma agência.

Tentamos com o um novo repositório, e sim funcionou, houve muitos aprendizados e desafios, com esta experiência vimos o que dá certo e o que tambem nao da.

### Estrutura
Um dos nossos maiores desafios é encontrar uma estrutura de arquivos que forneça para nos devs, um código legível, rápido de ser desenvolvido e também de fácil manutenção ou atualização caso necessário.

Ao longo da nossas história já tivemos alguns tipos de aprendizados, como monólitos, ou somente em um repositórios ou em múltiplos repositórios:

#### Monólitos (back e front):
**Pros**: Facilidade e entrega mais rápida.

**Contras**: Sem escalabilidade do front-end, muitas alterações no mesmo repositório e facilidade de dar problemas em merge, se amarra totalmente ao back-end.
***
#### Monólitos somente do front:
**Pros**: Independência dos times back-end e front-end, maior rapidez de desenvolvimento, unificação de informação...

**Contras**: Quando maior a equipe ou o repositório maior dificuldade de versionamento, ou divisão de tarefas, outros problemas fácil alteração em outras partes do sistema, ou seja quanto maior o repositório maior aumenta a dificuldade de gestão do mesmo.
***
#### Múltiplos repositórios:
**Pros**: Maior independência dos projetos, facilidade em divisão em equipes, builds mais concisos, maior rapidez de desenvolvimento do produto, maior foco,

**Contras**: Não consigo enxergar.

Seguindo a ideia de múltiplos repositórios favor ver a [estrutura de pastas](https://github.com/WilliamBewzenko/Front/tree/master/structure).

#### Tecnologias
* [callemall/material-ui](https://github.com/callemall/material-ui/tree/v1-beta)
* [facebook/react](https://github.com/facebook/react)
* [reactjs/redux](https://github.com/reactjs/redux)
* [redux-saga/redux-saga](https://github.com/redux-saga/redux-saga)
* [axios/axios](https://github.com/axios/axios)
* [reactjs/reselect](https://github.com/reactjs/reselect)
* [ReactTraining/react-router](https://github.com/ReactTraining/react-router)

#### Testes
* [facebook/jest](https://github.com/facebook/jest)
* [sinonjs/sinon](https://github.com/sinonjs/sinon)
* [airbnb/enzyme](https://github.com/airbnb/enzyme)
* [adriantoine/enzyme-to-json](https://github.com/adriantoine/enzyme-to-json)
* [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter)(opcional)

#### Ferramentas
* [webpack/webpack](https://github.com/webpack/webpack)
* [hooks](https://developer.github.com/v3/repos/hooks/)
* [eslint](https://www.npmjs.com/package/eslint-config-airbnb)
* [prettier](https://github.com/prettier/prettier)

#### Build

#### Desenvolvimento

#### Produção



