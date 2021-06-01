<h1 align="center" >
    <img src="./assets/logo.png" width = "240px">
</h1>

<h1 align="center"> Plantmanager 🌱💚 </h1>

<h2 align="center"> 
    Cuide bem da sua plantinha 🤗
</h2>

<h3 align="center">
  Este aplicativo foi desenvolvido usando React Native com Expo.
</h3>

# Clonando este repositório

```
git clone https://github.com/steephanie/plantmanager
```

# 💻  Requisitos

Para este aplicativo, precisamos ter instalado:

- [Node](https://nodejs.org/en/)
- [Yarn](https://yarnpkg.com/lang/en/) (Opcional)

## 📲 Aplicativo móvel

<h1 align="center">
</h1>

<h3 align="center">
  Não se esqueça de regar mais suas plantas. Temos o cuidado de lembrá-lo sempre que precisar.
</h3>

<p>
Neste projeto usamos:
</p>

- [Expo](https://expo.io/) como estrutura React Native.
- [Async Storage](https://react-native-async-storage.github.io/async-storage/docs/install/), para salvar plantas em armazenamento local.
- [Expo Notifications](https://docs.expo.io/versions/latest/sdk/notifications/), para enviar notificação local ao usuário.
- [styled-components](https://styled-components.com/) para estilos.
- [Lottie](https://github.com/lottie-react-native/lottie-react-native), para carregar animação.

### 🔥 Executando nossa API falsa

Primeiro, altere a propriedade `baseURL` em`./src/services/api.ts`, para o seu IP, com a porta `3333`.
Depois, abra uma nova janela de terminal e execute `npx json-server ./src/services/server.json --host "seu IP" --port 333`

### ⚡️ Start

Para iniciar o aplicativo, execute:

```
cd plantmanager
yarn
yarn start

# or

cd plantmanager
npm install
npm run start
```
## Para executar este aplicativo em um emulador/simulador

### IOS 🍎

Na interface do servidor Expo, clique em `Run on iOS simulator`

### Android 👾

Na interface do servidor Expo, clique em `Run on Android device/emulator`

## Para executar este aplicativo em um dispositivo físico.

Faça downloado do APP Expo go em seu dispositivo.
  - [Android](https://play.google.com/store/apps/details?id=host.exp.exponent&hl=pt_BR&gl=US)
  - [IOS](https://apps.apple.com/br/app/expo-go/id982107779)


