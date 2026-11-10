# Vila Velha · Regiões e Parcelas

WebGIS para visualização de regiões e parcelas de Vila Velha, desenvolvido com QGIS, qgis2web e OpenLayers.

## Conteúdo cartográfico

A exportação inclui bairros, limite municipal, cinco regiões, grades regionais e grade total. Os nomes publicados incluem Centro, Grande Ibes, Grande Aribiri, Grande Cobilândia e Grande Jucu.

Use o mapa para consultar as camadas e os atributos associados às feições. Os dados devem ter sua data, escala e metodologia verificadas antes de apoiar decisões técnicas.

## Executar localmente

Requer Python 3:

```bash
git clone https://github.com/RebecaGis/Vila-Velha-Regioes-Parcelas.git
cd Vila-Velha-Regioes-Parcelas
python -m http.server 8000
```

Abra http://localhost:8000. Recursos externos e mapas base podem depender de internet.

## Estrutura

| Caminho | Finalidade |
| --- | --- |
| `index.html` | Página principal |
| `layers/` | Dados e definições das camadas |
| `styles/` | Estilos e legendas |
| `resources/` | Bibliotecas e folhas de estilo |
| `webfonts/` | Fontes de ícones |

## Manutenção

Preserve a estrutura de pastas e os caminhos relativos dos recursos. A exportação web está disponível neste repositório; o projeto QGIS de origem não está incluído.

A documentação anterior usava o nome PDAU-Arquivos. Este README identifica o repositório atual, sem alterar endereços de publicação ou configurações de hospedagem.

## Fontes e reutilização

A camada de bairros é identificada nos arquivos como IJSN. As demais fontes, datas de referência e condições de reutilização devem ser confirmadas com a documentação original do trabalho.
