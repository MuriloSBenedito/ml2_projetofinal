
# Projeto de Conclusão de Módulo: Análise de Dados e Modelos de Machine Learning

## Autor
**Nome**: Murilo da Silva benedito  
**GitHub**: https://github.com/MuriloSBenedito

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

![image](https://github.com/user-attachments/assets/fa955b93-d0c6-4772-bb22-8a153f96198a)
![image](https://github.com/user-attachments/assets/42b6d751-74cf-4f26-9f6f-81a103607960)
![image](https://github.com/user-attachments/assets/d2ad3eb1-7804-46f3-8525-c814ad7d0015)



2. **Modelo Desenvolvido**:
   - **Modelo Não Supervisionado**:
     - **Algoritmo**: KMeans.
     - **Objetivo**: Identificar padrões entre os títulos com base em gêneros e anos.
     - **Clusters**: `N` clusters identificados com características como `[descreva os clusters]`.
     - 
![image](https://github.com/user-attachments/assets/37363c1f-6b30-43bb-8d92-a95e1b71efd0)
![image](https://github.com/user-attachments/assets/b6105654-3d6a-409d-900b-83ec0b8e9e5d)
![image](https://github.com/user-attachments/assets/17d2d791-e8c8-4bb9-8336-3d39fbe68c95)




---

## Dataset 2: Students Performance
**Descrição**: Contém informações sobre o desempenho de estudantes em matemática, leitura e escrita, além de dados como gênero, etnia e tipo de preparo para testes.

### O que foi feito:
1. **Análise de Dados**:
   - Distribuição por gênero e etnia.
![image](https://github.com/user-attachments/assets/cf7cb5bf-14f9-4b76-87ce-d7cce51a9910)

   - Correlações entre diferentes áreas de desempenho.
![image](https://github.com/user-attachments/assets/b5312c6e-9ca3-403d-8145-b29f55ef4cc5)
![image](https://github.com/user-attachments/assets/c68e0063-d270-4325-b109-f83ebdda9475)



2. **Modelo Desenvolvido**:
   - **Modelo Supervisionado**:
     - **Target**: Classificar os estudantes em categorias de desempenho (`alto`, `médio`, `baixo`).
     - **Algoritmo**: Random Forest.
     - **Resultados**: Acurácia de `YY%`.
![image](https://github.com/user-attachments/assets/25cdb75b-5544-4392-92ef-7773c910b16e)

---

## Conclusões
- **Netflix Titles**:
  - Os clusters revelaram tendências interessantes, como gêneros populares ao longo do tempo e padrões específicos de classificação indicativa.

- **Students Performance**:
  - A análise revelou disparidades de desempenho entre diferentes grupos demográficos.
  - O modelo supervisionado mostrou boa capacidade preditiva para categorizar o desempenho dos estudantes.

---

