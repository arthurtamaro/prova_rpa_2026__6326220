# Ficha de Avaliação de Processo (PDD) — Questão 5

> MOLDE. Copie para `entregas/lohan_6326234/` e preencha. Escolha **um** cenário (A ou B).

**Cenário escolhido:** <A>

1. **Nome do processo e descrição resumida:**
   <Processo: Renomeação e arquivamento diário de comprovantes em PDF.>

2. **Volume / frequência estimados:**
   <requência: Diária.
Volume estimado: Médio a alto, dependendo da quantidade de comprovantes recebidos durante o dia. O processo pode envolver dezenas ou centenas de arquivos diariamente.>

3. **As entradas são estruturadas?** (sim/não + justificativa)
   <Sim.
Os arquivos são PDFs e possuem nomes que seguem um padrão contendo informações como a data e o número do documento. Essas informações podem ser identificadas de forma padronizada pelo robô.>

4. **As regras são claras e determinísticas?** (sim/não + justificativa)
   <Sim.
As regras de nomenclatura e arquivamento são fixas. A partir da data e do número do documento presentes no nome do arquivo, o robô consegue determinar como o arquivo deve ser renomeado e onde deve ser armazenado.>

5. **Veredito — o processo é elegível a RPA?** (justifique com base em regras
   claras, dados estruturados e repetibilidade)
   <O processo é elegível a RPA.
O processo apresenta características adequadas para automação: possui regras claras e determinísticas, utiliza entradas estruturadas e é repetitivo, sendo executado diariamente. Dessa forma, um robô pode realizar a identificação, renomeação e arquivamento dos comprovantes seguindo as mesmas regras, reduzindo a necessidade de execução manual.>
