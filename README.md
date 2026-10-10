# Internações no SUS, 2008–2025 — análise descritiva (versão preliminar)

Página interativa com a análise descritiva exploratória das internações hospitalares do SUS (SIH/SUS, arquivos RD),
Brasil e cada UF de residência, 2008–2025: volume e taxas, série mensal e COVID-19, a queda de 2020 (eletivas e
urgências), idade e sexo, causas (CID-10), óbito, permanência e UTI, caráter e complexidade, valores pagos, comparação
entre UFs e qualidade do dado. É uma página única (`index.html`): os dados agregados estão embutidos nela e o filtro
por UF funciona no navegador, sem servidor.

## Aviso

Projeto pessoal de análise, em **versão preliminar e de teste**. Não é um produto oficial e não representa a posição
da Secretaria da Saúde do Ceará, do Ministério da Saúde ou de qualquer outra instituição a que o autor esteja vinculado.

**Pode conter erros.** A concepção, as perguntas e a revisão são de cgarciafilho; a extração, o código, os gráficos e
os textos foram feitos com inteligência artificial. Os totais da página foram conferidos com o TabNet do DATASUS
(internações, AIH, óbitos, valor, dias de permanência, caráter, capítulo da CID-10, faixa etária, sexo, raça/cor e
mês de atendimento). Confira os números no TabNet antes de citar ou de decidir algo com base neles. As definições e
limitações estão na seção "Método e limitações" da página.

## Fontes

- SIH/SUS: arquivos RD (AIH reduzida) do FTP do DATASUS, 2008–2025, baixados em 09–10/10/2026. Não há identificação de pessoas.
- População: POPSVS (Ministério da Saúde), estimativas por município, sexo e idade, 2000–2025.
- IPCA: IBGE (SIDRA, tabela 1737), para os valores em reais de 2025.
- Nomes da CID-10: tabela do DATASUS (versão 2008). Nomes dos subgrupos de procedimento: SIGTAP, conforme o TabNet.

## Contato

Erros, dúvidas e sugestões: cgarciafilho@gmail.com

## Sobre este repositório

Aqui fica só a página publicada. Os scripts que baixam os dados, calculam os agregados e conferem a página com o
TabNet ficam no projeto de origem, que não está publicado.

## Licença

MIT (arquivo `LICENSE`), para a página e o código. Os dados de origem (DATASUS, Ministério da Saúde, IBGE) são
públicos e seguem os termos de cada fonte.
