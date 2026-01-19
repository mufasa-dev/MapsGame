
🌍 MapsGame
O MapsGame é uma aplicação web de exploração geográfica inspirada no clássico GeoGuessr. O jogador é transportado para um local aleatório do mundo através do Google Street View e deve usar suas habilidades de observação para marcar sua localização exata em um mapa interativo.

🎮 Como Jogar
Exploração 360°: Navegue pelas ruas em busca de pistas visuais como placas, idiomas, vegetação e arquitetura.

O Palpite: Marque no mapa mundi onde você acredita estar.

Pontuação: O sistema calcula a distância real entre o seu marcador e a localização correta. Quanto mais perto, mais pontos você ganha!

🚀 Diferenciais Tecnológicos
A aplicação foi construída focando em performance extrema e experiência do usuário, utilizando o que há de mais moderno no ecossistema web:

Astro Islands (Arquitetura de Ilhas): A estrutura do site é estática e ultrarrápida. Apenas o visualizador 360° e o mapa interativo são "ilhas" de interatividade hidratadas via JavaScript somente quando necessário.

Performance Imbatível: Renderização no lado do servidor (SSR) que garante tempos de carregamento mínimos, mantendo a imersão entre as rodadas.

Estilização com Tailwind CSS: Interface moderna, responsiva e com suporte nativo a modo escuro.

🛠️ Stack Técnica
Framework: Astro

APIs: Google Maps JavaScript API (Street View Panorama & Maps SDK).

Estilização: Tailwind CSS.

Cálculos Geográficos: Implementação da Fórmula de Haversine para precisão milimétrica de distância em uma esfera.

✨ Funcionalidades Principais
Categorias de Mapas: Escolha entre jogar no "Mundo", "Capitais Europeias" ou "Brasil".

Sistema de Pontuação Dinâmico: Cálculo de distância em tempo real.

Ranking Local: Armazenamento das melhores pontuações via localStorage (ou integração futura com Supabase).

Interface Imersiva: Design focado totalmente na visualização do mapa e exploração.

🛠️ Instalação e Execução
Se você deseja rodar o projeto localmente:

Clone o repositório:

Bash
git clone https://github.com/seu-usuario/mapsgame.git
Instale as dependências:

Bash
npm install
Configure sua chave da API do Google Maps no arquivo .env.

Inicie o servidor de desenvolvimento:

Bash
npm run dev
