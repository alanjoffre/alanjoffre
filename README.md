# Alan Joffre

**Engenheiro de Dados** · [Noron.dev](https://noron.dev) · São Paulo, SP

Construo produtos de dados de ponta a ponta, do lakehouse (Databricks, Delta Lake e dbt) à IA aplicada com avaliação (RAG, fine-tuning e Text-to-SQL). Alocado em cliente de mobilidade e pagamentos, desenhei um lakehouse em Databricks e dbt que reduziu o tempo de apuração de até 20 para 2 dias. Hoje sou o responsável técnico pelo desenvolvimento e pela operação da Aira, produto de IA da Noron.dev.

Nos projetos abaixo, cada número vem de um teste ou de uma medição que roda no repositório. Os projetos abertos são feitos com apoio de assistente de IA; o escopo, as decisões de arquitetura e as medições são meus, e revisei o resultado.

## Projetos open source

- **[oss-lakehouse](https://github.com/alanjoffre/oss-lakehouse)** — lakehouse sobre dados reais do GitHub. 18 notebooks executados e mais de 180 testes, com CI. [Guia de estudo](https://github.com/alanjoffre/oss-lakehouse/blob/main/GUIA_DE_ESTUDO.md) com 199 perguntas respondidas.
- **[RodoIA](https://github.com/alanjoffre/rodoia)** — engenharia de IA de ponta a ponta, sobre dados públicos da ANTT. Fine-tuning com F1 de 0,13 para 0,77; avaliação como gate de CI (gate 30/30). [Demo ao vivo](https://huggingface.co/spaces/alanjoffre/rodoia-rag)
- **[Ledgerly Bank](https://github.com/alanjoffre/ledgerly-bank)** — banco digital fictício em Java, com Pix em Saga e Outbox. 1.141 testes e 96,7% de mutação no domínio.
- **[toll-analytics-platform](https://github.com/alanjoffre/toll-analytics-platform)** — plataforma de dados de ponta a ponta com dlt, dbt, Airflow, Soda e Terraform, construída do zero com dados sintéticos. [Dashboard ao vivo](https://alanjoffre.github.io/toll-analytics-platform/)
- **[RodoQuery](https://github.com/alanjoffre/rodoquery)** — Text-to-SQL sobre camada semântica: 100% contra 44,5% do SQL direto (n=146), em dados reais da ANTT.
- **[NãoConsta](https://github.com/alanjoffre/naoconsta)** — RAG contratual avaliado pelo que recusa responder: 510 contratos e 20.910 perguntas.

Todos os estudos de caso, com as decisões e os números, estão no **[portfólio](https://github.com/alanjoffre/portfolio)**.

## Em produção

**Aira**, produto de IA da Noron.dev, em produção na AWS desde maio/2026. Sou o responsável técnico pelo desenvolvimento e pela operação. Código fechado.

- **IA com permissão e fonte:** conduzi o desenho para que a IA consulte os arquivos da empresa só com ferramentas de leitura (recuperação agêntica), responda só com o que aquela pessoa tem permissão de ver e cite as fontes.
- **Avaliação e custo:** respostas avaliadas (mais de 30 casos em 7 categorias, dados fictícios, conferência determinística) antes de mudar prompt, modelo ou esforço; fila, limite por minuto, cota mensal e teto de gasto que bloqueia ou passa ao modelo mais econômico.
- **Operação:** Python/FastAPI e PostgreSQL em Docker na AWS; mais de 5.000 testes de back-end, trilha de auditoria encadeada por hash, backup diário cifrado (o deploy só segue com o backup externo confirmado) e mais de 60 versões publicadas.

## Stack

**Dados:** Python · SQL · Apache Spark (PySpark) · Databricks · Delta Lake · dbt · dlt · Airflow · Kafka · DuckDB · PostgreSQL · ETL/ELT<br>
**Qualidade e governança de dados:** testes dbt · Soda · OpenLineage · Unity Catalog<br>
**IA e MLOps:** LLMs (APIs de modelos de linguagem) · avaliação de LLMs (evals) · RAG · LangGraph · Qdrant · QLoRA · vLLM · PyTorch · Hugging Face · MLflow · DVC<br>
**Cloud e DevOps:** AWS · Azure · Docker · Terraform · GitHub Actions<br>
**Back-end e front-end:** FastAPI · Java (Spring Boot e Quarkus) · SvelteKit · TypeScript

## Contato

[LinkedIn](https://www.linkedin.com/in/alanjoffre) · [Página pessoal](https://alanjoffre.github.io/my-profile/) · [Currículo (PDF)](https://alanjoffre.github.io/my-profile/assets/curriculo_alanjoffre_ptbr.pdf) · [E-mail](mailto:alanjoffre01@gmail.com)
