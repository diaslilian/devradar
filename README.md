# DevRadar

Projeto desenvolvido na Semana OmniStack 10, aplicação que cadastra e busca os desenvolvedores utilizando geolocalização. Podendo ser filtrados pela tecnologia que trabalham.

### WEB

![web](https://user-images.githubusercontent.com/47895394/72686652-c5406c00-3ad5-11ea-973a-6ecabdb27218.png)

### MOBILE

![mobile](https://user-images.githubusercontent.com/47895394/72686497-43037800-3ad4-11ea-97a0-2f85572266ee.png)

## :rocket: Tecnologias

### API

- [Node.js](nodejs)
- [Express](https://expressjs.com/)
- [MongoDB](https://mongodb.com)
- [Mongoose](https://mongoosejs.com/)
- [axios](https://github.com/axios/axios)
- [Socket.io](https://socket.io/)
- Teste de endpoints com [Insomnia](https://insomnia.rest/)

### WEB

- [ReactJS](https://reactjs.org/)
- [axios](https://github.com/axios/axios)

### MOBILE

- [React Native](http://facebook.github.io/react-native/)
- [React Navigation](https://reactnavigation.org/)
- [Expo](https://expo.io/)
- [axios](https://github.com/axios/axios)
- [Socket.io](https://socket.io/)

## :information_source: COMO USAR:

To clone and run this application, you'll need [Git](https://git-scm.com), [Node.js v10.16](nodejs) or higher + [Yarn v1.13](yarn) or higher installed on your computer. From your command line:

### **Clonar o repositório**

```bash
# Clone this repository
$ git clone https://github.com/diaslilian/devradar

# Go into the repository
$ cd devradar
```

### **API**

> Logo após clonar o repositório navegue ate a pasta backend e execute o comando yarn install ou npm install.

> Você vai precisar criar uma conta no Mongo Atlas e criar um cluster e logo após pegar sua string de conexão e colocar dentro do arquivo **_example.env_** dentro da pasta backend, nele deve conter _MONGO=_ sua string de conexão com Mongo Atlas, após colocar sua string de conexão renomeie o arquivo para apenas **_.env_**.

> Logo após seguir tudo que foi feito acima pode executar o comando _yarn dev_ ou _npm run dev_ e o então deverá aparecer no console **_[SERVER] server runing in port 3333_**.

```bash
# Go into backend
$ cd backend

# Install dependencies
$ yarn install

# Start the backend server
$ yarn dev
```

### **Web**

> Após seguir os passos acima e o backend está funcionando vá para pasta web e execute _yarn install_ ou _npm install_.

> Depois das dependências terminarem de instalar execute o comando _yarn start_ ou _npm run start_.

```bash
# On another terminal, go to the web folder
$ cd ../web

# Install dependencies
$ yarn install

# Start the web server
$ yarn start
```

### **Mobile**

> Para executar o mobile entre na pasta do mobile logo após o backend estar funcionando execute _yarn install_ ou _npm install_.

> Após as dependências terminarem de baixar execute _yarn start_ ou _npm start_. O expo já estará funcionando para você ler o Qr Code e utilizar a aplicação.

```bash
# On another terminal, go to the mobile folder
$ cd ../mobile

# Install dependencies
$ yarn install

# Start the expo server
$ yarn start
```

Created by Lilian Dias :wave: [Hi-5!](https://www.linkedin.com/in/dias-lilian/)
