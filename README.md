# Projeto Semente

Protótipo de um jogo 2D top-down para PC, criado para aprender desenvolvimento de jogos e validar um loop simples de exploração, coleta e construção.

## Objetivo

Descobrir se é divertido explorar um pequeno mundo, coletar recursos, fabricar ferramentas e expandir uma primeira base.

## Loop principal

```text
Explorar → Coletar recursos → Retornar à base → Fabricar → Construir → Explorar novamente
```

## Tecnologia

- Engine: Godot 4.7.1
- Linguagem: C# / .NET
- Plataforma inicial: PC
- Estilo: 2D top-down
- Arte: placeholders e assets simples

## Protótipo

O primeiro protótipo será pequeno e focado no loop principal. Ele deverá conter:

- personagem com movimento e colisão;
- mapa pequeno;
- árvores, pedras e outros recursos;
- coleta de recursos;
- inventário simples;
- uma ferramenta;
- uma receita de craft;
- uma estrutura simples que possa ser construída.

Não haverá fome, sede ou temperatura nesta fase. Também ficam fora do primeiro protótipo multiplayer, chefes, magia, classes, NPCs, história, missões, agricultura, pesca, montarias, clima, estações, dungeons e sistema avançado de habilidades.

## Estado atual

- Projeto Godot criado.
- Cena principal criada.
- Jogador criado com `CharacterBody2D`.
- Movimento com as setas do teclado funcionando.
- Colisão do jogador configurada.
- Primeiro obstáculo estático criado.

## Próximos passos

1. Transformar uma pedra em recurso coletável.
2. Criar contador simples de recursos.
3. Criar uma árvore reutilizando a mesma lógica.
4. Adicionar inventário mínimo.
5. Criar ferramenta, receita e primeira construção.

## Regra do projeto

O objetivo é terminar um protótipo, não criar o jogo completo. Novas ideias ficam registradas no Estacionamento de Ideias e não entram no desenvolvimento antes da conclusão do escopo atual.
