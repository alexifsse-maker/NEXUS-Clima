# NEXUS Clima

PWA de previsão do tempo em português, com estilo NEXUS Tesla, busca de cidades, GPS, previsão de 24 horas e de 7 dias.

## Instalação
Ative GitHub Pages em Settings > Pages > Deploy from a branch > main > /(root). Abra o endereço HTTPS pelo Chrome Android e escolha Instalar app / Adicionar à tela inicial.

Dados e geocodificação: [Open-Meteo](https://open-meteo.com/). A API é consumida ao vivo e exige Internet para atualizar a previsão.

## Atualização automática (v1.1)
O aplicativo consulta o clima a cada 30 minutos quando está visível, e sempre que retorna ao primeiro plano. Em segundo plano, não são feitas consultas periódicas. O botão de atualizar permanece disponível.

## v1.2 — Offshore
Aba Meteorologia Marinha com coordenadas independentes (latitude/longitude), altura significativa de ondas, período, direção, swell, correntes e temperatura superficial, mais 48 horas de previsão pela Open-Meteo Marine API. Atualização quando aberto, a cada 30 minutos enquanto visível e ao retornar. Não utilizar como fonte exclusiva para decisões operacionais ou segurança marítima.
