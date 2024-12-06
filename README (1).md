
# Projeto de Conclusão de Módulo: Análise de Dados e Modelos de Machine Learning

## Autor
**Nome**: [Seu Nome]  
**GitHub**: [Seu GitHub](https://github.com/seuusuario)

---

## Sobre o Projeto
Este projeto foi desenvolvido como parte do processo seletivo para a **Ada & Rogério Ltda**. O objetivo é aplicar técnicas de análise de dados e machine learning em dois datasets distintos, explorando insights e desenvolvendo modelos supervisionados e/ou não supervisionados.

Datasets utilizados:
1. **Netflix Titles** - Análise de títulos disponíveis na plataforma Netflix.
2. **Students Performance** - Análise do desempenho de estudantes em diferentes áreas acadêmicas.

---

## Dataset 1: Netflix Titles
**Descrição**: Contém informações detalhadas sobre os títulos disponíveis na Netflix, incluindo tipo (Movie ou TV Show), gêneros, ano de lançamento, classificação indicativa e mais.

### O que foi feito:
1. **Análise de Dados**:
   - Distribuição entre `Movies` e `TV Shows`.
   - Gêneros mais populares.
   - Tendências ao longo dos anos de lançamento.
   - Exploração das classificações indicativas (rating).

   ![Gráfico 1](notebook_0_image_0.png)
   ![Gráfico 2](notebook_0_image_1.png)

2. **Modelo Desenvolvido**:
   - **Modelo Não Supervisionado**:
     - **Algoritmo**: KMeans.
     - **Objetivo**: Identificar padrões entre os títulos com base em gêneros e anos.
     - **Clusters**: `N` clusters identificados com características como `[descreva os clusters]`.

---

## Dataset 2: Students Performance
**Descrição**: Contém informações sobre o desempenho de estudantes em matemática, leitura e escrita, além de dados como gênero, etnia e tipo de preparo para testes.

### O que foi feito:
1. **Análise de Dados**:
   - Distribuição por gênero e etnia.
     ![Distribuição por Gênero](students_image_0.png)
   - Comparação de desempenhos médios em matemática, leitura e escrita.
     ![Desempenho Médio por Etnia](students_image_1.png)
   - Correlações entre diferentes áreas de desempenho.
     ![Correlação entre Notas](students_image_2.png)

2. **Modelo Desenvolvido**:
   - **Modelo Supervisionado**:
     - **Target**: Classificar os estudantes em categorias de desempenho (`alto`, `médio`, `baixo`).
     - **Algoritmo**: Random Forest.
     - **Resultados**: Acurácia de `YY%`.

---

## Conclusões
- **Netflix Titles**:
  - Os clusters revelaram tendências interessantes, como gêneros populares ao longo do tempo e padrões específicos de classificação indicativa.

- **Students Performance**:
  - A análise revelou disparidades de desempenho entre diferentes grupos demográficos.
  - O modelo supervisionado mostrou boa capacidade preditiva para categorizar o desempenho dos estudantes.

---

## Como Executar
1. Clone este repositório:
   ```bash
   git clone <URL_DO_REPOSITÓRIO>
   ```
2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
3. Abra e execute os notebooks:
   - `notebook_netflix.ipynb`
   - `notebook_students_performance.ipynb`

---

## Contato
- **Autor**: [Seu Nome]  
- **GitHub**: [Seu GitHub](https://github.com/seuusuario)
