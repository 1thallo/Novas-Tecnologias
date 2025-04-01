# Lista 3 - Coleções em Python  

Este repositório contém a resolução dos exercícios da Lista 3, que aborda o uso de coleções em Python. O objetivo é resolver os problemas de forma clara e utilizando práticas consideradas "pythônicas".  

## Exercícios  

1. **Dicionário de Tamanhos**  
    Dada uma lista de palavras, construa um dicionário que mapeia cada palavra ao número de caracteres que ela possui.  

2. **Agrupamento de Anagramas**  
    Dada uma lista de palavras, agrupe-as em um dicionário onde a chave seja uma forma canônica (por exemplo, os caracteres ordenados) e o valor seja a lista de palavras que são anagramas entre si.  
    - **Exemplo**:  
      Entrada: `["amor", "roma", "mora", "carro", "orça", "orca", "arco"]`  
      Saída:  
      ```python  
      {('a', 'm', 'o', 'r'): ['amor', 'roma', 'mora'],  
        ('c', 'o', 'r', 'r'): ['carro'],  
        ('a', 'c', 'o', 'r'): ['orça', 'orca', 'arco']}  
      ```  

3. **Mesclagem de Intervalos**  
    Dada uma lista de intervalos representados por tuplas `(início, fim)`, escreva um programa que mescle os intervalos que se sobrepõem.  
    - **Exemplo**:  
      Entrada: `[(1, 4), (2, 5), (7, 9)]`  
      Saída: `[(1, 5), (7, 9)]`  

4. **Filtragem por Frequência**  
    Dada uma lista de números, conte a frequência de cada número e exiba apenas os números que aparecem um número mínimo de vezes (por exemplo, pelo menos 3 vezes).  

5. **Multiplicação de Polinômios**  
    Represente polinômios como dicionários, onde as chaves são os expoentes e os valores são os coeficientes. Crie uma função que multiplique dois polinômios e retorne o polinômio resultante.  
    - **Exemplo**:  
      Polinômios: `3x² + 2x + 1` e `2x + 1`  
      Representação: `{2: 3, 1: 2, 0: 1}` e `{1: 2, 0: 1}`  

6. **Subconjunto com Soma Alvo**  
    Dada uma lista de números inteiros e um valor alvo, determine se existe um subconjunto cuja soma seja exatamente igual ao valor alvo.  

7. **Jogo da Forca**  
    Implemente um jogo da Forca utilizando listas. Dada uma palavra, forneça algumas chances para o usuário acertar.  

8. **Validação de Parênteses**  
    Escreva um programa que leia uma expressão com parênteses e, utilizando pilhas, verifique se os parênteses foram abertos e fechados na ordem correta.  
    - **Exemplo**:  
      Entrada: `(())` → OK  
      Entrada: `()()(()())` → OK  
      Entrada: `())` → Erro  

9. **Operações com Conjuntos**  
    Escreva um programa que compare duas listas e imprima:  
    - Os valores comuns às duas listas.  
    - Os valores exclusivos da primeira lista.  
    - Os valores exclusivos da segunda lista.  
    - Uma lista com os elementos não repetidos das duas listas.  
    - A primeira lista sem os elementos repetidos na segunda.  

10. **Cadastro de Pessoas**  
     Crie um programa que solicite ao usuário os dados de uma pessoa e armazene essas informações em um dicionário com as seguintes chaves:  
     - `first_name`: Primeiro nome  
     - `last_name`: Sobrenome  
     - `age`: Idade  
     - `city`: Cidade onde a pessoa vive  
     O programa deve exibir todas as informações armazenadas. Além disso, utilizando listas, armazene dados de várias pessoas e exiba todas as informações.  

---  