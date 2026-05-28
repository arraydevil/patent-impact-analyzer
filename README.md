# Patent Impact Analyzer: Cálculo de CII com Dados do Lens.org

Este projeto automatiza o cálculo do **Competitive Impact Index (CII)** para patentes, permitindo identificar tecnologias disruptivas em grandes volumes de dados extraídos do Lens.org.

## 💡 Contexto
O CII é uma métrica que normaliza o número de citações de uma patente em relação à média de citações do seu ano de publicação. Isso permite comparar de forma justa o impacto de uma patente dos anos 90 com uma patente de 2020.

## 🛠️ Tecnologias Utilizadas
- **Python 3.10**
- **Pandas**: Manipulação e limpeza de dados.
- **Matplotlib/Seaborn**: Visualização de distribuições e rankings.

## 📊 Resultados Obtidos
- Processamento automático de exportações CSV do Lens.
- Identificação de patentes 'Outliers' com impacto até 40x superior à média do setor.
- Visualização clara da dominância tecnológica por ano.

## 🚀 Como Executar
1. Clone o repositório.
2. Instale as dependências: `pip install pandas matplotlib seaborn`.
3. Execute o notebook na pasta `/notebooks`.
