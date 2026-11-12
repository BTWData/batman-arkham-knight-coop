# Batman: Arkham Knight — co-op online (versão de teste 0.3.3)

Mod de fã que adiciona co-op online para 2 jogadores ao Batman: Arkham Knight da Steam. O anfitrião joga de Batman e
o convidado de Robin, cada um no próprio PC, com a própria câmera e o próprio HUD. O launcher traz tudo dentro dele:
instala o mod sozinho e liga os dois PCs pela rede da Steam.

Projeto de fã, sem ligação com a Warner Bros. Games, a Rocksteady ou a DC. Você precisa ter o jogo na Steam.

## Baixar

Baixe o **`ak_coop_launcher_0.3.3.exe`** na página **[Releases](../../releases/latest)**. Os dois jogadores precisam
da **mesma versão**.

## O que você precisa

- Batman: Arkham Knight na Steam, atualizado (testado na build 13250859; o launcher avisa se a sua for diferente).
- A Steam aberta e logada na sua conta.
- Teclado e mouse ou controle, os dois servem.

## Abrir o launcher

1. Rode o `ak_coop_launcher_0.3.3.exe`.
2. O Windows pode avisar "O Windows protegeu o computador". Clique em **Mais informações** e depois em **Executar
   assim mesmo** (o aviso aparece porque o programa não tem assinatura digital paga).
3. Se o antivírus bloquear, libere o arquivo.
4. Veja a lista **VERIFICAÇÃO**: tudo deve ficar com o sinal de certo. Se algo der errado, clique em
   **INSTALAR / REPARAR**. Se o jogo não for achado, use **BUSCAR AUTOMÁTICO** ou **ESCOLHER MANUALMENTE**.

## Trocar os códigos (uma vez por partida)

Cada um clica em **COPIAR** no campo "SEU CÓDIGO STEAM" e manda para o outro (WhatsApp, Discord). O código é um
número de 17 dígitos.

## Quem hospeda (anfitrião = Batman)

1. Marque **Hospedar** e **Pela Steam**.
2. Cole o código do amigo em "CÓDIGO STEAM DO SEU AMIGO".
3. Clique em **JOGAR**, carregue o seu save e entre no mundo. O anfitrião entra no jogo **primeiro**.

## Quem entra (convidado = Robin)

1. Marque **Entrar** e **Pela Steam**.
2. Cole o código do anfitrião em "CÓDIGO STEAM DO ANFITRIÃO".
3. Espere o anfitrião já estar no mundo, clique em **JOGAR** e carregue qualquer save.
4. Uns segundos depois de entrar no mundo você vira o Robin, ao lado do Batman do anfitrião.

## Durante o jogo

- A conexão começa sozinha, não precisa apertar nada.
- Deixe o launcher **aberto** enquanto jogam (ele é a ponte com o amigo).
- Joguem perto um do outro.
- **Não** troque de janela (Alt+Tab) nem minimize: o jogo pausa quando perde o foco, e o seu amigo vê você parado.

## Se não conectar

- Um escolhe **Hospedar** e o outro **Entrar** (nunca os dois iguais).
- Cada um cola o código do **outro**, não o próprio.
- Embaixo do botão JOGAR aparece a "Ponte Steam": depois de 1 minuto sem nada chegar, ela diz o que conferir.
- O convidado pode entrar antes ou depois do anfitrião: ele tenta conectar de novo sozinho.

## Limites desta versão

- Os inimigos e as missões ainda **não** são compartilhados: cada um vê os bandidos do próprio jogo.
- Só o Batman (anfitrião) chama o Batmóvel.
- Só 2 jogadores por enquanto.
- Reiniciar pelo menu ou morrer passa por uma tela de carregamento; o Robin volta sozinho alguns segundos depois.
- Ainda não testado entre dois PCs de verdade: a conexão pela Steam entre duas contas e o teclado e mouse do
  convidado. Esta versão serve justamente para esse teste.

## Se algo der errado

No launcher, clique em **JUNTAR LOGS**. Ele cria um arquivo `.zip` e abre a pasta com ele. Abra uma
[issue](../../issues) e anexe o `.zip`.

## Créditos

- [BmSDK-AK](https://github.com/Team-BmSDK/BmSDK-AK), licença MIT, Copyright (c) 2026 Eli Kramer. Vai embutido no
  launcher.
- `steam_api64.dll`, da Valve (Steamworks), tirada do [Steamworks.NET](https://github.com/rlabrecque/Steamworks.NET).
