# BioGuard — Sistema de Controle de Acesso

Projeto demonstrativo de controle de acesso com webcam, MediaPipe Face Detection e simulação visual de portão.

## Como executar localmente

1. Baixe ou clone este repositório.
2. Abra a pasta no Visual Studio Code.
3. Execute o arquivo `index.html` com a extensão **Live Server** ou use um servidor local.
4. Permita o acesso à webcam quando o navegador solicitar.

> A webcam normalmente precisa de contexto seguro: `localhost` ou HTTPS. O GitHub Pages fornece HTTPS.

## O que o projeto demonstra

- Detecção de rosto com MediaPipe Face Detection.
- Exibição da imagem da webcam e marcação do rosto.
- Simulação de acesso autorizado ou negado.
- Animação de portão e histórico de eventos.

## Limitação importante

Este projeto detecta a presença de um rosto, mas **não identifica a identidade real da pessoa**. Os modos “morador” e “desconhecido” são simulações selecionadas na interface; não use como sistema real de segurança.
