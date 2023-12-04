# Joyjog Challenge Developer

Olá,
Primeiramente, obrigado pelo seu tempo. A seguir, explicaremos sobre o desafio.

Utilize a Unity na versão **2022.3** ou superior.

Seu objetivo é criar um jogo de plataforma 2D, para que um Game Design possa utilizar os espectros da Unity 3D e colocar todos os assets conforme no GDD.

Iremos utilizar estes assets para o cenário [ASSETS](https://assetstore.unity.com/packages/2d/characters/gothicvania-town-101407)

##### Personagem principal
- [Personagem](https://assetstore.unity.com/packages/2d/characters/warrior-free-asset-195707)

##### Sonoplastia
- [cenas](https://assetstore.unity.com/packages/audio/music/-free-music-tracks-for-games-156413)
- [swords](https://assetstore.unity.com/packages/audio/sound-fx/weapons/swordsoundpack-177824)
- [Magic](https://assetstore.unity.com/packages/audio/sound-fx/weapons/demo-ancient-magic-pack-free-175093)

## Prazo

Você terá um prazo de 7 dias para finalizar o teste, o prazo se inicia quando o recrutador informar este repositório ao candidato. Caso precise de mais tempo, informar ao recrutador com antecedência, que não será possível concluir o teste e informar o novo prazo para entrega.

## GDD - Game Design Document

### Mecânicas Básicas

#### Movimento Controlado por Teclas

O jogador precisa movimentar o personagem usando as teclas W, A, S, D.
O personagem precisa ter a capacidade de saltar com a barra de espaço.
O ataque do personagem deverá ficar no mouse, apertando o botão esquerdo.
O dasn deverá ficar no mouse, apertando o botão direito.


#### Coleta de Itens e Pontuação

Teremos um sistema de coleta de itens em que o jogador pode interagir com objetos espalhados pelo cenário para ganhar pontos. Cada item coletado deve ser registrado na interface do usuário, mostrando a pontuação atual.

#### Sistema de Inventário

Implemente um sistema de inventário onde o jogador pode coletar e armazenar diferentes tipos de itens. Permita que o jogador visualize seu inventário apertando a tecla **I** e possa utilizar os itens em lugares específicos sem a necessidade de precisar selecionar o item em seu inventário.
Por exemplo: Pode-se coletar uma chave em algum ponto do cenário, e utilizar esta chave em uma porta utilizando a tecla E.
As chaves precisam ser únicas e abrir somente um tipo de porta.

### Animações de Transição de Cena

Crie um ambiente com múltiplas cenas e implemente transições suaves entre elas. Por exemplo, ao entrar em uma porta, o jogador deve ser levado para outra cena.

### Sistema de Saúde e Dano

Crie um sistema de saúde para o jogador, onde ele pode ser danificado por obstáculos ou inimigos. Implemente também a capacidade de recuperar a saúde ao coletar itens específicos.

### Mecânica de Teletransporte

Implemente pontos de teletransporte no cenário, permitindo que o jogador se mova instantaneamente entre diferentes áreas do jogo.

&nbsp;

## GamePlay

#### Fase 1

O objetivo é encontrar uma chave para abrir uma porta 1 que está no início do cenário. A chave se encontra no final do mapa, ao coletar a chave poderá ser aberta a porta utilizando a tecla E.

#### Fase 2
O objetivo é matar 1 inimigo que utiliza as mesmas mecânicas da personagem principal, este inimigo não poderá utilizar o dash. Ao derrotar recebe uma chave que abre a porta 2 que leva para a cena 1 e se reinicia o level.


#### Desafio (não obrigatório)
Criar um NPC e utilizar o [ASSET](https://assetstore.unity.com/packages/tools/utilities/dialogue-editor-168329#reviews) para criar um diálogo simples.

### Entregável

Este repositório é um [Template](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template), e você deve criar seu projeto com base neste template. Leve em consideração os seguintes pontos:

- Seu usuário deve ser o **proprietário**
- Ao usar o modelo, selecione a opção `Incluir todas as branches` para fazer download de todas as branches do repositório.
- Depois de criar o repositório privado a partir do template, você deve usar os arquivos na branch `main`.
- Se não especificarem uma branch, você deve usar os arquivos que estão na `main`
- O repositório deve ser `privado`
- Depois que terminar compartilhe o desafio conosco adicione o usuário: **aquinoWill**
- Envie um email para o recrutador avisando do término do teste para ser analisado.


### Requisitos Técnicos
- Capacidade analítica;
- Qualidade do trabalho;
- Clean Code;
- Habilidade de organização dos Scripts, GamesObjects, Prefabs e Assets;

São **desejáveis** os seguintes pontos:

- Entregar no prazo;
- Atenção aos detalhes;
- Utilizar títulos e descrição para atributos públicos;
- Criar duas cenas para demostrar a transição;
- Animações do personagem principal

Desejáveis mas **não obrigatórios**:
- Commit semântico com ou sem uma ferramenta ou biblioteca;
- SOLID Architecture;
- Aplicar os assets para cenário;
- Animações dos personagens secundários;
- Configurar FMOD para aplicar sons e músicas.

#### Lembre-se

Você será avaliado como desenvolvedor(a), você precisa deixar tudo pronto para que um game design consiga trabalhar e aplicar os assets, sons e etc. Deixe tudo configurado que seja fácil para qualquer pessoa consiga utilizar sem a necessidade de documentação ou treinamento.

Boa sorte!
