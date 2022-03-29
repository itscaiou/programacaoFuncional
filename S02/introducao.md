# Paradigmas de Programação

## Paradigmas:

* Imperativo:
    ```
    É um paradigma que descreve passo a passo do que está acontecendo.
    Utiliza recursos com if, while, for e etc.
    Um exemplo seria listar elementos com base em alguma condição sobre eles.
    ```

* Estruturado:
    ```
    Contém elementos de um código imperativo com blocos logicos.
    O código é mais 'limpo' e mais fácil de ser legível.
    Utiliza os mesmos reecursos if, while e for de forma semelhante ao Imperativo.
    ```

* Orientação a Objetos:
    ```
    Encapsula os dados em classes e contém os próprios estados e metodos que nã osão compartilhados.
    Os objetos não conseguem se comunicar com outro, e não usa, ou tenta evitar, as variáveis globais.
    Define as classes como públicas ou privadas e gerencia o acesso.
    ```
    
* Declarativo: 
    ```
    Possui um fluxo lógico implícito
    Possui também linguagens de alto nível permitindo aos programadores dizer apenas o que se deseja.
    Exemplo em SQL - Buscar alunos que possuem nota acima ou igual a 7:
    
    SELECT Nome
    FROM Alunos
    WHERE nota >= 7
    Order by Nome
    ```

* Lógico: 
    ```
    É especificado apenas fatos e regras de inferência.
    O retorno é feito em forma de pergunta.
    ```

* Funcional: 
    ```
    Baseado em cálculo Lambda
    Os programas são composições de funções
    Não se faz a utilização de estados.
    É um paradigma Declarativo.
    ```
