# QuestMaster

**QuestMaster** é um aplicativo de lista de tarefas com uma abordagem única de gamificação. Transforme suas tarefas diárias em aventuras emocionantes, onde você pode ganhar recompensas, fortalecer seu avatar e enfrentar desafios épicos!

## Funcionalidades

- **Gamificação de Tarefas:** Conclua suas tarefas diárias e ganhe moedas virtuais.
- **Customização do Avatar:** Use suas moedas para comprar itens, roupas ou magias para o seu personagem.
- **Desafios Semanais:** Enfrente um chefe (boss) no final de cada semana, usando a experiência e poderes adquiridos ao completar tarefas.
- **Histórico de Tarefas:** Acompanhe seu progresso e veja como suas tarefas concluídas impulsionam seu sucesso no jogo.

## Tecnologias Utilizadas

- **Frontend:** React Native
- **Backend:** Firebase
- **Autenticação:** Firebase Authentication
- **Banco de Dados:** Firestore
- **Gerenciamento de Estado:** Redux
- **Armazenamento de Imagens:** Firebase Storage

## Como Executar o Projeto

1. Clone este repositório:

   ```bash
   git clone https://github.com/seu-usuario/questmaster.git
   ```
2. Instale as dependências:

   ```bash
   cd questmaster
   npm install
   ```
3. Configure o Firebase:

   - Crie um projeto no [Firebase](https://firebase.google.com/).
   - Adicione o arquivo `google-services.json` no diretório `android/app`.
   - Adicione o arquivo `GoogleService-Info.plist` no diretório `ios/`.
4. Execute o aplicativo:

   ```bash
   npx react-native run-android
   npx react-native run-ios
   ```

## Contribuição

Se você deseja contribuir para o QuestMaster, fique à vontade para abrir um pull request ou relatar problemas na aba de Issues.
