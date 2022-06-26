# EconoStat Automagic

Ferramentas que automatizam o processo de captar preços e formar indicadores econômicos para a cidade de Londrina.

## Mercados

- Carrefour        (Shopping Catuaí)
- Muffato          (Rua Duque de Caxias, 1200)
- Cidade Canção    (Av. Maringá)
- Condor           (Rua Rio Grande do Sul, 50)
- Musamar          (Rua Pernambuco, 785)
- Viscardi         (Av. Inglaterra, 505)
- Tonhão           (Av. Dez de Dezembro, 6237)
- Super Golff      (Av. Saul Elkind, 4607)
- 88               (Av. das Maritacas, 1546)
- Santarém         (Av. Saul Elkind, 1068)
- Almeida Mercados (Rua Araçatuba, 218)
- Walmart          (Shopping Boulevard)

## Produtos

- Açúcar           (5kg)
- Arroz            (5kg)
- Banana           (1kg)
- Batata           (1kg)
- Café             (500g)
- Carne            (1kg)
- Farinha de trigo (1kg)
- Feijão           (1kg)
- Leite            (1L)
- Margarina        (500g)
- Óleo             (900mL)
- Pão francês      (50g)
- Tomate           (1kg)

## Frequência

- UTFPR:               Mensal
- EconoStat Automagic: Diária

## Tecnologias

As ferramentas são baseadas em Javascript Node com extensão Typescript e utilizam tecnologia de contêineres Docker para fácil replicação e deployment em ambientes de produção.

## Estrutura dos arquivos

automail/ é responsável por fazer o download automático de arquivos .csv ou .xlsx anexos por e-mail por membros responsáveis da UTFPR.

dashboard/ é a ferramenta de visualização online dos dados captados pelas universidades e pelo scraper. Utiliza React.js como tecnologia de frontend.

database/ contém definições da base de dados que agrega os preços obtidos.

scraper/ é a implementação de uma API REST que fornece dados retirados de sites dos principais supermercados de Londrina.