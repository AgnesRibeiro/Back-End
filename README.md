# 📚 Senac Biblioteca Digital - Sistema de Usuários
Sistema completo de gerenciamento de usuários para biblioteca com backend e mobile.

Comandos de Instalação (Backend):

# Navegar para o repositório do backend

cd /workspaces/Back-End/backend-crud

# Instalar todas as dependências

npm install

# Se precisar instalar manualmente:

npm install express cors

npm install -D nodemon

# 🚀 PASSO A PASSO - EXECUTAR TUDO

1. PRIMEIRO: BACKEND

Terminal 1- Backend

cd /workspaces/Back-End/backend-crud

npm run dev

Deve aparecer:
🚀 Backend rodando na porta: 3001
🌐 URL: http://localhost:3001

Teste o Backend:

No navegador ou Thunder Client:

http://localhost:3001/usuarios

Deve retornar JSON com usuários

# 📞 SUPORTE RÁPIDO
Comandos de Emergência:

Reinstalar tudo (backend)

cd /workspaces/Back-End/backend-crud

rm -rf node_modules package-lock.json

npm install


# 🛠️ SOLUÇÃO DE PROBLEMAS COMUNS

Erro: "Module not found"

No mobile OU backend:

npm install

ou

npm ci

Erro: "Port already in use"

No backend, mude a porta no server.js

const PORT = 3002; # ou 3003, 3004...

Erro no Expo: "Unable to resolve module"

cd /workspaces/Mobile/mobile-crud

npx expo start -c  # Limpa cache

Erro: "Network request failed" (iOS)

Use 127.0.0.1 em vez de localhost

Ou execute: (npx expo start --tunnel)