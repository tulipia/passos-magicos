# Trabalho Datathon- Fase 5

O objetivo do trabalho é: 

- O grande objetivo do Datathon é você como um cientista de dados criar uma proposta preditiva ou como um(a) analista de dados realizar uma proposta analítica para demonstrar o impacto que a ONG “Passos Mágicos” tem realizado sobre a comunidade que atende. A associação busca instrumentalizar o uso da educação como ferramenta para a mudança das condições de vida das crianças e jovens em vulnerabilidade social. Com base no dataset de pesquisa extensiva do desenvolvimento educacional no período de 2020, 2021 e 2023, você pode entregar uma das seguintes propostas:

        1 - Proposta analítica: A ideia é demonstrar os impactos que a ONG “Passos Mágicos” realizou sobre a performance de estudantes e levantar indicadores de performance. Sendo assim, deve-se criar um dashboard e storytelling contando uma história com os dados para auxiliar a Passos Mágicos a tomar as melhores decisões com base nos indicadores e conhecer o perfil dos estudantes.
        
        2 - Proposta preditiva: Criar um modelo preditivo para prever o comportamento do estudante com base em algumas variáveis que podem ser cruciais para a identificação do desenvolvimento do estudante. Na proposta preditiva, você pode utilizar a criatividade para propor uma solução de algoritmo supervisionado ou não supervisionado. A ideia é utilizar um dos conhecimentos aprendidos no curso como solução (machine learning, deep learning ou processamento de linguagem natural).

Base de dados:

- A base de dados contém informações educacionais e socioeconômicas dos estudantes da Passos Mágicos. Vão ser disponibilizadas duas bases de dados com as características de desenvolvimento educacional e questões socioeconômicas dos estudantes e um dicionário de dados com o mapeamento de todas as variáveis. Além da base de dados, alguns relatórios de pesquisa realizada pela Passos Mágicos também serão disponibilizados para auxiliar no conhecimento do negócio.

Entrega:
- É importante ressaltar que o grupo pode optar em entregar apenas uma proposta ou também as duas.
- Caso você opte pela proposta analítica, a entrega deve ser um dashboard e um relatório contendo a análise dos dados. Caso você opte pela proposta preditiva, a entrega é um modelo preditivo com o deploy realizado no Streamlit.
- Você pode subir seu projeto no repositório do seu github e compartilhar o link do projeto na plataforma com os arquivos utilizados e o link do seu dashboard ou modelo preditivo.

Link dos dados:

    https://drive.google.com/drive/folders/1Xm_z9aiySMUrLuFfmIkIQP3mWcGVw-L3

# Primeira Etapa

Iniciando o projeto começamos com a exploração dos diversos dados que temos com o python.

1 - Realizamos a exploração da base <b>"PEDE_PASSOS_DATASET_FIAP.csv"</b> através do arquivo: <b>"extracao_dados.ipynb"</b>. Dentro deste arquivo separa a base em 3 datasets, sendo eles:

- dados_2020.csv
- dados_2021.csv
- dados_2022.csv

Cada um destes dados separado dentro da pasta <b>"bases_finais/"</b>

2 - Analisamos algumas das bases do banco de dados no arquivo <b>"index_v2.ipynb"</b>. As explorações se iniciaram com a tbAluno. Seguem alguns pontos gerais que exploramos inicialmente:

- Há 2238 alunos distintos na base.

- Verificamos a distruibuição das etinias de cada um dos alunos.

- Verificamos a idade de cada um dos alunos atualmente.

- Verificamos questões de deficiências dos alunos.

- Verificamos os responsáveis cadastrados de cada um dos alunos.

Ao final dessas verfificações montamos algumas visões para facilitar a análise e o entendimento. 

A primeira visão criada foi em relação a idade e o sexo de cada um dos alunos:

![alt text](imagens/grafico_distribuição_idade_sexo.png)

Podemos observar que uma <b>concentração nas idades de 10 a 11 anos</b> e uma <b>predominancia do sexo feminino</b>.

Em seguida, analisamos os alunos por suas etnias.

![alt text](imagens/grafico_distribuicao_idade_etnia.png)

Aqui podemos observar uma <b>concentração das classificações "B" e "R".</b>

Para um entendimento melhor, decidimos olhar as visões para cada um dos sexos dos alunos.

- Masculino:
