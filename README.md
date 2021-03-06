![](images/week-11.jpg)

# devradar-omnistack-week

This project is based on Omnistack Week 11 developed by Rocketseat, the objective is make a Fullstack application using NodeJS with Express and SQLite in backend, React in web frontend and React Native in mobile. That app can register NGOs and yours incidents with the cost in mobile the user can list these incidents and view the details and get in touch via Whatsapp or Email.

<p align="center">
  <a aria-label="Versão do Node" href="https://github.com/nodejs/node/blob/master/doc/changelogs/CHANGELOG_V12.md#12.14.1">
    <img src="https://img.shields.io/badge/node.js@lts-12.14.1-informational?logo=Node.JS"></img>
  </a>
  <a aria-label="Versão do React" href="https://github.com/facebook/react/blob/master/CHANGELOG.md#16120-november-14-2019">
    <img src="https://img.shields.io/badge/react-16.12.0-informational?logo=react"></img>
  </a>
  <a aria-label="Versão do Expo" href="https://www.npmjs.com/package/expo-cli/v/3.11.5">
    <img src="https://img.shields.io/badge/expo--CLI-3.11.5-informational?logo=expo"></img>
  </a>
</p>

## backend
To install the dependences and run the server in development mode execute:
```bash
cd backend
yarn install
yarn start
```
> If you need use the file "insomnia_workspace.json" to import Insomnia Workspace and access the routes.

## frontend
To start the web frontend run the following commands:
```bash
cd frontend
yarn install
yarn start
```

### Screenshots
![](images/frontend-1.jpg)
![](images/frontend-2.jpg)

## mobile
Before start the mobile change the file `src/services/api.js` with your machine address in your network and execute:
```bash
# If you don't have the expo-cli installed run this line above
yarn global add install expo-cli
cd mobile
yarn install
yarn start
```

### Screenshots
![](images/mobile-2.jpg)
![](images/mobile-1.jpg)

After that access the application using an emulator or the Expo App.
## License

[MIT](./LICENSE) &copy; [Rocketseat](https://rocketseat.com.br/)
