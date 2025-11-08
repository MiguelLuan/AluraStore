<h1 align="center" style="font-weight: bold;"> AluraStore 🛒 - Análise de Dados</h1>

<p align="center">
  <img src="https://img.shields.io/badge/status-Concluido-green" alt="Status: Concluído"/>
  <img src="https://img.shields.io/github/languages/count/MiguelLuan/AluraStore" alt="Contagem de Linguagens GitHub"/>
  <img src="https://img.shields.io/github/last-commit/MiguelLuan/AluraStore" alt="Último Commit"/>
  <img src="https://img.shields.io/github/license/MiguelLuan/AluraStore" alt="Licença"/>
  <img src="https://img.shields.io/github/stars/MiguelLuan/AluraStore" alt="Estrelas"/>
</p>

<p align="center">
 <a href="#objective">Objetivo da Análise</a> • 
 <a href="#structure">Estrutura do Projeto</a> • 
 <a href="#steps">Etapas da Análise</a> • 
 <a href="#results">Principais Resultados</a> •
 <a href="#techs">Tecnologias Utilizadas</a> • 
 <a href="#execute">Como Executar o Projeto</a> • 
 <a href="#conclusion">Conclusão</a> • 
 <a href="#license">Licença</a> • 
</p>

<p align="center">
    Este projeto tem como objetivo realizar uma análise exploratória dos dados de vendas da <strong>AluraStore</strong>, buscando compreender o desempenho das lojas, produtos e categorias, além de identificar oportunidades de melhoria com base nos indicadores obtidos.</b>
</p>

---

<h2 id="objective">📊 Objetivo da Análise</h2>

<p>
  O notebook <strong>AluraStore.ipynb</strong> realiza uma série de análises com foco em:
  
  <li>O <strong>faturamento total</strong> das lojas;</li>
  <li>O <strong>O custo médio do frete</strong></li>
  <li>As <strong>categorias de produtos mais e menos vendidas</strong>;</li>
  <li>A <strong>média das avaliações de clientes</strong> por loja;</li>
  <li>Os <strong>produtos mais e menos vendidos</strong>;</li>
  <li>A identificação de <strong>tendências e padrões</strong> nos dados.</li>
  <br>
  Essas análises auxiliam o <strong>Sr. João</strong> (caso de estudo) a decidir <strong>qual loja vender</strong> com base em desempenho e indicadores de satisfação.
</p>

<h2 id="structure">🧩 Estrutura do Projeto</h2>

```
AluraStore
  ├── AluraStore.ipynb # Notebook principal com toda a análise
  ├── dados/ # Pasta (opcional) com os arquivos CSV utilizados
  └── README.md # Este arquivo de documentação
```

<h2 id="steps">🧠 Etapas da Análise</h2>

1. **Importação de bibliotecas**
   - Uso de `pandas`, `numpy`, `matplotlib` para tratamento e visualização.

2. **Carregamento dos dados**
   - Leitura dos arquivos de vendas e informações das lojas.

3. **Análises realizadas**
   - Faturamento por loja;
   - Receita por Estados;
   - Produtos e categorias mais e menos vendidos;
   - Frete médio por loja;
   - Avaliação média por loja;
   - Comportamento de Pagamento em Receita;

4. **Visualizações**
   - Gráficos de barras, dispersão e linhas para facilitar a interpretação;
   - Comparação entre preço e frete médio,faturamento total/categoria por loja,volume arrecadado por categoria e loja e evolução do faturamento ao decorrer dos messes com foco na loja 4.

5. **Conclusão**
   - Síntese dos resultados e indicação de qual loja apresenta menor desempenho geral.

<h2 id="results">📈 Principais Resultados</h2>

- **Loja com menor faturamento:** Loja 4
- **Categoria mais vendida:** Categoria Brinquedos 
- **Produto mais vendido:** Cômoda (moveis) - Loja 1
- **Loja com alta volatilidade**: Loja 4
- **Loja com melhor avaliação média:** Loja 3 

 <h2 id="techs">🛠️ Tecnologias Utilizadas</h2>

- **Python 3**
- **Pandas** — manipulação e análise de dados  
- **NumPy** — operações numéricas  
- **Matplotlib** — visualização de dados  
- **Google Colab / Jupyter Notebook** — ambiente de execução


<h2 id="execute">🚀 Como Executar o Projeto</h2>

1. Clone o repositório:
   ```bash
   git clone https://github.com/MiguelLuan/AluraStore.git
2. Acesse a pasta do projeto:
   ```bash
   cd AluraStore

3. Abra o notebook no Jupyter ou Google Colab:
   ```bash
   jupyter notebook AluraStore.ipynb
   | Certifique-se de ter instaladas as bibliotecas necessárias listadas no início do notebook.
   

<h2 id="conclusion">Conclusão</h2>

A análise fornece uma visão clara sobre o desempenho de cada loja, permitindo identificar qual apresenta:
  - Maior faturamento;
  - Melhores avaliações de clientes;
  - Melhor equilíbrio entre vendas e diversidade de produtos;
  - Melhor custo operacional;
  - Alta previsibilidade de Receita.

Com base nos indicadores, o Sr. João pode tomar uma decisão informada sobre qual loja vender.


<h2 id="contribute">🧑‍💻 Desenvolvedor(es)</h2>

| [<img src="https://avatars.githubusercontent.com/u/211078180?s=400&u=e42935c528efd7f3f727529e71286a5803fe4aa7&v=4" width=115><br><sub>Miguel Luan</sub>](https://github.com/MiguelLuan) |
| :---: 


<h2 id="license">📝 Licença</h3>

Este projeto esta sobe a licença [MIT](https://github.com/MiguelLuan/AluraStore/blob/main/LICENSE).
