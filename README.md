GG Store - Trabalho N2 (Mobile)

Como rodar:
1. Abra a pasta do projeto no terminal
2. npm install
3. npx expo start
   - Celular: ler o QR Code com o Expo Go
   - Emulador Android: apertar a tecla A
   - Navegador: apertar a tecla W

Estrutura:
- App.js ............................ NavigationContainer + AppProvider
- src/dados.js ...................... catálogo estático (7 jogos)
- src/dao/GameDAO.js ................ chamadas ao AsyncStorage (favoritos e perfil)
- src/contexts/AppContext.js ........ estado global (wishlist, nickname, tema)
- src/componentes/CardJogo.js ....... card da vitrine
- src/componentes/ItemWishlist.js ... item da lista de desejos
- src/screens/ ...................... TelaVitrine, TelaDetalhes, TelaPerfil
- src/navigation/Navegacao.js ....... Abas + Pilha
