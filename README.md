# Temoco

O **Temoco** é um aplicativo mobile idealizado como Trabalho de Conclusão de Curso do Técnico em Desenvolvimento de Sistemas do SENAI. A proposta é oferecer uma experiência lúdica de apoio à rotina e à aprendizagem de crianças autistas, com personagens, tarefas e jogos, além de uma área destinada aos responsáveis.

Este repositório reúne a parte do projeto em que atuei no desenvolvimento das interfaces e na organização da aplicação.

## Design do projeto

Os protótipos das telas foram criados no Figma.

**[Visualizar o projeto Temoco no Figma](https://www.figma.com/design/bXKAvjbw4N3POnmn5UdG2W/Temoco?node-id=6-2&t=36m81q4NpZZTs9c2-1)**

## Áreas do aplicativo

O projeto reúne interfaces para diferentes etapas da experiência:

### Cadastro e personalização inicial

- Telas de abertura, cadastro e login.
- Campos para informações do responsável e da criança.
- Questionário inicial para orientar a personalização da experiência.
- Preferências visuais e sonoras, como brilho, música, efeitos sonoros e tamanho da fonte.

### Área infantil

- Tela principal com acesso ao perfil, às tarefas e aos jogos.
- Perfil da criança com indicadores de pontos, tarefas e jogos.
- Seleção de personagens, incluindo opções liberadas e bloqueadas.
- Menu com tarefas concluídas e pendentes.
- Menus e telas relacionados a jogos, diário de missões e amigos.
- Elementos de progressão, como pontos e Tomocoins.

### Área dos responsáveis — Mamãe Ganso

- Telas de relatórios e visualização de desempenho.
- Gerenciamento de perfis das crianças.
- Configurações da experiência.
- Área de Tomocoins e apresentação de planos de assinatura.
- Mural de publicações, incluindo uma interface para perfil profissional.

> **Nota sobre o escopo:** os itens acima descrevem as interfaces e os fluxos representados no projeto. Nem todas as funcionalidades planejadas foram concluídas ou conectadas a serviços e dados persistentes.

## Minha contribuição

Atuei no projeto como **Scrum Master e desenvolvedora**. Criei os protótipos das telas no Figma e implementei as interfaces no aplicativo, trabalhando na estrutura visual das áreas infantil e dos responsáveis. Também participei da organização do desenvolvimento e deixei a aplicação preparada para a continuidade do trabalho e uma futura integração com banco de dados.

## Tecnologias

As principais tecnologias e bibliotecas utilizadas ou declaradas no projeto incluem:

- **React Native** — desenvolvimento da interface mobile.
- **Expo** — ferramentas e ambiente para desenvolvimento React Native.
- **TypeScript** — tipagem do código.
- **Expo Router** — organização das rotas e da navegação.
- **NativeWind e Tailwind CSS** — estilização das interfaces.
- **Clerk Expo, Async Storage, Expo SecureStore e React Native Chart Kit** — bibliotecas presentes nas dependências do projeto para recursos como autenticação, armazenamento e gráficos.

A presença de uma biblioteca nas dependências não significa que sua integração esteja completa ou funcionando em todos os fluxos.

## Estrutura geral

```text
TCC-Temoco/
├── android/          # Projeto nativo Android
├── src/
│   ├── app/           # Rotas e telas da aplicação
│   │   ├── (auth)/    # Área relacionada à autenticação
│   │   ├── (main)/    # Área principal
│   │   ├── (mmg)/     # Área Mamãe Ganso
│   │   └── (new)/     # Fluxos adicionais
│   ├── assets/        # Recursos visuais
│   ├── components/   # Componentes reutilizáveis
│   ├── context/      # Contextos da aplicação
│   └── styles/       # Estilos globais
├── app.json          # Configurações do Expo
├── package.json      # Dependências e scripts
└── tsconfig.json     # Configuração do TypeScript
```

## Estado do projeto

O Temoco permaneceu como um projeto acadêmico em desenvolvimento, e não como um produto finalizado. Algumas telas e fluxos foram implementados parcialmente; outros comportamentos planejados, incluindo partes da experiência de carregamento, não foram concluídos. A integração final com banco de dados também ficou para uma etapa futura.

Por isso, este repositório deve ser entendido como um registro do trabalho desenvolvido no TCC — especialmente das interfaces e da estrutura preparada para continuidade — e não como uma versão pronta para produção. A documentação não descreve as telas do protótipo como funcionalidades completas quando isso não foi confirmado.
