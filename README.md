# Sistema de Recomendação 
Sistema de recomendações produzido na matéria de "Teoria dos Grafos" ministrada pelo professor Adolfo Pinto  

Grupo
- Johnny William
- Paulo Vitor
## Finalidade do Projeto
Passado um usuário dentro do escopo utilizado (612) com prefixo "User" o sistema faz a leitura do usuário (vértice) e pega todos seus Adjacentes(vértices) que seria outros usuários que também já assistiram e deram como nota 5 (arestas), com isso é feito uma análise do vértice principal e seus adjacentes retirando todos os filmes que o mesmo ja avaliou com nota 5, após isso é feito uma ordenação dos dados e retirado 10 filmes que foram avaliados entre todos esses usuários em comum.  

### Exemplificação
- Vértices > Usuários 
- Arestas > Filmes avaliados com nota 5 em comum 


## Como rodar o sistema
- Se estiver pelo Colab executar toda as células que estão presentes dentro da célula abaixo: 
![main](https://github.com/vitorcosta26/Teoria_dos_Grafos-Trabalho-Pratico_2/blob/main/to_readme/sistema.png)  
- Se não for o caso, executar todos as células manualmente até a célula Executar  
![executar](https://github.com/vitorcosta26/Teoria_dos_Grafos-Trabalho-Pratico_2/blob/main/to_readme/executar2.png)  

- Quando estiver nesta parte do código:  
![sistema](https://github.com/vitorcosta26/Teoria_dos_Grafos-Trabalho-Pratico_2/blob/main/to_readme/executar.png)  
- Se todos os passos tiverem sidos feitos corretamente, irá pedir no console o nome do usuário desejado a recomendar, nossa database é constituída de 612 usuários todos com a formatação "User"+(número do usuário(1-612)) 
### Exemplo:  
- User312
- User125
- User18

### Resultado: 
![exemplo](https://github.com/vitorcosta26/Teoria_dos_Grafos-Trabalho-Pratico_2/blob/main/to_readme/exemplo.png)  
- Após a digitação do usuário desejado, nosso sistema irá fazer as devidas análises e retornar para Usuário 10 filmes que mais foram vistos por outros usuários em comum.

### Até a proxima!
![seeya](https://github.com/vitorcosta26/Teoria_dos_Grafos-Trabalho-Pratico_2/blob/main/to_readme/seeya.gif)  

