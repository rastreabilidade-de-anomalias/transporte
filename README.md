# Roteirização · rotas de ônibus

App para mapear rotas de ônibus: cada rota com sua cor, paradas numeradas,
caminho pintado pelas ruas e destaque dos trechos e paradas que mais de uma rota usa.

## Importante: nenhum dado fica neste repositório

Este repositório guarda **só o app**. As rotas, paradas e coordenadas são
carregadas no aparelho, pelo botão **Carregar planilha**, e ficam salvas
apenas no navegador de quem usa. Não envie planilhas para cá.

## Como usar

1. Abra o link do GitHub Pages.
2. Toque em **Carregar planilha** e escolha a planilha das rotas
   (colunas: `rota`, `ordem`, `tipo`, `latitude`, `longitude`, `referencia`).
3. Ou crie uma rota pelo nome e adicione pontos colando a coordenada
   do Google Maps ou tocando no mapa.
4. Use **Salvar em Excel** para guardar uma cópia dos dados.

## Serviços usados (gratuitos, pela internet)

- Mapa: Esri World Street Map e World Imagery
- Caminho pelas ruas: OSRM (router.project-osrm.org)
- Nome das ruas: Nominatim / OpenStreetMap
- Bibliotecas: Leaflet 1.9.4 e SheetJS 0.18.5 (cdnjs)

Esses serviços recebem apenas as coordenadas consultadas.
