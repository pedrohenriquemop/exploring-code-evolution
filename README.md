# Explorando evolução de código

Autor: Pedro Henrique Madeira de Oliveira Pereira

1. **Repositório selecionado:** [Storybook](https://github.com/storybookjs/storybook)

2. **Gráfico selecionado:** Lines of code (LOC)

3. **Explicação:**

   Houve uma queda abrupta do número de linhas de código de 2024 para 2025. De 2020 para 2024 havia uma tendência de crescimento, que foi abruptamente quebrada de 2024 para 2025, reduzindo mais de 95% das linhas. O crescimento de 2020 para 2024 pode ser explicado pelo crescimento natural do projeto. Para a queda observada de 2024 para 2025, haverá uma tentativa de explicação a seguir.

   Alguns fatores que podem ter contribuído para essa queda abrupta são: refatoração massiva, remoção de código legado, migração tecnológica e separação de projeto.

   - **Refatoração massiva:** pode ter havido uma refatoração grande em toda extensão do código para reduzir a quantidade de linhas total, mas acredito fortemente que esse não seja o único fator, mas há grandes chances de pelo menos ser um deles.

   - **Remoção de código legado:** a remoção de grandes trechos de código que se tornaram legado em versões de 2025 também pode ser uma explicação para a queda do número de linhas. Houve a remoção de suporte a certas ferramentas e frameworks considerados obsoletos, além da remoção de pacotes e addons descontinuados.

   - **Migração tecnológica:** semelhante ao ponto anterior, houveram atualizações de compatibilidade do Storybook e remoção do suporte a versões antigas do Svelte e do TypeScript, o que pode ter contribuído com uma boa parcela das linhas de código que foram reduzidas.

   - **Separação de projeto:** outro fator provável é a divisão do "monorepo" em repositórios menores, o que alivia a quantidade de código no repositório original.

   Por fim, apesar de ser menos provável, mas pode ser que o algoritmo de contagem de linhas tenha falhado em algum momento e atestado uma redução abrupta que na verdade não existiu entre 2024 e 2025, mas essa opção foi praticamente descartada das minhas hipóteses.

<details>
<summary>Enunciado original da atividade</summary>

# Explorando evolução de código

Neste exercício, iremos explorar a evolução de código em sistemas reais.

Iremos utilizar a ferramenta [GitEvo](https://github.com/andrehora/gitevo).
Essa ferramenta analisa a evolução de código em repositórios Git nas seguintes linguagens: Python, JavaScript, TypeScript e Java.

Você deve submeter via Moodle apenas o link do seu `fork`, conforme descrito abaixo.

# Passo 1: Selecionar repositório a ser analisado

Selecione um repositório relevante na linguagem de sua preferência (Python, JavaScript, TypeScript ou Java).
Você pode encontrar projetos interessantes nos links abaixo:

- Python: https://github.com/topics/python?l=python
- JavaScript: https://github.com/topics/javascript?l=javascript
- TypeScript: https://github.com/topics/typescript?l=typescript
- Java: https://github.com/topics/java?l=java

# Passo 2: Instalar e rodar a ferramenta GitEvo

Instale a ferramenta [GitEvo](https://github.com/andrehora/gitevo) com o comando:

```
pip install gitevo
```

Rode a ferramenta no repositório selecionado através do seguinte comando (dependendo da linguagem do projeto que escolheu):

```shell
# Python
$ gitevo -r python <git_url>

# JavaScript
$ gitevo -r js <git_url>

# TypeScript
$ gitevo -r ts <git_url>

# Java
$ gitevo -r java <git_url>
```

Onde `<git_url>` é URL do repositório a ser analisado.
Por exemplo, para analisar o projeto Flask escrito em Python:

```
$ gitevo -r python https://github.com/pallets/flask
```

# Passo 3: Explorar os gráficos de evolução de código (`index.html`)

Ao rodar a ferramenta [GitEvo](https://github.com/andrehora/gitevo), o arquivo `index.html` é gerado com diversos gráficos de evolução de código.

Abra o arquivo `index.html` e observe com atenção os gráficos gerados.

# Passo 4: Explicar um gráfico de evolução de código

Selecione um dos gráficos de evolução e explique-o com suas palavras.
Por exemplo, você pode:

- Detalhar a evolução ao longo do tempo,
- Detalhar se as curvas estão de acordo com boas práticas,
- Explicar grandes alterações nas curvas,
- Explorar a documentação do repositório em busca de explicações para grandes alterações
- Etc.

Seja criativo!

# Exercício

Para responder este exercício, primeiramente, você deve fazer um `fork` deste repositório.
No Moodle, você deve submeter apenas a URL do seu `fork`.

Em seguida, adicione o arquivo gerado `index.html` no seu fork.

Por fim, responda as questões abaixo no seu `fork`:

1. Repositório selecionado: <URL_DO_REPOSITORIO_SELECIONADO_AQUI>

2. Gráfico selecionado: <NOME_DO_GRAFICO_SELECIONADO_AQUI>

3. Explicação: <EXPLICACAO_AQUI>

</details>
