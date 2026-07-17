[[Sistemas/Legends 4/Cenas/Tipos/Combate/Iniciativa/Iniciativa|<- Iniciativa]]

### Descrição
Neste tipo, as [[Criatura|Criaturas]] envolvidas na cena de [[Sistemas/Legends 4/Cenas/Tipos/Combate/Combate|Combate]] são separadas em times. Cada time possui sua própria posição na ordem de [[Sistemas/Legends 4/Cenas/Tipos/Combate/Iniciativa/Iniciativa]].

### Quando Usar
Este tipo de [[Sistemas/Legends 4/Cenas/Tipos/Combate/Iniciativa/Iniciativa]] pode ser utilizado em cenas de [[Sistemas/Legends 4/Cenas/Tipos/Combate/Combate|Combate]] rápidas ou em que a ordem dos times seja mais importante do que a ordem individual de cada criatura.

### Conceitos
- **Time:** Representa um grupo de [[Sistemas/Legends 4/Criaturas/Criaturas|Criaturas]] que agem pelo mesmo lado em uma cena de [[Sistemas/Legends 4/Cenas/Tipos/Combate/Combate|Combate]].
- **Time Ativo:** Representa o `Time` que pode agir no momento atual, permitindo que suas [[Sistemas/Legends 4/Criaturas/Criaturas|Criaturas]] utilizem suas [[Ações]].
- **Representante:** Representa a [[Criatura]] que realiza a rolagem de [[Sistemas/Legends 4/Cenas/Tipos/Combate/Iniciativa/Iniciativa]] do seu `Time`.

### Resolução
No início de uma cena de [[Sistemas/Legends 4/Cenas/Tipos/Combate/Combate|Combate]], cada `Time` define uma [[Criatura]] `Representante` para realizar a rolagem de [[Sistemas/Legends 4/Cenas/Tipos/Combate/Iniciativa/Iniciativa]].

Cada `Representante` realiza uma rolagem de 1d20 + [[Reflexos]]. Os `Times` são ordenados do maior resultado para o menor e agem seguindo essa ordem. 

O `Time` com o maior resultado se torna o primeiro `Time Ativo`. Enquanto estiver ativo, as [[Sistemas/Legends 4/Criaturas/Criaturas|Criaturas]] desse `Time` podem agir usando suas [[Ações]], como [[Ação Padrão]], [[Ação de Movimento]], [[Ação Bônus]] e [[Ação Livre]].

Enquanto um `Time` for o `Time Ativo`, suas [[Sistemas/Legends 4/Criaturas/Criaturas|Criaturas]] podem agir em qualquer ordem e intercalar suas [[Ações]]. Uma [[Criatura]] pode pausar seu [[Turno]], permitir que outra [[Criatura]] do mesmo `Time` aja e retomá-lo antes que o próximo time se torne ativo.

Uma [[Criatura]] encerra seu turno quando decide encerrá-lo ou quando não possui mais [[Ações]] disponíveis, desconsiderando [[Ação Livre|Ações Livres]] e [[Reação|Reações]].

Quando todas as [[Sistemas/Legends 4/Criaturas/Criaturas|Criaturas]] do `Time Ativo` encerram seus [[Turno|Turnos]], o próximo `Time` na ordem de [[Sistemas/Legends 4/Cenas/Tipos/Combate/Iniciativa/Iniciativa]] se torna ativo.

Quando todas as criaturas do último `Time` da ordem encerram seus turnos, uma nova [[Rodada]] começa e o primeiro `Time` da ordem se torna ativo novamente.

### Reações
[[Reação|Reações]] e [[Ação Livre|Ações Livres]] podem ser usadas por uma [[Criatura]] mesmo que seu `Time` não seja o `Time Ativo` no momento, desde que seus gatilhos sejam cumpridos.

Caso uma [[Rodada]] termine e uma [[Criatura]] não tenha usado sua [[Reação]], esse recurso é perdido. Na nova [[Rodada]], as [[Reação|Reações]] são renovadas normalmente.

### Empates
Em caso de empate na rolagem de [[Sistemas/Legends 4/Cenas/Tipos/Combate/Iniciativa/Iniciativa]], o `Time` cujo `Representante` possui maior [[Reflexos]] age primeiro.

Se ainda houver empate, o [[Mestre]] decide a ordem ou solicita uma nova rolagem entre os `Representantes` empatados.

### Exemplo
Uma cena de [[Sistemas/Legends 4/Cenas/Tipos/Combate/Combate|Combate]] possui três times: `personagens`, `bandidos` e `esqueletos`.

Cada time escolhe um `Representante` para realizar sua rolagem de [[Sistemas/Legends 4/Cenas/Tipos/Combate/Iniciativa/Iniciativa]]. O representante dos `personagens` obtém o maior resultado, seguido pelos representantes dos `bandidos` e dos `esqueletos`, respectivamente.

Com a ordem definida, a primeira [[Rodada]] começa e os `personagens` se tornam o primeiro `Time Ativo`.

Um personagem se move e realiza um ataque. Antes de encerrar seu [[Turno]], ele permite que outro personagem conjure uma magia. Depois disso, o primeiro personagem retoma seu [[Turno]] e utiliza as [[Ações]] que ainda possui.

Mesmo que um dos personagens falhe em uma rolagem, seu time continua ativo. Os `bandidos` só se tornam o novo `Time Ativo` depois que todos os personagens encerram seus turnos.

Os `bandidos` realizam seus turnos da mesma forma e, quando todos os membros encerram seus turnos, os `esqueletos` se tornam o `Time Ativo`.

Quando todos os esqueletos encerram seus turnos, a primeira [[Rodada]] termina. Uma nova [[Rodada]] começa seguindo a mesma ordem, e os `personagens` se tornam o primeiro `Time Ativo` novamente.