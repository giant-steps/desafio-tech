# Desafio Giant Steps
## Nosso desafio técnico

Agora que você já chegou até aqui, temos um desafio técnico para você mostrar que está bem afiado com tecnologia!
Gostariamos que você criasse um programa que analisasse o retorno de de um dos nosso fundos, o Zarathustra, utilizando alguns conceitos de matemática financeira.

PS: Não publique a sua resposta publicamente! Mande um invite de seu repositório privado para [@rafalee](https://github.com/rafalee) e [@vmesel](https://github.com/vmesel)

### Nosso fundo: Giant Zarathustra Fundo de Investimentos Multimercado

Nosso fundo principal, o Giant Zarathustra, é um fundo de investimentos multimercado que conta 
com algumas de nossas estratégias quantitativas.

Dada a série histórica do fundo e do CDI disponível nos arquivos `cotas_cdi_dados.xlsx`, `zarathustra.csv` e `cdi.csv`, crie um programa que:

 1. Dado um range de datas, calcule a **rentabilidade do período em porcentagem**
 2. Dado um range de datas, calcule a **rentabilidade relativa ao CDI em porcentagem**
 3. Dado um range de datas, calcule a **evolução do patrimônio do fundo em Reais (BRL)**
 4. Dado um range de datas, retorne a **data e o valor de maior retorno diário em porcentagem**
 5. Dado um range de datas, retorne a **data e o valor de menor retorno diário em porcentagem**
 6. Dado um range de datas, retorne uma **série de retorno acumulado do fundo**

### O que gostariamos de ver:

- Python 3 >
- Testes bem escritos e com uma boa cobertura
- Organização e instruções de como executar o projeto (se entregar em docker melhor ainda!)


### Exemplo

#### Inputs

 **start_date** 2019-01-02
 
 **end_date** 2019-01-31

#### Outputs
1. **Rentabilidade do período em porcentagem**: 2,5406 %
2. **Rentabilidade relativa ao CDI em porcentagem**: 467,8768 %
3. **Evolução do patrimônio do fundo em Reais (BRL)**: R$ 52.828.272,10
4. **Data e o valor de maior retorno diário em porcentagem**: 2019-01-02, 1,3983 %
5. **Data e o valor de menor retorno diário em porcentagem**: 2019-01-07, -0,9556 %
6. **Série de retorno acumulado do fundo**:

 Data   | Retorno Acumulado
 ------ |   ---------------
 2019-01-02  | 1.3983%
 2019-01-03  |	1.5597%
 2019-01-04  |	1.3118%
 2019-01-07  |	0.3436%
 2019-01-08  |	0.4664%
 2019-01-09  |	0.7862%
 2019-01-10  |	0.4035%
 2019-01-11  |	0.3816%
 2019-01-14  |	0.8947%
 2019-01-15  |	0.4789%
 2019-01-16  |	0.4023%
 2019-01-17  |	0.7056%
 2019-01-18  |	0.5959%
 2019-01-21  |	0.5130%
 2019-01-22  |	0.5043%
 2019-01-23  |	1.0036%
 2019-01-24  |	1.2778%
 2019-01-25  |	1.2283%
 2019-01-28  |	0.8988%
 2019-01-29  |	1.3156%
 2019-01-30  |	1.3889%
 2019-01-31  |	2.5406%
