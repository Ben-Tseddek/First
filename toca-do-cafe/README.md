# Toca do Café

Jogo de arcade original para PC, no gênero "cavar túneis" dos anos 80, com gráficos desenhados em tempo real (HTML5 Canvas), iluminação dinâmica e ciclo de dia e noite.

Um jardineiro de chapéu de palha, com lanterna na aba, cava a terra para colher grãos de **Café Catuaí Amarelo**, enquanto besouros, vespas e tatus saem do ninho para persegui-lo.

## Como jogar

Abra `index.html` em qualquer navegador moderno. Na tela inicial escolha a dificuldade (← → ou 1–4) e pressione Enter.

| Tecla | Ação |
|---|---|
| Setas ou W A S D | Andar e cavar |
| Espaço (X / Z) | Lançar a semente mágica |
| P ou Esc | Menu de pausa (som, música, voltar) |
| M | Liga/desliga o som |
| Enter | Confirmar |
| Controle (gamepad) | Direcional/analógico, botão A = semente, Start = pausa |

## Dificuldades

| Nível | Vidas | Inimigos por fase | Observação |
|---|---|---|---|
| Fácil (Colhedor) | 5 | 4+ | lentos, semente recarrega rápido |
| Normal (Lavrador) | 3 | 6+ | ritmo clássico |
| Difícil (Mestre do Terreiro) | 3 | 8+ | vespas desde o início |
| Lendário (Barão do Café) | 2 | 10+ | enxame, tatus cedo |

O recorde é guardado separadamente para cada dificuldade.

## Regras

- **Grãos de café**: colha todos para passar de nível. Oito seguidos valem +500 e chamam um **vagalume**.
- **Vagalumes** carregam as letras **C·A·F·É**. Acerte-os com a semente ou com uma jaca; as quatro letras dão vida extra e +3000.
- **Jacas**: cave embaixo e elas caem, esmagando quem estiver no caminho (1000, 2000, 4000...). Dá para empurrá-las de lado num túnel aberto. Se caírem mais de uma fileira, se partem.
- **Semente mágica**: ricocheteia pelos túneis e elimina o primeiro inimigo que tocar. Recarrega cada vez mais devagar.
- **Inimigos**: besouros (perseguem; às vezes viram toupeiras e cavam até você), vespas (rápidas e erráticas), tatus (blindados: a semente só os deixa tontos; precisam de uma jaca).
- **Diamante**: aparece no ninho quando todos os inimigos saíram. Congela os inimigos; tocá-los nesse tempo os elimina (+300).
- **Power-ups** caem de inimigos esmagados: Lanterna (luz maior e inimigos lentos), Sementes (recarga instantânea por 12 s), Relógio (congela 5 s).
- **Fase bônus** a cada 3 níveis: 28 segundos de chuva de café, sem inimigos.
- Vida extra aos 10.000 pontos e a cada 20.000 depois.

## Ambiente

Cada nível muda o solo e a hora do dia. À noite só se vê o que a lanterna alcança; os olhos dos inimigos, os grãos e a semente brilham no escuro.

| Solo | Por que tem essa cor |
|---|---|
| Terra Roxa | hematita, Fe₂O₃ |
| Barro Dourado | goethita, FeO(OH) |
| Húmus da Mata | ácidos húmicos da matéria orgânica |
| Argila do Rio | caulinita, Al₂Si₂O₅(OH)₄ |
| Cascalho de Quartzo | SiO₂ |
