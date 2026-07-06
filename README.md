# Diversidade de Gênero na Computação: Impactos das Ações de Enfrentamento à Baixa Presença e Evasão das Mulheres na Graduação da Área

Repositório de Iniciação Científica desenvolvido no **Instituto de Computação da Universidade Federal Fluminense (IC-UFF)**, com o objetivo de registrar a trajetória e os materiais de pesquisa sobre a disparidade de gênero nos cursos de **Ciência da Computação (CC)** e **Sistemas de Informação (SI)**, e sobre os impactos das ações de enfrentamento à baixa presença e evasão feminina nessas graduações.

## Sobre a pesquisa

O estudo investiga a seguinte questão de pesquisa:

> *Quais os impactos das ações de enfrentamento à baixa presença e evasão feminina nas graduações presenciais do ICUFF nas estudantes?*

Para responder a essa pergunta, foi adotada uma **metodologia mista**, combinando:

- **Análise quantitativa**: dados de ingresso, cancelamento e conclusão de curso (2019–2024), obtidos junto ao Portal de Indicadores da Graduação (Prograd) e à Superintendência de Tecnologia da Informação (STI) da UFF.
- **Análise qualitativa**: grupo focal com 17 alunas de diferentes períodos dos cursos de CC e SI, com roteiro semiestruturado, conduzido via Google Meet e posteriormente transcrito e categorizado por temas.

A pesquisa tem como foco o projeto de extensão **Include Meninas UFF**, iniciativa do IC-UFF voltada à inserção e permanência de mulheres na Computação, atuante desde 2016 através de rodas de conversa, bolsas de estudo, workshops e acolhimento de calouras.

### Principais achados

- Entre 2019 e 2024, os homens ingressaram, em média, 5,8 vezes mais que as mulheres nos cursos de CC e SI.
- A taxa de evasão proporcional entre os gêneros é próxima (7,1% feminina vs. 6,9% masculina), mas essa aparente equivalência esconde assimetrias estruturais: **67,6% dos cancelamentos femininos ocorrem em CC**, com taxa acumulada de 10,1% — mais que o dobro da registrada em SI (4,4%).
- A quantidade de homens que se formam é, em média, 4,7 vezes maior que a de mulheres.
- Os relatos qualitativos apontam síndrome da impostora, dupla jornada (acadêmica e doméstica) e episódios de machismo sutil como barreiras adicionais não capturadas apenas pelos números.
- Ações de extensão como o Include Meninas têm impacto positivo na criação de redes de apoio e no senso de pertencimento das estudantes, mas os avanços em termos absolutos ainda são tímidos, reforçando a necessidade de políticas institucionais estruturais e contínuas.

## Estrutura do repositório

```
├── Análise Qualitativa/
│   └── Categorização das respostas/   # Categorização temática das falas do grupo focal
├── Gráficos/                          # Gráficos da análise quantitativa (ingresso, evasão e conclusão por gênero/curso)
├── Roteiro de Entrevistas/            # Roteiro semiestruturado utilizado no grupo focal
└── README.md
```

## 🔎 Metodologia

### 1. Coleta de dados quantitativos
Dados de ingresso, cancelamento e conclusão dos cursos de CC e SI (2019–2024) foram extraídos do painel público do Prograd:

🔗 [Painel Prograd — Analytics UFF](https://analytics.uff.br/superset/dashboard/prograd_ensino_graduacao/)

Esses dados foram complementados por informações da STI para estimar o perfil sociorracial das alunas, já que o Prograd não discrimina autodeclaração étnico-racial.

### 2. Tratamento e visualização
Os dados foram organizados e transformados em gráficos comparativos por gênero, curso e ano, disponíveis na pasta [`Gráficos/`](./Gráficos).

### 3. Grupo focal
Foi elaborado um roteiro semiestruturado (disponível em [`Roteiro de Entrevistas/`](./Roteiro%20de%20Entrevistas)) para guiar a discussão com as 17 participantes selecionadas via formulário online, respeitando os cuidados éticos descritos no Termo de Consentimento Livre e Esclarecido (TCLE).

### 4. Análise qualitativa
Os áudios das entrevistas foram transcritos e categorizados por tópicos (motivações de escolha do curso, dificuldades enfrentadas, senso de pertencimento, percepção sobre as ações de suporte), disponíveis em [`Análise Qualitativa/Categorização das respostas/`](./An%C3%A1lise%20Qualitativa/Categoriza%C3%A7%C3%A3o%20das%20respostas).

## Artigo

O artigo completo com a análise integrada (quantitativa + qualitativa) está disponível como PDF neste repositório / vinculado à submissão do evento.

## Financiamento

Pesquisa financiada pelo Conselho Nacional de Desenvolvimento Científico e Tecnológico (CNPq), pelo Ministério da Ciência, Tecnologia e Inovações (MCTI) e pelo Ministério da Mulher (MM), no âmbito do projeto RENACEE (processo nº 440502/2024-1).

## 👥 Autoria

- **Marianna Lima** — Instituto de Computação, UFF — `mariannalima@id.uff.br`
- **Luciana C. Salgado** (orientadora) — Instituto de Computação, UFF — `luciana@ic.uff.br`
