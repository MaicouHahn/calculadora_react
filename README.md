# Calculadora - React Native com Expo

Exercício da disciplina de Soluções Mobile.

App de calculadora simples feito com React Native, Expo e React Native Paper.
Faz as operações básicas: soma (+), subtração (-), multiplicação (*) e divisão (/).

## O que eu usei

- React Native com Expo
- React Native Paper (componentes Button, Card e Text)
- Hook `useState` para guardar o valor do display, o primeiro número e a operação

## Como rodar

1. Clonar o repositório
2. Instalar as dependências:
   ```
   npm install
   ```
3. Rodar o projeto:
   ```
   npx expo start
   ```
4. Abrir no celular com o app Expo Go (lendo o QR Code) ou no emulador

## Como funciona

- Digita o primeiro número
- Escolhe a operação
- Digita o segundo número
- Aperta `=` para ver o resultado
- O botão `C` limpa tudo
- Se tentar dividir por zero aparece "Erro"
