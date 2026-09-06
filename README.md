# We-can-fly

# Como fatores de gênero e raça influenciam a renda salarial media no Brasil e impactam nos recortes de grupos sub-representados.
TCC da Turma Fly 2026 - diversiData

`Python` `pandas` `scikit-learn` `[base usada]`

## O problema
Análise de como gênero e raça influenciam a renda salarial média no Brasil, evidenciando desigualdades e a sub-representação de grupos no mercado de trabalho.Investigamos como gênero e raça influenciam a renda salarial média no Brasil.
Analisamos as diferenças de remuneração entre grupos sociais.
O estudo é importante para evidenciar desigualdades e a sub-representação no mercado de trabalho

## Os dados
- Fonte: [[Rendimento médio mensal (R$) do trabalho principal segundo posição da ocupação com contribuição para a Previdência Social por sexo e raça/cor, Fonte:  (PNAD) e da Pesquisa Nacional por Amostra de Domicílios Contínua (PNAD Contínua) do IBGE, recorte, período 2022].]
- Recorte: [periodo, regiao, filtros aplicados]
- Amostra neste repositorio: [X linhas, so para o codigo rodar]
- Como reproduzir: [ver dados/FONTE.md]

## O metodo
[Quatro linhas: limpeza, variaveis, modelo escolhido e por que.]

## Os resultados
- **[numero principal]** - [o que ele quer dizer]
- [segundo achado]
- [terceiro achado]

## O prototipo
[[Link do GitHub Pages](https://anaglebia.github.io/We-can-fly/)] - 

Este simulador interativo expõe o viés salarial do mercado ao demonstrar visualmente como gênero e raça alteram drasticamente a renda prevista pela PNAD Contínua para perfis profissionais idênticos.

## Limitacoes
⚠️ 1. Limitações do Modelo Estatístico (Isolamento de Variáveis)Efeito "Ceteris Paribus" Artificial: Na realidade, gênero e raça moldam as oportunidades de vida desde a infância. Ao travar idade e escolaridade, o modelo assume que uma mulher negra e um homem branco chegam ao mercado com as mesmas trajetórias, o que ignora o racismo e o machismo estruturais prévios ao emprego.Variáveis Omitidas: A PNAD não captura dados cruciais que impactam a renda, como produtividade individual, soft skills, redes de contatos (networking) e o prestígio da instituição onde a pessoa estudou.

📊 2. Limitações da Base de Dados (PNAD Contínua)Informalidade e Subdeclaração: Trabalhadores informais ou autônomos tendem a flutuar ou subdeclarar seus rendimentos na pesquisa, reduzindo a precisão do modelo para esses grupos.Super-ricos Subrepresentados: A PNAD é uma pesquisa domiciliar por amostragem e costuma não capturar os rendimentos do topo da pirâmide financeira (o 1% mais rico), onde a disparidade de gênero e raça pode ser ainda mais extrema.Falta de Dados Setoriais Específicos: A pesquisa traz grandes recortes (ex: "Indústria", "Comércio"), mas não diferencia se a pessoa é desenvolvedora de software ou assistente de TI, o que distorce a previsão para profissões de nicho.

💡 3. Limitações de Interpretação (Viés vs. Discriminação)Correlação não é Causalidade: O modelo aponta que o gênero e a raça estão associados a uma renda menor, mas ele não consegue explicar o motivo exato (se é discriminação direta do chefe, penalidade pela maternidade, ou barreiras de entrada em setores que pagam mais).Segregação Ocupacional Oculta: O modelo pode sugerir um viés puro na canetada do salário, quando na verdade parte da diferença ocorre porque mulheres e pessoas negras são empurradas para profissões historicamente menos valorizadas e pior pagas.

## O grupo

Ana Bezerra - [LinkedIn](https://www.linkedin.com/in/ana-almeida-ti/)

Isadora de Oliveira Silva - [LinkedIn](https://www.linkedin.com/in/isadora-de-oliveira-silva-496954164)

Jaqueline Martins Duarte - [LinkedIn](https://www.linkedin.com/in/jaquilenemartins)

Bernardo Chiusoli - [LinkedIn](https://www.linkedin.com/in/bernardochiusoli)

Victoria Paixão - [LinkedIn](https://www.linkedin.com/in/bernardochiusoli)

Lorena - [LinkedIn](https://www.linkedin.com/in/lorena-g-a67978124)

Roberta - [LinkedIn](https://www.linkedin.com/in/roberta-bueno-de-souza-algarves-8226b8173)


## Como rodar
1. Abra `notebook/01_analise_completa.ipynb` no Google Colab
2. Rode as celulas de cima para baixo
3. As bibliotecas estao em `requisitos.txt`
