# Teste-Analytics-Housi
 
Análise de Dados referente aos exames de COVID de pacientes do Hospital Israelita Albert Einstein/SP.

[Teste_Housi.pdf](https://github.com/barbaramani/Teste-Analytics-Housi/files/12966650/Teste_Housi.pdf)

Alguns pontos que pude observar nessa análise: 

*  	Tamanho da tabela:<br>
  Quantidade de linhas: 5644 <br>
  Quantidade de colunas: 111

*   Os tipos de dados encontrados são do tipo int, object e float.
  
*  	Algumas colunas não possuem nenhum registro e, portanto, foram eliminadas.
As colunas eliminadas são: 

'Mycoplasma pneumoniae','Fio2 (venous blood gas analysis)','Urine - Nitrite','Prothrombin time (PT), Activity','D-Dimer'

Com isso o tamanho da tabela ficou: 

Quantidade de linhas: 5644
Quantidade de colunas: 106

* Percebi que aproximadamente 10% dos pacientes testaram positivo para o teste de COVID, enquanto 90% obtiveram resultado negativo.
  
*  	Dos pacientes que testaram positivo para COVID:
    
    36 ficaram internados em enfermaria regular <br>
    8 ficaram internados em em semi-intensiva <br>
    8 ficaram internado em UTI 
  	
  
*   Análise para pacientes que tiveram resultado reagente e não reagente para Influeza do tipo A e B<br>
    Reagente para Influenza A: 18<br>
    Não reagente para Influenza A: 1336<br>
    Reagente para Influenza B: 77<br>
    Não reagente para Influenza B: 1277

* Dos pacientes que positivaram para COVID, existe apenas 3 casos de pacientes que detectaram Influenza do tipo B. Para pacientes que detectaram Influenza A, não houve registro de paciente com COVID.

*  	Casos de internação de pacientes com algum tipo de Influenza:<br>
    Quantidade de paciente com resultado positivo na Enfermaria: 2<br>
    Quantidade de paciente com resultado positivo na Semi-intensivo: 2<br>
    Quantidade de paciente com resultado positivo na UTI: 1

*  Dos pacientes que fizeram teste rápido, somente 15 casos detectaram algum tipo de Influenza. Para esses casos, não houve nenhum registro de COVID.

*  Dos pacientes que tiveram teste rápido negativada, 20 detectaram algum tipo de Influenza. Para esses casos, não houve nenhum registro de COVID.






