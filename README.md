# Teste Prático, Desenvolvedor(a) de Jogos Unity - Joyjog

Bem-vindo(a)! Este é um desafio prático curto, pensado para você mostrar como pensa e trabalha. Não existe uma "resposta certa" única, queremos ver **como** você constrói um jogo.

Leia tudo com calma antes de começar. A parte mais importante talvez não seja a que parece.
Caso tenha alguma dúvida, **não inicie o teste** pergunte ao intrevistador, lembre-se estamos aqui para ajudar a você fazer o seu melhor!

---

## O que você vai construir

Um mini-jogo de plataforma em 3D. A ideia é simples de descrever:

- Um **personagem** representado por um **cilindro**.
- Uma série de **caixas (steps)** dispostas no cenário, formando um percurso.
- O personagem **salta entre as caixas** para avançar.
- Espalhadas pelo caminho, existem **moedas** que o jogador **coleta**.

É isso. O jogo cabe em uma frase. O que **fazemos** com essa frase é o que nos interessa.

---

## Requisitos mínimos

Para o teste ser considerado válido, o projeto precisa ter:

1. Um personagem-cilindro controlável pelo jogador(W,A,S,D).
2. Movimentação e **pulo** funcionais.(SPACE)
3. Um percurso de caixas onde o personagem consiga saltar de uma para a outra.
4. Moedas que possam ser **coletadas** ao contato.
5. Alguma forma de o jogador saber quantas moedas coletou (contador, HUD, ou o que fizer sentido).

Se você entregar apenas isso, funcionando sem bugs, o requisito básico está cumprido. Caso não consiga entregar os requisitos mínimos do teste no prazo, entre em contato com o entrevistador.

Emprevistos acontecem e não queremos que fatores externos atrapalhe no seu teste!

---

## Especificações técnicas

- **Engine:** Unity 6 LTS (ou versão LTS recente equivalente).
- **Render pipeline:** URP (Universal Render Pipeline).
- **Dimensão:** 3D.
- **Assets:** você tem total liberdade. Sugerimos usar formar primitivas da Unity (cilindro, cubos). Não precisa de arte sofisticada **não estamos avaliando modelagem**.
- **Código:** C#. Organize como preferir, mas de preferência para padrão de desenvolvimento a arquitetura.

Não há restrição sobre pacotes, plugins ou ferramentas auxiliares. Use o que você usaria em um projeto real.

## Padrões técnicos e boas práticas

Vamos olhar o projeto com os mesmos olhos com que olharíamos código que entra em produção. Não temos uma lista fechada de exigências, o que nos interessa é perceber, pelo seu código, que você conhece e aplica os padrões consolidados do mercado quando eles fazem sentido.

Pergunte-se coisas como: este código seria fácil de outra pessoa ler e estender? As responsabilidades estão bem separadas? Os sistemas conversam de forma desacoplada? Os valores importantes estão fáceis de ajustar? A base está pronta para crescer sem virar uma bola de neve?

Não esperamos arquitetura de engine AAA num desafio pequeno, esperamos maturidade para tomar boas decisões técnicas no escopo certo. Mostre que, mesmo num projeto simples, você trabalha como trabalharia num projeto de verdade.

---

## Liberdade criativa

Demos o esqueleto de propósito. **Tudo o que não está listado como requisito mínimo é decisão sua**: câmera, controles, ritmo, dificuldade, estética, quantidade de fases, condição de vitória, o que acontece quando o jogador coleta todas as moedas... Faça as escolhas que você faria se este fosse *seu* jogo.

Preferimos ver um escopo pequeno bem executado do que um escopo grande pela metade.

---

## Entrega

Este repositório é um [Template](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template), e você deve criar seu projeto com base neste template. Leve em consideração os seguintes pontos:

- **Propriedade:** Seu usuário deve ser o **proprietário**
- **Como entregar:** Ao usar o modelo, selecione a opção `Incluir todas as branches` para fazer download de todas as branches do repositório.
- **Qual Branch usar:** Depois de criar o repositório privado a partir do template, você deve usar os arquivos na branch `main`. Se não especificarem uma branch, você deve usar os arquivos que estão na `main`
- **Tipo de repositórop:** O repositório deve ser `privado`
- **Adcionar Reviwer:** Depois que terminar compartilhe o desafio conosco adicione o usuário: **aquinoWill**
- **Notificar:** Envie uma mensagem no Discord para o recrutador avisando do término do teste para ser analisado.
- **Prazo sugerido:** `3 dias` Não precisa usar todo o tempo, use o que achar necessário.
- **Build:** não precisa fazer o build
- **Descrição:** Crie um novo arquivo na raiz do projeto com o nome `SEU_NOME.md` contando o que você priorizou, como pensou, descrevendo as suas desisões de uma forma clara e simples.

---

## Dicas

Algumas observações soltas, sem ordem de importância, leve como conversa, não como checklist.

O jogo, no papel, é trivial: um cilindro, umas caixas, umas moedas, um pulo. Você provavelmente monta o esqueleto funcional em pouco tempo. A pergunta interessante começa depois disso: **quando o esqueleto já roda, o que você faz com o tempo que sobra?**

Pense em como o jogo **se sente** na mão de quem joga, não só em como ele funciona. Um pulo pode simplesmente mover o cilindro para cima, ou pode ser algo que dá vontade de repetir. Uma moeda pode sumir ao ser tocada, ou pode *acontecer* algo quando ela some. Cada ação do jogador é uma oportunidade de resposta: o que o jogo devolve quando ele pula, aterrissa, coleta, erra o salto?

Não estamos pedindo nada disso explicitamente. Estamos curiosos para ver **o que você acha que um bom jogo precisa ter** quando ninguém te entrega uma lista. Onde você decide investir esforço quando a especificação para de te dizer o que fazer diz muito sobre como você trabalha.

Se em algum momento você se pegar pensando "isso aqui já está funcionando, mas ainda não está *gostoso*" siga essa intuição. É exatamente esse tipo de percepção que gostamos de ver em ação.

E, no fim: divirta-se. Se o jogo for divertido para você construir e testar, há uma boa chance de ser divertido para quem for avaliar. Surpreenda a gente.

---

## O que NÃO precisa se preocupar

- Não precisa de menu completo, save/load, ou telas de configuração.
- Não precisa de arte original nem áudio autoral (assets livres estão liberados).
- Não precisa suportar múltiplas plataformas.
- Não precisa de multiplayer.

Foque a energia no jogo em si.

---

Boa sorte, e divirta-se construindo. 🎮
