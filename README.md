# Análise de Dados do Campeonato Brasileiro utilizando o claude sonnet 4.0

## Descrição do Projeto

Este projeto consiste em uma análise exploratória e estatística aprofundada dos dados do Campeonato Brasileiro de Futebol. Utilizando técnicas de ciência de dados e visualização, este estudo revela padrões e tendências nas partidas de futebol brasileiro, explorando desde a distribuição de cartões e gols até análises multivariadas avançadas com PCA e clustering.

## Conjuntos de Dados

O projeto utiliza quatro datasets principais:

1. **campeonato-brasileiro-cartoes.csv**: Informações sobre cartões amarelos e vermelhos
   - Colunas: partida_id, rodata, clube, cartao, atleta, num_camisa, posicao, minuto

2. **campeonato-brasileiro-estatisticas-full.csv**: Métricas de jogo
   - Colunas: partida_id, rodata, clube, chutes, chutes_no_alvo, posse_de_bola, passes, precisao_passes, faltas, cartao_amarelo, cartao_vermelho, impedimentos, escanteios

3. **campeonato-brasileiro-full.csv**: Detalhes completos das partidas
   - Colunas: ID, rodata, data, hora, mandante, visitante, formacao_mandante, formacao_visitante, tecnico_mandante, tecnico_visitante, vencedor, arena, mandante_Placar, visitante_Placar, mandante_Estado, visitante_Estado

4. **campeonato-brasileiro-gols.csv**: Dados sobre os gols marcados
   - Colunas: partida_id, rodata, clube, atleta, minuto, tipo_de_gol

## Pré-requisitos

Para executar este projeto, você precisará de:

- Python 3.7+
- Jupyter Notebook ou JupyterLab
- Bibliotecas Python: pandas, numpy, matplotlib, seaborn, scikit-learn

## Instalação

Clone o repositório e instale as dependências:

```bash
git clone https://github.com/seu-usuario/campeonato-brasileiro-analise.git
cd campeonato-brasileiro-analise
pip install -r requirements.txt
```

## Como Usar

1. Inicie o Jupyter Notebook:
```bash
jupyter notebook
```

2. Abra o arquivo `analise.ipynb` para explorar todas as análises.

3. Execute todas as células para reproduzir as visualizações e resultados.

## Principais Análises

O projeto inclui as seguintes análises:

### 1. Análise de Cartões
- Distribuição temporal de cartões amarelos e vermelhos
- Clubes com mais cartões
- Evolução de cartões por rodada

### 2. Estatísticas de Jogo
- Padrões de chutes, passes e faltas
- Eficiência de finalização por clube
- Correlações entre diferentes métricas de jogo

### 3. Análise de Resultados
- Distribuição de vitórias por clube
- Vantagem do mandante
- Padrões de placar

### 4. Análise de Gols
- Artilheiros do campeonato
- Distribuição temporal dos gols
- Tipos de gols (pênaltis, gols contra)
- Clubes com maior poder ofensivo

### 5. Análises Avançadas
- Análise de Componentes Principais (PCA)
- Clustering de partidas por características estatísticas
- Análises multivariadas de padrões de jogo

## Resultados Principais

Entre as descobertas mais significativas:

- Os cartões aumentam dramaticamente nos minutos finais das partidas
- Existe uma clara vantagem para os times mandantes
- A marcação de gols é mais frequente no final de cada tempo
- Clubes como Flamengo e Palmeiras lideram em eficiência ofensiva
- Existem fortes correlações entre ações técnicas e disciplinares
- As partidas podem ser agrupadas em clusters distintos com base em seus perfis estatísticos

## Tecnologias Utilizadas

- **Python**: Linguagem de programação principal
- **Pandas**: Manipulação e análise de dados
- **NumPy**: Computação numérica
- **Matplotlib & Seaborn**: Visualização de dados
- **Scikit-learn**: Análises estatísticas avançadas (PCA, K-means)
- **Jupyter Notebook**: Ambiente de desenvolvimento interativo

## Contribuição

Contribuições são bem-vindas! Para contribuir:

1. Faça um fork do projeto
2. Crie sua feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit suas alterações (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## Autor

[Seu Nome] - [seu-email@exemplo.com]

## Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo LICENSE para mais detalhes.

## Agradecimentos

- À CBF pelos dados do Campeonato Brasileiro (ou mencione a fonte original dos dados)
- A todos os clubes e jogadores que fazem do Campeonato Brasileiro um dos mais competitivos do mundo
