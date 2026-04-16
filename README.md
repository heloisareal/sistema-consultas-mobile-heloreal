# Sistema de Consultas Mobile
- Heloísa Real - 554535

Aplicação mobile construída com **Expo** e **React Native** que simula o fluxo básico de uma consulta médica. O app apresenta informações completas da consulta, incluindo médico, paciente e status, com possibilidade de interação direta na interface.

---

## Tecnologias Utilizadas

- Expo  
- React Native  
- React  
- TypeScript  

---

## Organização do Projeto

```
.
├── App.tsx
├── src
│   ├── components
│   │   └── ConsultaCard.tsx
│   ├── interfaces
│   │   ├── consulta.ts
│   │   └── medico.ts
│   ├── screens
│   │   └── Home.tsx
│   ├── styles
│   │   ├── app.styles.ts
│   │   └── consultaCard.styles.ts
│   └── types
│       ├── especialidade.ts
│       ├── paciente.ts
│       └── statusConsulta.ts
├── assets
└── package.json
```

---

## Como Rodar o Projeto

### Pré-requisitos

Antes de começar, você precisa ter instalado:

- Node.js  
- npm  
- Expo Go (no celular) **ou** emulador configurado (Android/iOS)  

---

### Instalação

```bash
npm install
```

---

### Executando a aplicação

```bash
npx expo start
```

Após iniciar o servidor, você pode:

- Pressionar **`a`** → abrir no Android  
- Pressionar **`i`** → abrir no iOS (somente macOS)  
- Pressionar **`w`** → abrir no navegador  
- Escanear o QR Code com o Expo Go  

---

### Atalhos disponíveis

```bash
npm run android
npm run ios
npm run web
```

---

## Estrutura de Dados

A aplicação utiliza entidades simples para simular o domínio:

- **Especialidade** → área médica do profissional  
- **Médico** → dados do profissional + especialidade  
- **Paciente** → informações cadastrais  
- **Consulta** → reúne todos os dados da consulta  
- **StatusConsulta** → controla o estado atual da consulta  

---

## Tela Principal

A tela `Home` funciona como ponto central da aplicação:

- Cria dados fictícios em memória  
- Renderiza o componente `ConsultaCard`  
- Permite interações com o status da consulta  

### O componente `ConsultaCard` é responsável por:

- Exibir status atual  
- Mostrar médico, paciente, data, valor e observações  
- Permitir confirmar ou cancelar consultas agendadas  
- Atualizar a interface conforme a ação do usuário  

---

## Scripts Disponíveis

```bash
npm start
npm run android
npm run ios
npm run web
```

---
