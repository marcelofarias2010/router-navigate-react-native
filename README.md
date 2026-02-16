# Instruções das aulas

## Aula 01
### Navegação em Stack e Empilhamento de Telas
1. navigate
📖 Docs: https://reactnavigation.org/docs/native-stack-navigator
✅ O que faz:
* Navega para uma tela
* Se ela já estiver na stack, pode reutilizar
* Não duplica telas se já estiver no topo
2. push
📖 Docs: https://reactnavigation.org/docs/stack-actions/#push
✅ O que faz:
* Sempre adiciona uma nova instância da tela na pilha
* Mesmo que já esteja na stack

3. replace
📖 Docs: https://reactnavigation.org/docs/stack-actions/#replace
✅ O que faz:
* Remove a tela atual
* Coloca outra no lugar
* Não permite voltar para a anterior

## Aula 02
### Parâmetros na Rota, Rotas Aninhadas e Tela de Not Found

## Aula 03
### Navegação em Tabs (Abas)

navigation.navigate() em Tabs
📖 Docs: https://reactnavigation.org/docs/bottom-tab-navigator
✅ O que faz em Tabs:
* Muda para a aba desejada
* Não cria nova instância
* Apenas alterna a tab ativa

## Aula 04
### Navegação em Drawer (Menu Hambúrguer)

Exemplo básico — Drawer
Instalação (caso ainda não tenha):
npm install @react-navigation/drawer
navigation.navigate() no Drawer
📖 Docs: https://reactnavigation.org/docs/drawer-navigator

✅ O que faz:
* Muda para outra tela do Drawer
* Não cria nova instância
* Apenas troca a rota ativa


# Welcome to your Expo app 👋

This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

## Get started

1. Install dependencies

   ```bash
   npm install
   ```

2. Start the app

   ```bash
   npx expo start
   ```

In the output, you'll find options to open the app in a

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).

## Get a fresh project

When you're ready, run:

```bash
npm run reset-project
```

This command will move the starter code to the **app-example** directory and create a blank **app** directory where you can start developing.

## Learn more

To learn more about developing your project with Expo, look at the following resources:

- [Expo documentation](https://docs.expo.dev/): Learn fundamentals, or go into advanced topics with our [guides](https://docs.expo.dev/guides).
- [Learn Expo tutorial](https://docs.expo.dev/tutorial/introduction/): Follow a step-by-step tutorial where you'll create a project that runs on Android, iOS, and the web.

## Join the community

Join our community of developers creating universal apps.

- [Expo on GitHub](https://github.com/expo/expo): View our open source platform and contribute.
- [Discord community](https://chat.expo.dev): Chat with Expo users and ask questions.
