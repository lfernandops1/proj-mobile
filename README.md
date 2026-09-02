# Interface mobile de autenticação

<p>
  <img src="https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React Native" />
  <img src="https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white" alt="Expo" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Formik-2563EB?style=flat-square" alt="Formik" />
  <img src="https://img.shields.io/badge/Yup-111827?style=flat-square" alt="Yup" />
</p>

Estudo de interface mobile para um fluxo de autenticação e cadastro. O projeto combina navegação em etapas, formulários validados e uma camada visual construída com componentes reutilizáveis.

## Recursos

- Tela de acesso com perfil salvo
- Cadastro em múltiplas etapas
- Campos de senha reutilizáveis
- Validação declarativa com Formik e Yup
- Navegação em pilha com React Navigation
- Opções visuais para autenticação social
- Ajustes responsivos para diferentes dimensões de tela
- Execução em Android, iOS e Web pelo Expo

> Este projeto apresenta o fluxo e a experiência de interface. As ações de autenticação social e o envio definitivo do cadastro são demonstrativos.

## Estrutura

```text
src/components     componentes compartilhados
src/screens        telas de acesso e cadastro
src/navigations    rotas e tipos de navegação
src/utils          utilitários de responsividade
src/assets         imagens, ícones e recursos visuais
```

## Executando o projeto

### Pré-requisitos

- Node.js
- Yarn
- Ambiente compatível com Expo SDK 44

```bash
git clone https://github.com/lfernandops1/proj-mobile.git
cd proj-mobile
yarn install
yarn start
```

Atalhos disponíveis:

```bash
yarn android
yarn ios
yarn web
```

## Stack

| Área | Tecnologia |
|---|---|
| Interface | React Native |
| Plataforma | Expo |
| Linguagem | TypeScript |
| Navegação | React Navigation |
| Formulários | Formik e Yup |
| Estilos | StyleSheet e styled-components |

## Autor

[Fernando Santos](https://github.com/lfernandops1) · [LinkedIn](https://www.linkedin.com/in/fernando-p-santos/)
