[[Iniciativa|<- Iniciativa]]

### Descrição
Neste tipo, as [[Criatura|Criaturas]] envolvidas na cena de [[Sistemas/Legends 4/Cenas/Tipos/Combate/Combate|Combate]] são separadas em times. Cada time possui sua própria posição na ordem de [[Iniciativa]], mas o time que está ativo alterna conforme falhas e decisões táticas.

Diferente da [[Por Time|Iniciativa por Time]], as [[Sistemas/Legends 4/Criaturas/Criaturas|Criaturas]] de um time não precisam ter seus turnos encerrados para que outro time se torne ativo. O turno de uma [[Criatura]] pode ser pausado e retomado dentro da mesma [[Rodada]], até que ela encerre seu próprio [[Turno]] ou fique sem [[Ações]] disponíveis.

### Quando Usar
Este é o tipo de [[Iniciativa]] recomendado para jogar Legends 4.

Use este tipo em qualquer cena de [[Sistemas/Legends 4/Cenas/Tipos/Combate/Combate|Combate]], mas principalmente naqueles com peso narrativo, ritmo dinâmico e tensão a cada rolagem importante.

### Conceitos
- **Time:** Representa um grupo de [[Sistemas/Legends 4/Criaturas/Criaturas|Criaturas]] que agem pelo mesmo lado em uma cena de [[Sistemas/Legends 4/Cenas/Tipos/Combate/Combate|Combate]].
- **Time Ativo:** Representa o `Time` que pode agir no momento atual, permitindo que suas [[Sistemas/Legends 4/Criaturas/Criaturas|Criaturas]] utilizem suas [[Ações]].
- **Time Elegível:** Representa o `Time` que possui ao menos uma [[Criatura]] que ainda não encerrou seu [[Turno]] naquela [[Rodada]].
- **Representante:** Representa a [[Criatura]] que realiza a rolagem de [[Iniciativa]] do seu `Time`.
- **Rolagem com Dificuldade:** Representa uma rolagem cujo resultado pode ser bem-sucedido ou falho, como uma rolagem de [[Perícias]] ou [[Rolagem de Ataque]]. Rolagens de dano, duração, quantidade e semelhantes não são `Rolagens com Dificuldade`.

### Resolução
No início de uma cena de [[Sistemas/Legends 4/Cenas/Tipos/Combate/Combate|Combate]], cada `Time` define uma [[Criatura]] `Representante` para realizar a rolagem de [[Iniciativa]].

Cada `Representante` realiza uma rolagem de 1d20 + [[Reflexos]]. Os `Times` são ordenados do maior resultado para o menor e agem seguindo essa ordem. 

O `Time` com maior resultado se torna o primeiro `Time Ativo`. Enquanto ativo, as [[Sistemas/Legends 4/Criaturas/Criaturas|Criaturas]] desse `Time` podem agir usando suas [[Ações]], como [[Ação Padrão]], [[Ação de Movimento]], [[Ação Bônus]] e [[Ação Livre]].

As [[Sistemas/Legends 4/Criaturas/Criaturas|Criaturas]] do `Time Ativo` podem agir em qualquer ordem escolhida pelos [[Jogador|Jogadores]] ou pelo [[Mestre]], dependendo de quem controla o `Time`.

Enquanto um `Time` for o `Time Ativo`, suas [[Sistemas/Legends 4/Criaturas/Criaturas|Criaturas]] podem agir em qualquer ordem e intercalar suas [[Ações]].

Quando uma [[Criatura]] do `Time Ativo` falha em uma `Rolagem com Dificuldade`, a ação, habilidade, efeito ou regra que exigiu a rolagem é completamente resolvida. Depois disso, o time fica inativo e o próximo `Time Elegível` na ordem de [[Iniciativa]] se torna o novo `Time Ativo`.

Quando todas as [[Sistemas/Legends 4/Criaturas/Criaturas|Criaturas]] do `Time Ativo` encerram seus [[Turno|Turnos]], ele deixa de ser um `Time Elegível` e o próximo `Time Elegível` se torna o novo `Time Ativo`.

Quando o último `Time` da ordem fica inativo, a [[Rodada]] não termina automaticamente. O primeiro `Time Elegível` da ordem se torna o `Time Ativo` novamente.

Caso reste apenas um `Time Elegível` na [[Rodada]], suas falhas não o tornam inativo, pois não existe outro `Time Elegível` para assumir.

Quando não restar nenhum `Time Elegível`, a [[Rodada]] termina. Todas as criaturas renovam suas [[Ações]] e [[Reação|Reações]], e uma nova [[Rodada]] começa seguindo a mesma ordem de [[Iniciativa]]. O primeiro `Time Elegível` da ordem se torna o novo `Time Ativo`.

Caso nenhuma [[Criatura]] do `Time Ativo` queira agir naquele momento e exista outro `Time Elegível`, o time pode ficar inativo voluntariamente. O próximo `Time Elegível` se torna ativo, mas os turnos ainda não encerrados do time anterior permanecem disponíveis.

Caso todos os `Times Elegíveis` fiquem inativos voluntariamente em sequência sem que nenhuma [[Criatura]] realize uma [[Ações|Ação]] ou encerre seu [[Turno]], o primeiro `Time Elegível` volta a ser ativo. Esse time não pode ficar inativo voluntariamente novamente até que uma de suas [[Sistemas/Legends 4/Criaturas/Criaturas|Criaturas]] realize uma ação ou encerre seu [[Turno]].

