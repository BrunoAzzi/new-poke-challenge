# Desafio de front-end

Olá amigo(a)! Estamos muito animados em convidá-lo para o nosso processo de seleção de novos candidatos front-end.

A ideia por trás desse desafio de codificação (ou tarefa para levar para casa) é entender melhor como você trabalha em tarefas específicas de front-end, seu processo de pensamento e como você projeta seu código.

O desafio é simples e deve levar um desenvolvedor experiente de 6 a 8 horas de trabalho.

Você terá uma semana inteira para terminar isso e entregá-lo à nossa equipe. Se você precisar de uma extensão, informe-nos com antecedência para que possamos avaliar seu teste o mais rápido possível.

### Tópicos de avaliação

Para tornar esse teste super transparente, avaliaremos os seguintes tópicos em seu código assim que você o entregar, em nenhuma ordem específica:
- Completude do desafio
- Compreensão da proposta do desafio
- Escrita idiomática
- Cobertura de teste
- Boas práticas de uso
- Arquitetura geral para a solução
- Facilidade de execução
- Automação
- Documentação
- Uso de padrões de estilo modernos

Este teste é uma janela para o seu trabalho, então não se apresse, use o tempo para criar algo com qualidade que mostre sua compreensão do ecossistema de front-end, ferramentas e práticas recomendadas.

### Restrições

Existem algumas restrições em suas escolhas para desenvolver este teste. Você deve criar esta solução usando qualquer um dos seguintes:

- React
- Preact
- Qualquer framework compatível com React (Next, Gatsby, entre outros)

O uso do Typescript é altamente recomendado.

Lembre-se, enquanto estivermos dando algumas restrições, pediremos que você justifique suas escolhas e por que elas são boas escolhas.

- Você não pode usar bibliotecas de wrapper PokeAPI.
- Você pode usar qualquer pré-processador CSS, como Sass ou Less.
- Você pode usar qualquer framework CSS que julgar apropriado, como Tailwind, mas não pode usar bibliotecas de componentes, como MDI ou bootstrap.

## Desafio

Então, somos grandes fãs de Pokémon, e os amamos, e queremos pegá-los todos. Queremos que você projete e implemente um Pokedex do zero, usando APIs disponíveis gratuitamente (https://pokeapi.co/).

### Lista de Pokémon

Crie um projeto que possa se conectar ao PokeAPI e nos mostre uma lista de Pokémon. Existem vários Pokémon na PokeAPI, portanto, certifique-se de que o site possa lidar com todos os Pokémon e exibi-los organizados.

Não há design de interface do usuário sugerido para este projeto, então você pode ser tão criativo quanto quiser.

Você deve exibir cada Pokémon em um cartão, juntamente com informações importantes sobre cada um:

- Uma pequena imagem/ícone
- Número Dex Nacional (por exemplo: #001)
- Nome (por exemplo: Bulbasaur)
- Tipos (por exemplo: Grama, Veneno)

Seu projeto deve suportar a ordenação de pokemons por nome, tipo ou número dex. Quando você clica em um pokemon, ele deve mostrar sua página de detalhes.
Aqui estão algumas referências que você pode dar uma olhada em sites famosos relacionados a pokémon:

- Bulbapédia
- Marilândia

### Detalhe Pokémon

Crie uma página que mostre os detalhes do pokemon com as seguintes informações:

- Número Dex
- Nome
- Tipos
- Estatísticas
- As estatísticas básicas podem chegar a um máximo de 255, use isso a seu favor enquanto cria uma interface de usuário legal!
- Exibição de imagem
- Deve ter uma maneira de alternar entre sprites normais e brilhantes
- Os movimentos do Pokémon.
- Classe de dano (físico, especial)
- Poder
- Precisão
- Tipo (grama, água, etc.)
- Descrição

## Crédito extra

Se você tiver tempo e quiser adicionar mais recursos, aqui estão algumas ideias:

- Mostrar mais informações disponíveis na API
- Mostrar a linha evolutiva das espécies do pokemon
- Implante seu projeto em algum lugar com algum CI/CD