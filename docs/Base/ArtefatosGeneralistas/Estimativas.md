# ESTIMATIVAS DE CUSTO

## 1. Introdução

Este documento apresenta as **estimativas de esforço, tempo e custo** para o desenvolvimento do projeto, utilizando a técnica de **Avaliação de Especialista**.
Essa técnica consiste em reunir pessoas com experiência no domínio ou projeto (neste caso, dois membros da equipe), que discutem e atribuem valores de esforço para cada atividade. A estimativa final é obtida pela **média ou consenso** das opiniões.

---

## 2. Informações do Projeto

* **Nome do projeto:** Jogo Digital
* **Grupo:** 01
* **Professora:** Milene Serrano
* **Plataforma alvo:** Desktop

---

## 3. Premissas e Restrições

|  ID | Premissa/Restrição |      Impacto     | Observação |
| :-: | :----------------- | :--------------: | :--------- |
|  P1 | Desenvolvimento em Python          |Médio | Liguagem de programação principal definida   |
|  R1 | Tempo de entrega acadêmico          | Alto | Datas fixas de disciplina   |
|  R2 | Funcionalidades priorizadas           |Médio | Loja, inimigos e defesas simples na 1ª versão   |

---

## 4. Método de Estimativa

* **Técnica:** Avaliação de Especialista
* **Participantes:** Victor Pontual, Leticia Arisa
* **Critério de consenso:** Média aritmética

---

### **5. Lista de Atividades**

Com base no **Rich Picture**, as estimativas feitas pelos 2 especialistas depois são distribuídas entre os **10 membros**:
| ID | Atividade             | Descrição                                | Estimativa A (h) | Estimativa B (h) | Estimativa Final (h) | Alocação de Equipe |
| -- | --------------------- | ---------------------------------------- | ---------------- | ---------------- | -------------------- | ------------------ |
| 1  | Menu Inicial          | Implementar menu, configs, loja          |       5h         |       6h         |        5.5h          | 2 devs             |
| 2  | Configurações         | Acessibilidade, volume, prefs            |      10h         |      12h         |        11h           | 1 dev              |
| 3  | Loja                  | Comprar e vender recursos                |      25h         |      28h         |        26.5h         | 2 devs             |
| 4  | Modo de Jogo          | Dificuldade, mapa, fases                 |      30h         |      32h         |        31h           | 2 devs             |
| 5  | Rodadas               | Ciclo de início, defesa, vitória/derrota |      20h         |      18h         |        19h           | 3 devs             |
| 6  | Inimigos              | IA básica e ataques                      |      20h         |      22h         |        21h           | 2 devs             |
| 7  | Defesas               | Implementar personagens folclóricos      |      40h         |      38h         |        39h           | 3 devs             |
| 8  | Status do Jogador     | Vida, pontos, recursos                   |      10h         |      9h          |        9.5h          | 2 devs             |
| 9  | Pontuação/Ranking     | Contagem de pontos e vitórias            |       5h         |      6h          |        5.5h          | 1 dev              |
| 10 | Persistência de dados | Salvar/carregar progresso                |      20h         |      18h         |        19h           | 2 devs             |
| 11 | Testes                | Jogabilidade e feedback                  |      60h         |      62h         |        61h           | Equipe inteira     |


---

## 6. Estimativa de Esforço e Tempo

* **Unidade usada:** Horas
* **Esforço total estimado:** 258h
* **Tempo previsto (cronograma):** 4 semanas
* **Equipe:** 10 pessoas

---

## 7. Estimativa de Custo

Definir custo-hora da equipe e multiplicar pelo esforço. Foi considerado a média salarial de R$30,00/h para uma equipe de desenvolvedores provida pelo Glassdoor.

| Item                     | Valor    |
| ------------------------ | -------- |
| Custo por hora (R$)      | 30,00    |
| Esforço total (h)        | 258      |
| **Custo estimado (R$)**  | 7.740    |

---

## 8. Cronograma Macro
| Marco                 | Início   | Fim      | Responsável |
| --------------------- | -------- | -------- | ----------- |
| Protótipo             | 03/09 | 04/09 | todos    |
| Implementação inicial | 05/09 | 30/09 | equipe de desenvolvimento |
| Testes e ajustes      | 01/10 | 30/10 | equipe de testes |
| Entrega final         | 31/10 | 31/10 | todos |

---

## 9. Riscos e Contingências
| Risco                        | Probabilidade      | Impacto         | Mitigação                       |
| ---------------------------- | ------------------ | --------------- | -------------------------------- |
| Atraso na entrega            | Média              | Alto            | Revisão semanal do progresso     |
| Falta de experiência técnica | Baixa              | Médio           | Treinamento e apoio entre membros|
| Mudança de requisitos        | Média              | Médio           | Documentação clara e comunicação |
| Problemas de integração      | Baixa              | Alto            | Testes frequentes e integração contínua |

---

## 10. Resultados e Conclusões

Resumo das principais métricas:

* **Esforço total:** 258h
* **Tempo previsto:** 2 meses
* **Custo estimado:** R$ 7.740

Decisões tomadas:
- Utilização da técnica de Avaliação de Especialista para estimativas
- Definição de cronograma macro para garantir entrega em 2 meses
- Priorização de funcionalidades essenciais na primeira versão

---
## Histórico de revisão
|   Data   | Versão | Descrição            | Autor(es) |
| :------: | :----: | :------------------- | :-------- |
| 03/09 |   0.1  | Criação do documento base para preenchimento futuro | Victor Pontual  |
| 03/09 |   0.2  | Preenchimento da coluna A da tabela de Lista de Atividades | Leticia Arisa  |
| 03/09 |   0.3  | Preenchimento das estimativas finais e cálculo do esforço total | Leticia Arisa  |
| 03/09 |   0.4  | Atualização do custo estimado e cronograma macro | Victor Pontual, Leticia Arisa  |
| 03/09 |   1.0  | Preenchimento dos tópicos de riscos, conclusões e revisão final do documento | Victor Pontual  |
