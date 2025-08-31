# BAT PASS APP

Este é um aplicativo simples de gerenciamento e geração de senhas, desenvolvido com React Native e Expo.

## Funcionalidades
- Gerar senhas (exemplo: botão "GENERATE")
- Exibir senha gerada em campo de texto
- Copiar senha gerada (botão "👾COPY")
- Interface amigável e responsiva

## Estrutura do Projeto
```
├── assets/
│   └── bat-logo.png
├── src/
│   └── components/
│       └── bat_logo/
│           ├── BatLogo.tsx
│           ├── BatLogoStyles.tsx
│           └── BatButton/
│               └── BatButton.tsx
│           └── BatTextInput/
│               └── BatTextInput.tsx
├── App.tsx
├── package.json
├── tsconfig.json
```

## Como executar
1. Instale as dependências:
   ```bash
   npm install
   ```
2. Inicie o projeto:
   ```bash
   npx expo start
   ```
3. Escolha o modo de execução (Android, iOS ou Web) conforme sua preferência.

## Tecnologias utilizadas
- React Native
- Expo
- TypeScript

## Observações
- O arquivo de logo deve estar em `assets/bat-logo.png`.
- O botão "GENERATE" gera uma senha de exemplo.
- O botão "👾COPY" pode ser adaptado para copiar a senha para a área de transferência.

## Autor
Feito para fins de estudo e demonstração.
