# Music-Connect-Nordeste-recomenda-es-de-musica-



## Music Connect Nordeste

### Sistema de Recomendação de Músicas usando Grafos (Neo4j)

### Este projeto foi desenvolvido como um desafio para criar um sistema de recomendação de músicas utilizando o banco de dados de grafos Neo4j.
### O objetivo é mostrar como usuários, músicas, artistas e gêneros podem ser conectados para gerar recomendações inteligentes.

## Objetivos do Sistema
### O sistema deve ser capaz de:
###    • Representar usuários, músicas, artistas e gêneros como nós no grafo.
###    • Representar interações como arestas com propriedades, como:  
###         OUVIU, CURTIU, SEGUIU, COMENTOU
 ###   • Utilizar consultas Cypher para gerar recomendações personalizadas.

## Estrutura do Projeto
### O projeto contém 3 scripts:
### 1. nodes.cypher — Criação de nós
### Aqui ficam as criações dos usuários, artistas, músicas e gêneros.
 ### 2. relationships.cypher — Criação de relacionamentos
### Aqui ficam as relações: escutar, curtir, seguir, comentar etc.
### 3. queries.cypher — Consultas Cypher
### Consultas para encontrar recomendações.


## Usuários criados
### Foram criados 10 usuários fictícios: 
### Ana, Bruno, Carlos, Daniela, Eduardo, Fernanda, Gustavo, Helena, Igor, Julia


## Artistas criados Nordeste
  ###    Luiz Gonzaga – Elba Ramalho – Dominguinhos – Fagner - Alceu Valença -  Noda de Caju  -  Calcinha Preta - Wesley Safadão – Bell Marques – Mastruz com Leite.

## Músicas (10 músicas do Nordeste)
##3    1. Asa Branca – Luiz Gonzaga
 ###   2. Xote das Meninas – Luiz Gonzaga
  ###  3. Diga Sim pra Mim – Noda de Caju
   ### 4. De Volta pro Aconchego – Elba Ramalho
  ### 5. Anunciação – Alceu Valença
  ### 6. Borbulhas de Amor – Fagner
   ### 7. Você não Vale Nada – Calcinha Preta
  ###  8. Meu Vaqueiro, Meu Peão – Mastruz com Leite
 ###   9. Camarote – Wesley Safadão
 ###   10.   Selva Branca  - Bell Marques
       
## Gêneros musicais
 ###     Forró, Xote, Baião, Arrocha, Piseiro, Frevo, Forró Eletrônico, Forró Tradicional, Axé, Sertanejo Nordestino.

## Interações Criadas
###   • CURTIU (deu like)
 ###   • SEGUIU (seguiu artista)
  ###  • COMENTOU (comentário em música)
### Exemplo de comentários criados:
  ###  • Perfeito
   ### • Amo o Ritmo
### • Romântica demais
   ### • TOP
## Consultas (Queries) Implementadas
### Recomendar músicas que o usuário ainda não ouviu
### Baseado no gênero que ele mais escuta.
### Recomendar artistas seguidos por amigos
### Identificar conexões.
###  Recomendar músicas parecidas com as que ele curtiu
### Usando similaridade por gênero ou artista.

<img width="842" height="498" alt="visualisation(1)" src="https://github.com/user-attachments/assets/e1b27588-8197-4d11-aa5c-bb64e1e74f46" />





