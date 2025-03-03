DevPost
DevPost é uma aplicação mobile desenvolvida em React Native que permite aos usuários compartilhar posts, interagir com outros usuários através de curtidas e gerenciar seus perfis.

🚀 Tecnologias Utilizadas
React Native
Firebase (Authentication, Firestore, Storage)
Styled Components
React Navigation
React Native Vector Icons
React Native Animatable
React Native Image Picker
Date-fns
Async Storage
📋 Funcionalidades
Autenticação
Login com email e senha
Cadastro de novos usuários
Persistência de login
Posts
Criação de posts
Feed com posts de todos usuários
Sistema de curtidas
Visualização de posts por usuário
Carregamento lazy loading do feed
Pull to refresh
Perfil
Atualização de foto de perfil
Edição de nome de usuário
Visualização de informações do usuário
Busca
Pesquisa de usuários por nome
Visualização de perfis de outros usuários
🎨 Layout
A aplicação possui um design moderno com:

Tema escuro
Animações suaves
Interface intuitiva
Componentes reutilizáveis
Design responsivo
📁 Estrutura do Projeto

src/
  ├── components/
  │   ├── Header/
  │   ├── PostsList/
  │   └── SearchList/
  ├── contexts/
  │   └── auth.js
  ├── pages/
  │   ├── Home/
  │   ├── Login/
  │   ├── NewPost/
  │   ├── PostsUser/
  │   ├── Profile/
  │   └── Search/
  └── routes/
🔧 Instalação
Clone o repositório
BASH

git clone https://github.com/seu-usuario/devpost.git
Instale as dependências
BASH

cd devpost
npm install
Configure o Firebase
Crie um projeto no Firebase Console
Adicione as configurações no arquivo firebase.js
Habilite Authentication, Firestore e Storage
Execute o projeto
BASH

npx react-native run-android
# ou
npx react-native run-ios
🔐 Variáveis de Ambiente
Crie um arquivo .env na raiz do projeto com as seguintes variáveis:


FIREBASE_API_KEY=sua_api_key
FIREBASE_AUTH_DOMAIN=seu_auth_domain
FIREBASE_PROJECT_ID=seu_project_id
FIREBASE_STORAGE_BUCKET=seu_storage_bucket
FIREBASE_MESSAGING_SENDER_ID=seu_sender_id
FIREBASE_APP_ID=seu_app_id
📱 Screenshots
[Adicione screenshots da sua aplicação aqui]

👥 Contribuição
Faça o fork do projeto
Crie uma branch para sua feature (git checkout -b feature/AmazingFeature)
Commit suas mudanças (git commit -m 'Add some AmazingFeature')
Push para a branch (git push origin feature/AmazingFeature)
Abra um Pull Request
📄 Licença
Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

📫 Contato
Fabio Sena
18 981579318
https://www.linkedin.com/in/fabio-vicente-de-sena/
https://github.com/fabiosena1436