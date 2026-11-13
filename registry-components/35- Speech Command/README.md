# Speech Command

## Objetivo
O Speech Command permite controlar elementos da cena
através de comandos de voz.

## Funcionamento
O exemplo reconhece dois comandos:
- "show menu": apresenta o menu.
- "hide menu": esconde o menu.

## Teste
1. Abrir a página através de HTTPS ou localhost.
2. Permitir o acesso ao microfone.
3. Utilizar o Google Chrome.
4. Dizer "show menu".
5. Dizer "hide menu".

## Dependências
- A-Frame 0.7.0
- annyang 2.5.0
- aframe-speech-command-component

## Nota
O reconhecimento de voz depende do suporte do browser
à Web Speech API.