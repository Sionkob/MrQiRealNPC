#### Português | [English](./README.md)

# Senhor Qi é um Verdadeiro NPC
[Senhor Qi é um Verdadeiro NPC](https://www.nexusmods.com/stardewvalley/mods/16724) é um mod Content Patcher que transforma o Senhor Qi em um NPC presenteável adicionando ele como um NPC customizado. O mod traz uma história nova para o personagem respeitando a personalidade original do Senhor Qi.

# Requisitos
Atualmente, o mod precisa de 2 mods para funcionar:
- [Content Patcher](https://www.nexusmods.com/stardewvalley/mods/1915) - De Pathoschild
- [Extra Map Layers](https://www.nexusmods.com/stardewvalley/mods/9633) - De aedenthorn

# Instruções de instalação
Para instalar o mod, basta copiá-lo para a pasta Mods do seu jogo. Para desinstalá-lo, basta remover a pasta do mod da sua pasta Mods.

# O que está funcionando atualmente?
O mod está em desenvolvimento e algumas coisas ainda não estão completas, mas algumas coisas já estão funcionando, por exemplo:
- Sr. Qi é reconhecido como um NPC presenteável pelo jogo.
- Existem novos diálogos até 4 corações.
- Existem 4 eventos prontos, sendo 2 deles eventos de coração.
- 2 novos mapas foram adicionados.

Conforme o mod for atualizado, mais funções serão adicionadas, removidas ou modificadas.

# O que não funciona/não está 100% pronto?
Atualmente existem algumas coisas que não estão completas por enquanto, eu irei terminá-las o mais rápido possível:
- Os horários estão incompletos, só há o horário para a Primavera.
- Os gostos de presentes ainda não estão definidos. No momento são os mesmos gostos de presentes de Abigail com poucas alterações.
- Sr. Qi não aparece em nenhum festival.
- Não é possível convidá-lo para assistir um filme.
- Faltam os diálogos de 6, 8 e 10 corações.
- Faltam os eventos de 6, 8 e 10 corações.

Nos meus testes, não há nada que não esteja funcionando, apenas há alguns recursos incompletos que serão completos conforme as atualizações. Se você tiver alguma sugestão ou encontrar algum bug, sinta-se a vontade para comentar na página de [posts](https://www.nexusmods.com/stardewvalley/mods/16724?tab=posts) no Nexus Mods.

# Mais detalhes
Aqui estão alguns detalhes sobre o que está adicionado atualmente, algumas coisas podem mudar no decorrer das atualizações.

## Configurações
Esse mod traz uma configuração, que pode ser mudada quando você abrir o jogo pela primeira vez após instalar o mod:

#### Criança ou Nome
Essa configuração permite que você mude a forma que o Sr. Qi irá se referir a você em alguns diálogos, ele pode se referir a você como “Criança” ou nome do seu fazendeiro. O padrão é que ele use o nome do seu fazendeiro. 

## Novos Mapas
Este mod adiciona 2 novos mapas ao jogo: O quarto do Sr. Qi e um pequeno laboratório.

### Mapa do quarto do Sr. Qi:

<img src="https://i.ibb.co/MkNDV9K/QiRoom.png" width="710" height="355">

O quarto do Sr. Qi pode ser acessado por um corredor no Cassino.

### Mapa do laboratório:

<img src="https://i.ibb.co/5BtmWhk/QiLab.png" width="694" height="336">

A entrada para o laboratório do Sr. Qi fica na porta no centro do pequeno corredor no quarto dele. O laboratório só pode ser acessado quando o jogador tiver 6 corações ou mais com o Sr. Qi. Se o jogador não tiver corações o suficiente, a entrada para o laboratório do Sr. Qi estará fechada com uma parede invisível que impede a passagem do jogador.

## Eventos
Atualmente há 4 eventos adicionados, 2 deles são eventos de coração, mais eventos serão adicionados com o tempo. Essas são as pré-condições para acionar cada evento:

#### Evento #1
Entre no Cassino após obter o [Cartão do Clube](https://pt.stardewvalleywiki.com/Cart%C3%A3o_do_Clube).

#### Evento #2
Após atingir o nível 100 da [Caverna da Caveira](https://pt.stardewvalleywiki.com/Caverna_da_Caveira) após ter lido o [Recado Secreto #10](https://pt.stardewvalleywiki.com/Recados_Secretos#Recado_Secreto_.2310), volte para a entrada da Caverna da Caveira.

#### Evento #3
Tendo 2 corações com Sr. Qi, entre no [Cassino](https://pt.stardewvalleywiki.com/Cassino) a qualquer hora.

#### Evento #4
Tendo 4 corações com Sr. Qi, entre no [Oásis](https://pt.stardewvalleywiki.com/O%C3%A1sis) entre 09h e 21h.

## Horários
Atualmente há apenas o horário para a Primavera, que é aplicado a todas as estações.

Sr. Qi sai do seu quarto as 7h e fica no cassino até o meio-dia, após isso ele entra no seu laboratório e fica lá até a meia-noite, quando vai dormir. Entre as 19h e a meia-noite, se você entrar na [Sala de Nozes](https://pt.stardewvalleywiki.com/Sala_de_Nozes_do_Sr._Qi) você o encontrará observando o telão à sua frente. Você não conseguirá pontos de amizade interagindo com ele quando ele estiver na Sala de Nozes, e também não há diálogos definidos para ele quando ele estiver lá.

Pode ser difícil obter pontos de amizade com ele no início porque ele fica muito tempo no laboratório, que é inacessível ao jogador até que você tenha 6 corações com ele. Ele também fica pouco tempo no Cassino, um dos poucos momentos em que você pode conversar com ele. Eu irei melhorar esse horário e adicionar novos horários para os dias da semana e outras estações.

# Erros Conhecidos
No momento há apenas um “erro” no mod:

Ao abrir o jogo pela primeira vez (ou no início de cada dia), se você abrir o console SMAPI, encontrará um erro parecido com esse:

`[ERROR game] Failed parsing schedule for NPC Mister Qi:
0 QiNutRoom 5 2 1/1920 QiNutRoom 7 4 0 mrqi_staring/2400 QiNutRoom 5 2 1
ArgumentException: In warpCharacter, the character's currentLocation must not be null
   at StardewValley.Game1.warpCharacter(NPC character, GameLocation targetLocation, Vector2 position)
   at StardewValley.NPC.parseMasterSchedule_Patch1(NPC this, String rawData)`
	
Esse erro acontece porque existem 2 “Senhores Qi” no jogo, cada um com um nome interno diferente. Um deles tem o nome interno definido como “Mister Qi”. Esse Sr. Qi não pode ser transformado em um NPC presenteável (ou seja, não é possível fazer amizade), mas aparentemente ele pode ter um horário, mesmo que o console SMAPI acuse erro. Nos meus testes mesmo com esse erro, o horário funciona normalmente, esse erro pode ser ignorado, pelo menos por enquanto. Eu ainda não sei como corrigir esse erro, mas eu estou estudando formas de resolvê-lo o mais rápido possível.
