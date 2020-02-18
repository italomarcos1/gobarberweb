<h1 align="center">
  <img alt="GoBarber" title="GoBarber" src="./gobarber.svg" width="150px" />
</h1>

---

**GoBarber Web**, uma aplicação **React** que simula o agendamento de serviços em uma barbearia. Essa aplicação consome os dados da **API** [GoBarber](https://github.com/italomarcos1/GoBarber/), também feita durante o bootcamp GoStack.

---
### Libs e Frameworks utilizados:

- [React](https://github.com/facebook/react)
- [Redux](https://github.com/reduxjs/redux) - lib para gerenciamento de estado global entre os componentes. Também conta com Redux Saga para lidar com assincronismo e chamadas à API, e Redux Persist.para persistir os dados do usuário no LocalStorage (para mantê-lo logado na aplicação, etc).
- [Immer](https://github.com/immerjs/immer) - manipula o estado do Redux, sem quebrar a imutabilidade.
- [History](https://github.com/ReactTraining/history) - usado para redirecionamento de rotas.
- [Styled Components](https://github.com/styled-components/styled-components) - cria componentes estilizados permitindo encadear os estilos (estilizar componentes e estruturas internas do componente), e estilizar baseado em propriedades.
- [Axios](https://github.com/axios/axios) - usado para fazer as requisições e consumir os dados do back-end.
- [Unform](https://github.com/rocketseat/unform) - biblioteca de para gerar os formulários de login e cadastro. 
- [Polished](https://github.com/styled-components/polished) - manipulação de cores nos botões das telas de login e cadastro. Usado em conjunto com o Styled Components.
- [React Toastify](https://github.com/fkhadra/react-toastify) - **alerts** estilizados nas telas de login, cadastro, e atualização de dados. usados em casos de sucesso e erro.
- [Socket.IO](https://github.com/socketio/socket.io) - implementando *real-time* na aplicação. As notificações de novos agendamentos são listadas em tempo real na **Dashboard** do usuário.
- [Date-fns](https://github.com/date-fns/date-fns) - lidando com datas e timezone no Javascript.
- [Prop Types](https://github.com/facebook/prop-types) - validação dos dados passados como propriedades nos componentes.
- [Reactotron](https://github.com/infinitered/reactotron) - usado em desenvolvimento para debugar a aplicação, monitorar e gerenciar o estado do Redux, e lidar com os dados recebidos da API.

---

## Como executar a aplicação:

Clone o repositório:
```
$ git clone https://github.com/italomarcos1/gobarberweb.git
```
Abra o repositório:
```
$ cd gobarberweb
```
Instale as libs pra rodar a aplicação (a pasta *node_modules* será criada):
```
$ yarn
```
Inicialize a API do [GoBarber](https://github.com/italomarcos1/GoBarber), as instruções estão na página:
```
...
```

Após iniciar o servidor no passo anterior, execute o comando abaixo para iniciar a aplicação:
```
$ yarn start
```
Por [Italo Marcos](https://www.linkedin.com/in/italo-m-b181b1117/)

---
## Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](https://github.com/flaviohugo14/fastfeet/blob/master/LICENSE) para mais detalhes.

---




This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