### Re-rolagens
Caso uma `Rolagem com Dificuldade` falha possa ser re-rolada, o `Time Ativo` só fica inativo depois que todas as re-rolagens permitidas forem realizadas ou recusadas.

Apenas o resultado final é considerado. Caso ele seja bem-sucedido, o `Time Ativo` continua agindo normalmente.

### Turno da Criatura
O [[Turno]] de uma [[Criatura]] começa quando ela decide agir enquanto seu `Time` for o `Time Ativo`. Ao iniciar seu [[Turno]], ela resolve todas as regras de começo de turno antes de utilizar suas [[Ações]]. Utilizar apenas [[Reação|Reações]] ou [[Ação Livre|Ações Livres]] não inicia seu [[Turno]].

Uma [[Criatura]] encerra seu [[Turno]] quando decide encerrá-lo ou quando não possui mais [[Ação Padrão|Ações Padrão]], [[Ação Bônus|Ações Bônus]] ou [[Ação de Movimento|Ações de Movimento]] que possa realizar durante ele. [[Ação Livre|Ações Livres]] e [[Reação|Reações]] não impedem o encerramento do [[Turno]].

Uma [[Criatura]] pode deixar de agir enquanto seu `Time` for o `Time Ativo` sem encerrar seu turno. Nesse caso, ela poderá agir novamente quando seu `Time` voltar a se tornar o ativo durante a mesma [[Rodada]].

Caso uma [[Criatura]] precise realizar uma rolagem no começo de seu [[Turno]], ela pode permitir que outras [[Sistemas/Legends 4/Criaturas/Criaturas|Criaturas]] do mesmo `Time` ajam antes que ela, desde que ainda não tenha iniciado seu próprio turno.

O [[Mestre]] pode encerrar o [[Turno]] de uma [[Criatura]] caso o [[Jogador]] esteja evitando encerrá-lo para abusar de efeitos, ações restantes ou regras de fim de turno.

Pausar um [[Turno]] não encerra ou renova efeitos ligados ao seu começo ou fim. Esses efeitos permanecem ativos até que o [[Turno]] seja realmente encerrado.

### Reações
[[Reação|Reações]] e [[Ação Livre|Ações Livres]] podem ser usadas por uma [[Criatura]] mesmo que seu `Time` não seja o `Time Ativo` no momento, desde que seus gatilhos sejam cumpridos.

Falhas em rolagens feitas como parte de [[Reação|Reações]] de [[Sistemas/Legends 4/Criaturas/Criaturas|Criaturas]] que não pertencem ao `Time Ativo` não trocam o status dele.

Caso uma [[Rodada]] termine e uma [[Criatura]] não tenha usado sua [[Reação]], esse recurso é perdido. Na nova [[Rodada]], as [[Reação|Reações]] são renovadas normalmente.

### Empates
Em caso de empate na rolagem de [[Iniciativa]], o `Time` cujo `Representante` possui maior [[Reflexos]] age primeiro.

Se ainda houver empate, o [[Mestre]] decide a ordem ou solicita uma nova rolagem entre os `Representantes` empatados.

### Exemplo
Uma cena de [[Sistemas/Legends 4/Cenas/Tipos/Combate/Combate|Combate]] possui três times: `personagens`, `esqueletos` e `bandidos`.

Os `Representantes` realizam suas rolagens de [[Iniciativa]]. O representante dos `personagens` obtém o maior resultado, seguido pelos representantes dos `bandidos` e dos `esqueletos`, respectivamente.

Com a ordem de [[Iniciativa]] definida, a primeira [[Rodada]] se inicia, onde os `personagens` se tornam o primeiro `Time Ativo`.

Um personagem ataca e falha na rolagem, mas usa uma habilidade para re-rolar. A nova rolagem é bem-sucedida, então os `personagens` continuam ativos.

Depois, outro personagem tenta conjurar uma magia e falha. A magia é resolvida, os `personagens` ficam inativos e os `bandidos` se tornam o `Time Ativo`.

Os `bandidos` realizam todas as suas [[Ações]] sem falhas e todos os membros encerram seus turnos. Os `bandidos` então ficam inativos e não são mais considerados um `Time Elegível` por aquela [[Rodada]]. 

Os `esqueletos` se tornam o `Time Ativo`. Um esqueleto ataca e falha. Após o ataque ser resolvido, os `esqueletos` ficam inativos e os `personagens` se tornam o `Time Ativo` novamente.

Mais tarde, quando apenas os `esqueletos` ainda possuem criaturas com turnos não encerrados, eles continuam ativos mesmo que falhem, pois não existe nenhum outro `Time Elegível` para se tornar um `Time Ativo` naquela [[Rodada]].

Quando os `esqueletos` encerram seus turnos, não resta nenhum `Time Elegível`. A primeira [[Rodada]] termina, todas as [[Sistemas/Legends 4/Criaturas/Criaturas|Criaturas]] renovam suas [[Ações]] e [[Reação|Reações]], e os `personagens` se tornam o primeiro `Time Ativo` da nova [[Rodada]].