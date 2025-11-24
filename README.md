## 🍽️ Foods – Delivery App

Aplicativo de delivery moderno desenvolvido com Expo, React Native, Expo Router e NativeWind, combinando performance, organização e rapidez no desenvolvimento.
Inclui também uma API fake usando json-server para facilitar testes durante o desenvolvimento.

## 🚀 Tecnologias utilizadas

- **Expo** (SDK 50+)
- **React Native**
- **Expo Router** (file-based routing)
- **TypeScript**
- **NativeWind** + `react-native-css-interop` (Tailwind no React Native)
- **json-server** (API fake via arquivo `db.json`)

## 📦 Como Executar o Projeto
1. Instalar dependências

   ```bash
   npm install
   ```
   ou
   ```bash
   yarn
   ```
   
2. Iniciar o app
   ```bash
   yarn
   ```

## 🌐 Rodando o Servidor Fake API

Instalar json-server
   ```bash
 npm install -g json-server
   ```
   ou
   ```bash
npm install json-server --save-dev
   ```
Iniciar o servidor
   ```bash
 npx json-server db.json
   ```
API disponível em:
```bash
http://localhost:3000
```

## 🎨 Estilização com NativeWind

```
import { Text, View } from "react-native";

export function Example() {
  return (
    <View className="flex-1 items-center justify-center bg-slate-950">
      <Text className="text-2xl font-semibold text-amber-400">
        Hello, NativeWind 👋
      </Text>
    </View>
  );
}

```

## 🗂 Estrutura do Projeto

```
.
├── src
│   ├── app
│   │   ├── _layout.tsx      # Layout raiz (Expo Router)
│   │   └── index.tsx        # Tela inicial (Home)
│   ├── components           # Componentes reutilizáveis
│   └── ...
├── assets                   # Imagens, ícones
├── db.json                  # Banco fake (json-server)
├── global.css               # Configuração NativeWind/Tailwind
├── tailwind.config.js       # Config Tailwind
└── ...
```


📚 Links úteis

- **Documentação do Expo** → https://docs.expo.dev  
- **Expo Router – File-based routing** → https://docs.expo.dev/router/introduction  
- **Documentação do NativeWind** → https://www.nativewind.dev  
- **json-server no GitHub** → https://github.com/typicode/json-server



## 🤝 Contribuindo

Sinta-se à vontade para:
* Questões em aberto
* Sugira melhorias
* Adicionar novas telas usando o NativeWind
* Estenda a db.json com novos endpoints de API


