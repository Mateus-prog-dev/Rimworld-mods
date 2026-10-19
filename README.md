created by Mateus, the mod had help from Claude AI

A RimWorld mod that lets drafted colonists eat food and use drugs from their inventory without being undrafted, with optional automation for hunger and mental-break risk.

Supported RimWorld versions: 1.5 and 1.6 · Requires Harmony: no · Languages: English, Brazilian Portuguese

Everything in this mod only works while the colonist is drafted.

Features
🍽️ Eat button
A button appears next to the draft button when a drafted colonist has edible food in their inventory.
Uses the best food available (never raw food, never drugs).
Disabled when the colonist's food bar is practically full.
👥 Group eat button
Appears when two or more colonists are selected and all of them are drafted.
Every selected colonist eats from their inventory even if they are not hungry. Colonists without food are skipped.
🤖 Auto-eat
A drafted colonist who is hungry eats on their own when no hostile is within 20 cells.
Only starts when the colonist is idle (it never interrupts movement or attack orders).
Never eats raw food. Stops eating automatically if an enemy shows up.
💊 Auto-drugs (mental-break prevention)
Minor or major break risk → drinks a beer from the inventory.
Extreme break risk → smokes a smokeleaf joint (then falls back to beer).
After each dose it waits 10 seconds; if the colonist is still at risk, the next dose is used.
Default limits: 3 beers and 1 joint. Limits reset when the colonist is undrafted.
A dose that is cancelled does not count towards the limit.
Flake and yayo can be enabled in the settings. They are used only at extreme risk, after the main drugs reached their limit or are missing. An option allows them at major risk as well (never at minor).
🎒 Cancelled? The item goes back to the inventory

If the eating or drug-use animation is cancelled or interrupted, the item returns whole to the colonist's inventory instead of dropping on the ground (no partially eaten food, same as vanilla behaviour otherwise).

⚙️ Mod settings

Options → Mod settings → Eat From Inventory v5

Turn auto-drug use on/off.
Wait time between doses (5–60 s).

Compatibility notes
No Harmony: the mod replaces the vanilla Ingest job driver with a subclass that behaves the same, except for returning the item to the inventory when the job ends for a drafted colonist.
Flake = "Floco" and Yayo = "Brilho" in the Brazilian Portuguese settings text; the names shown in the settings menu come from the game's own language files.



🇧🇷 Português

🇬🇧 English · 🇧🇷 Português

Um mod de RimWorld que permite que colonos alistados (drafted) comam comida e usem drogas do inventário sem precisar desalistar, com automações opcionais para fome e risco de colapso mental.

Versões do RimWorld suportadas: 1.5 e 1.6 · Precisa de Harmony: não · Idiomas: inglês e português brasileiro

Tudo neste mod só funciona enquanto o colono estiver alistado.

Funções
🍽️ Botão de comer
Aparece ao lado do botão de alistar quando um colono alistado tem comida no inventário.
Usa a melhor comida disponível (nunca comida crua, nunca drogas).
Fica desativado quando a barra de comida do colono está praticamente cheia.
👥 Botão de comer em grupo
Aparece quando dois ou mais colonos estão selecionados e todos estão alistados.
Cada colono selecionado come do inventário mesmo sem estar com fome. Quem não tem comida é ignorado.
🤖 Comer automático
O colono alistado que está com fome come sozinho quando não há nenhum inimigo num raio de 20 células.
Só começa quando o colono está parado (nunca interrompe ordens de movimento ou ataque).
Nunca come comida crua. Para de comer automaticamente se um inimigo aparecer.
💊 Drogas automáticas (prevenção de colapso mental)
Risco de colapso leve ou grave → bebe uma cerveja do inventário.
Risco de colapso extremo → fuma um baseado de folha de fumo (depois recorre à cerveja).
Depois de cada dose espera 10 segundos; se o colono continuar em risco, usa a próxima dose.
Limites padrão: 3 cervejas e 1 baseado. Os limites reiniciam quando o colono é desalistado.
Uma dose cancelada não conta no limite.
Floco (flake) e brilho (yayo) podem ser habilitados nas configurações. Eles são usados somente em risco extremo, depois que as drogas principais bateram o limite ou faltaram. Uma opção permite usá-los também em risco grave (nunca no leve).
🎒 Cancelou? O item volta para o inventário

Se a animação de comer ou usar a droga for cancelada ou interrompida, o item volta inteiro para o inventário do colono em vez de cair no chão (sem comida parcialmente comida; fora isso, o comportamento é o do jogo).

⚙️ Configurações do mod

Opções → Configurações de mods → Eat From Inventory v5

Liga/desliga o uso automático de drogas.
Tempo de espera entre doses (5 a 60 s).
Permitir ou bloquear cada droga e ajustar o limite (0 a 10).
Permitir floco/brilho também em risco grave.
Restaurar padrões.
Instalação
Baixe a última release
Coloque a pasta EatFromInventory em RimWorld/Mods/.
Ative o mod na lista de mods. Nenhum outro mod é necessário.
Allow or block each drug and set its limit (0–10).
Allow flake/yayo also at major risk.
Reset to defaults.

Notas de compatibilidade
Sem Harmony: o mod troca o driver do job Ingest do jogo por uma subclasse que se comporta igual, exceto por devolver o item ao inventário quando o job termina para um colono alistado.
Floco = Flake e Brilho = Yayo; os nomes mostrados no menu vêm dos arquivos de idioma do próprio jogo.
