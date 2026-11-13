# Batman: Arkham Knight — co-op online (versão de teste 0.4.0)

Mod de fã que adiciona co-op online ao Batman: Arkham Knight da Steam, para até 4 jogadores. Cada um joga no
próprio PC, com a própria câmera e o próprio HUD, e vê os amigos andando, lutando e planando no mesmo mundo.
Tudo é feito **dentro do jogo**, no menu **MULTIPLAYER**: criar a sala, convidar pela Steam, entrar, escolher o
personagem e a skin. O instalador só instala o mod.

Projeto de fã, sem ligação com a Warner Bros. Games, a Rocksteady ou a DC. Você precisa ter o jogo na Steam.

## Baixar

Baixe o **`ak_coop_instalador_0.4.0.exe`** na página **[Releases](../../releases/latest)**. Todos os jogadores
precisam da **mesma versão**.

## O que você precisa

- Batman: Arkham Knight na Steam, atualizado (testado na build 13250859; o instalador avisa se a sua for diferente).
- A Steam aberta e logada na sua conta.

## Instalar (uma vez, e de novo só quando sair uma versão nova)

1. Feche o jogo.
2. Rode o `ak_coop_instalador_0.4.0.exe`. O Windows pode avisar "O Windows protegeu o computador": clique em
   **Mais informações** e depois em **Executar assim mesmo** (o aviso aparece porque o programa não tem
   assinatura digital paga). Se o antivírus bloquear, libere o arquivo.
3. Clique em **INSTALAR TUDO**. Quando aparecer "Tudo instalado", feche o instalador. Ele **não** precisa ficar
   aberto.

## Jogar (tudo dentro do jogo)

Abra o jogo pela Steam, normal, e no menu principal entre em **MULTIPLAYER**.

**Quem recebe os amigos (anfitrião, sempre o Batman)**

1. **HOSPEDAR PARTIDA**: a sua sala é criada (até 4 jogadores) e mostra quem entrou.
2. **CONVIDAR AMIGO (STEAM)**: abre a lista de amigos da Steam para convidar.
3. **ESCOLHER SKIN DO BATMAN**, se quiser.
4. Com todos na sala, **COMEÇAR PARTIDA**: todos vão para o seu mundo.

**Quem entra (convidado)**

1. Aceite o convite pela Steam, ou entre em **ENTRAR EM PARTIDA** e clique na sala do amigo.
2. **ESCOLHER PERSONAGEM E SKIN**: escolha com as setas (Batman, Robin, Asa Noturna, Mulher-Gato, Azrael e, com
   as DLCs, Batgirl, Arlequina e Capuz Vermelho).
3. Espere o anfitrião começar: você carrega o mundo dele e vira o personagem escolhido. O seu próprio save
   **nunca** é tocado enquanto você joga no mundo do anfitrião.

## Durante o jogo

- No menu de pausa, **STATUS MULTIPLAYER** mostra quem está conectado e o ping de cada um.
- Se o personagem cair no limbo, use **DESBUGAR PERSONAGEM** nesse mesmo menu.
- O nome Steam de cada amigo aparece em cima dele.
- Enquanto estão conectados, todos ficam **imortais** (para evitar mortes à toa, que passam por tela de
  carregamento).
- **Não** troque de janela (Alt+Tab) nem minimize: o jogo pausa quando perde o foco, e os seus amigos veem você
  parado.

## Limites desta versão

- Os inimigos e as missões ainda **não** são compartilhados: cada um vê os bandidos do próprio jogo.
- Só o anfitrião avança a história e salva.
- Quem não tiver uma skin (DLC) vê aquele amigo com a skin padrão do personagem.
- Esta é a primeira versão com tudo dentro do jogo. Ela foi testada num PC só; o teste entre dois PCs é o
  próximo passo.

## O que mudou na 0.4.0

- Tudo dentro do jogo: menu **MULTIPLAYER** com **HOSPEDAR PARTIDA** e **ENTRAR EM PARTIDA**, convites pela Steam,
  sem códigos e sem launcher aberto. A conexão usa a própria Steam do jogo.
- Até **4 jogadores**.
- Escolha de **personagem e skin** com setas; cada um vê a skin dos outros.
- Nome Steam em cima de cada amigo.
- Tela de carregamento própria enquanto o convidado vai para o mundo do anfitrião.
- O launcher virou só um **instalador** (botão **INSTALAR TUDO**).

## Se algo der errado

Abra o instalador e clique em **JUNTAR LOGS**. Ele cria um arquivo `.zip` e abre a pasta com ele. Abra uma
[issue](../../issues) e anexe o `.zip`.

## Créditos

- [BmSDK-AK](https://github.com/Team-BmSDK/BmSDK-AK), licença MIT, Copyright (c) 2026 Eli Kramer. Vai embutido
  no instalador.
