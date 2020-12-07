# Brazilian Township Politicians Elegibility Based on Ownership of Goods (2020)
Data Analysis using Python

## Goal
Rumors of vote buying in some regions of Brazil are fairly common among brazilians </br>
Brazilian's candidates to councilor and mayoral from three different states in three different regions of Brazil with diverse cultures where analysed.
This Data Analysis aims on making a parallel betwen how much property in goods a candidate has declared (in BRL) and it's elegibility

## Parameters
   - 3 diferente states from 3 diferent regions
   - The year of analysis is 2020 (lattest township elections)
   - Only using candidates that declare their goods
   - Alternate elects will not be counted
   
## Results
Starting with two graphs on witch we can see the number of elected by property from ten thousand (10^4) to one hundred million (10^8).
Note that the majority lies within the ten thousand and one hundred thousand, but at this range there is a drop of electeds at Bahia (BA) and Goiás (GO). .

<img src="/images/electeds.png" width=45% height=45%> <img src="/images/non-electeds.png" width=45% height=45%> 

Interesting... but we can still mess a little with it. For instance, let's check the Mean Instrucion Grade at each range.  

<img src="/images/instruction-electeds.png" width=45% height=45%> <img src="/images/instruction-non-electeds.png" width=45% height=45%> 

As expected, the higher the ownership the higher the instruction level. But at the greater numbers we see a great decline on the electeds at Bahia (BA). 🤔

## Conclusion
In some states, we get a higher election rate within the middle range (10^4 to 10^5) although at the other ones it stay pretty much the same. As expected, as the total value of the candidate's goods increaces, the mean of instruction grade also rises. The most interesting fact found by this analysis in my opnion is the great drop in instruction mean we see in the high end of ownership at Bahia (BA) by the elected candidadates.

## Data Source
### Tribunal Superior Eleitoral (TSE)
https://www.tse.jus.br/eleicoes/estatisticas/repositorio-de-dados-eleitorais-1 
   - Candidatos (formato ZIP)
      - consulta_cand_2020_BA.csv
      - consulta_cand_2020_GO.csv
      - consulta_cand_2020_SP.csv
   - Bens de candidatos (formato ZIP)
      - bem_candidato_2020_BA.csv
      - bem_candidato_2020_GO.csv
      - bem_candidato_2020_SP.csv
      
## References
https://github.com/pandas-dev/pandas/blob/master/doc/cheatsheet/Pandas_Cheat_Sheet.pdf </br>
https://github.com/fcostafelipe/Raspagem-de-dados-Ensino-Superior-2012-a-2018

#### by João Pedro Santos Pereira 
