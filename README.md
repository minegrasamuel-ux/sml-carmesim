# SML Carmesim V6

Painel Luau para Roblox com identidade SML, movimento, combate, ESP e uma rotina experimental para Batatinha Frita no Squid Game X.

O arquivo `sml-carmesim.lua` contém o script completo e a logo incorporada. A publicação permite carregar esse arquivo por uma URL Raw, sem colar o código inteiro no editor.

## Estado da versão

- Sintaxe e comportamento verificados em simulação; não validados ao vivo no Delta.
- Somente Batatinha Frita está mapeada para a opção AUTO FASE. Outras fases aguardam implementação.
- O teleporte depende de verde confirmado e dos objetos da arena carregados.
- O servidor decide dano, recarga, recompensas e validação dos movimentos. A rotina não confirma vitória apenas pela posição local.
- A invisibilidade é visual local. Não inclui imortalidade nem criação de moedas.

## Controles

- O X minimiza o painel para o ícone SML sem desligar os recursos.
- COMBATE: equipe o soco, clique VINCULAR e ligue SOCO / COMBO AUTO.
- RODADAS: entre como corredor e ative AUTO FASE para a rotina mapeada.
- No PC: F alterna voo, T tenta atacar e RightShift alterna o painel.
