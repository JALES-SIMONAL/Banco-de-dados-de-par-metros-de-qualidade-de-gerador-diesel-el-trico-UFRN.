# Banco-de-dados-de-parâmetros-de-qualidade-de-gerador-diesel-elétrico-UFRN.

<div align="justify">

Este repositório disponibiliza o conjunto de dados (*dataset*) contendo 29 parâmetros de qualidade de um grupo gerador diesel-elétrico da UFRN, conforme apresentado no artigo **"Desenvolvimento de hardware e dashboard supervisório para o monitoramento remoto de grupos geradores em operações críticas"**.

O banco de dados foi estruturado utilizando uma lógica de armazenamento por evento: um novo registro só é inserido quando ocorre mudança no valor do parâmetro. Dessa forma, intervalos sem registros novos devem ser interpretados como a manutenção do último valor coletado. Cabe ressaltar que alguns parâmetros podem apresentar registros consecutivos com valores visualmente idênticos; tal comportamento deve-se à flutuação de precisão numérica (*floating point memory*), onde variações ínfimas na casa decimal são interpretadas pelo sistema como uma alteração do dado. Abaixo, segue a tabela com os parâmetros contidos no banco de dados.

</div>

<p align="center">
  <img width="388" src="https://github.com/user-attachments/assets/5a58b50b-c3e0-48ae-8baf-0fae55ae6474" alt="Tabela de Parâmetros" />
</p>

---

<div align="justify">

Este trabalho foi desenvolvido no **LANCE (Leading Advanced Technologies Center of Excellence)**. O presente trabalho foi realizado com apoio da Coordenação de Aperfeiçoamento de Pessoal de Nível Superior - Brasil (CAPES) - Código de Financiamento 001.

</div>
