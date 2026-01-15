MapsGame é uma aplicação web de exploração geográfica inspirada no clássico GeoGuessr, desenvolvida com o framework Astro. O objetivo é simples: o jogador é "jogado" em um local aleatório do mundo através do Google Street View e deve marcar no mapa onde acredita estar. Quanto mais próxima a marcação, maior a pontuação.

🚀 Diferenciais Tecnológicos
Astro Islands (Arquitetura de Ilhas): A casca do site (menus, rodapé e textos) é estática e ultrarrápida. Apenas o visualizador 360° e o mapa interativo são "ilhas" de interatividade hidratadas via JavaScript.

Performance Imbatível: Graças à renderização no lado do servidor (SSR), os tempos de carregamento são mínimos, garantindo que o jogador não perca a imersão entre as rodadas.

Integração de APIs: Utiliza a Google Maps JavaScript API para renderizar o Street View Panorama e o componente de mapa para palpites.

Estilização com Tailwind CSS: Interface moderna, responsiva e com suporte a modo escuro, focada totalmente na experiência do mapa.

🎮 Funcionalidades Principais
Exploração 360°: Navegação completa pelas ruas para buscar pistas visuais (placas, vegetação, arquitetura).

Sistema de Pontuação Dinâmico: Cálculo de distância em tempo real usando a fórmula de Haversine para determinar a precisão do palpite.

Categorias de Mapas: Possibilidade de escolher "Mundo", "Capitais Europeias" ou "Brasil", filtrando as coordenadas geográficas.

Ranking Local: Armazenamento das melhores pontuações via localStorage ou integração com banco de dados leve (como Supabase).
