Documentação de Comandos - Orion RolePlay
Esta documentação lista todos os comandos disponíveis no servidor Orion RolePlay, separados por categorias. Cada comando é descrito com base em seu nome e função no servidor.

Índice
Comandos de Chat e Comunicação
Comandos de Administração
Comandos de Veículos
Comandos de Economia e Itens
Comandos Relacionados a Trabalhos (Jobs)
Comandos Relacionados a Roubo e Missões
Comandos Relacionados a NPCs e Interações com o Mundo
Comandos Relacionados a Inventário
Comandos Relacionados a Sincronização e Ambiente
Comandos de Debug e Ferramentas
Comandos de Chat e Comunicação
Esses comandos controlam a comunicação no servidor, incluindo o chat e comandos roleplay.

/toggleChat
Arquivo: cl_chat.lua
Descrição: Ativa ou desativa o chat.

/say
Arquivo: sv_chat.lua
Descrição: Envia uma mensagem no chat.

/ooc, /me, /do, /news, /ad, /twt, /anon
Arquivo: cc-rpchat\server\main.lua
Descrição: Comandos de comunicação roleplay, incluindo chat OOC e mensagens de RP.

/limpar
Arquivo: mri_Qchat\cl_chat.lua
Descrição: Limpa o chat para o jogador.

Comandos de Administração
Esses comandos são usados pelos administradores do servidor para gerenciar jogadores, teleporte, veículos, etc.

/admin
Arquivo: ps-adminmenu\server\main.lua
Descrição: Abre o menu de administrador.

/tpway, /god, /tuning, /menu_admin, /customs, /raycast
Arquivo: utilities-modules\commands.lua
Descrição: Comandos de administração para teleporte, modo deus, tunagem de veículos e outras funções.

/report, /noclip, /names, /blips, /admincar, /setmodel, /vec2, /vec3, /vec4, /heading
Arquivo: qbx_adminmenu\server\commands.lua
Descrição: Comandos para relatórios, noclip, visualização de nomes, teleporte e ajuste de coordenadas.

/openserver, /closeserver
Arquivo: qbx_core\server\commands.lua
Descrição: Comandos para abrir ou fechar o servidor para novos jogadores.

Comandos de Veículos
Esses comandos controlam diferentes aspectos do comportamento dos veículos no jogo.

/vehcontrol, /engine, /door, /seat, /window, /hood, /trunk, /vehcontrolclose
Arquivo: mri_Qvehcontrol\client.lua
Descrição: Controle de veículos, incluindo motor, portas, assentos, janelas, capô e porta-malas.

/togglelocks
Arquivo: mri_Qcarkeys\client\modules\keys.lua
Descrição: Alterna o travamento das portas do veículo.

/car, /dv
Arquivo: qbx_core\server\commands.lua
Descrição: Comandos para spawnar ou remover veículos.

/npc, /tow
Arquivo: qbx_towjob\server\main.lua
Descrição: Comandos relacionados ao trabalho de reboque de veículos.

Comandos de Economia e Itens
Comandos que manipulam dinheiro, inventário e recursos do servidor.

/earn, /spend
Arquivo: money\server.lua
Descrição: Comandos para ganhar ou gastar dinheiro.

/cash, /bank, /dev
Arquivo: mri_Qhud\server.lua
Descrição: Gerencia dinheiro em mãos e no banco.

/givemoney, /setmoney
Arquivo: qbx_core\server\commands.lua
Descrição: Dá dinheiro a um jogador ou define um valor específico.

/stackkeys, /unstackkeys
Arquivo: mri_Qcarkeys\server\commands.lua
Descrição: Comandos para manipular chaves de veículos.

Comandos Relacionados a Trabalhos (Jobs)
Comandos usados para gerenciar trabalhos e suas respectivas funcionalidades.

/addjob, /removejob, /setjob, /changejob
Arquivo: qbx_core\server\commands.lua
Descrição: Gerencia trabalhos de jogadores.

/createjob, /open_jobs
Arquivo: mri_Qjobsystem\server\server.lua
Descrição: Comandos para criar ou abrir sistemas de trabalhos no servidor.

Comandos Relacionados a Roubo e Missões
Comandos específicos para roubos e missões no servidor.

/pdfleeca
Arquivo: mri_Qfleecaheist\server.lua
Descrição: Comando relacionado ao roubo de bancos Fleeca.

/storerobbery, /liberar
Arquivo: mri_Qstorerobbery\server.lua
Descrição: Comandos relacionados a roubos de lojas.

Comandos Relacionados a NPCs e Interações com o Mundo
Esses comandos manipulam NPCs ou interagem com o ambiente do servidor.

/npc
Arquivo: mri_Qnpc\server\npc.lua
Descrição: Comando provavelmente usado para interagir ou spawnar NPCs.

/objectspawner, /objectdelete
Arquivo: mri_Qobjects\server\commands.lua
Descrição: Spawna ou remove objetos no mundo do jogo.

/waypointsettings, /clearwaypoints, /adminwaypoint
Arquivo: pickle_waypoints\modules\main
Descrição: Comandos para gerenciar waypoints no mapa.

Comandos Relacionados a Inventário
Manipulação do inventário dos jogadores e controle de evidências.

/removeitem, /setitem, /clearevidence, /viewinv, /takeinv
Arquivo: ox_inventory\server.lua
Descrição: Comandos para manipular itens e evidências no inventário dos jogadores.
Comandos Relacionados a Sincronização e Ambiente
Controla o tempo, clima e outras variáveis de ambiente no servidor.

/time, /noon, /morning, /evening, /night, /timescale, /freezetime
Arquivo: Renewed-Weathersync\server\time.lua
Descrição: Comandos para ajustar o tempo no servidor.

/weather
Arquivo: Renewed-Weathersync\server\weather.lua
Descrição: Altera o clima no servidor.

Comandos de Debug e Ferramentas
Comandos utilizados para testes e depuração.

/record, /clip, /saveclip, /delclip, /editor
Arquivo: qbx_editor\client.lua
Descrição: Ferramentas relacionadas à gravação e edição de clips.

/run, /crun, /runcode
Arquivo: runcode\runcode_sv.lua
Descrição: Comandos para executar código remotamente no servidor.

Como Publicar no GitHub
Criar um Arquivo README.md: No seu repositório GitHub, crie ou edite o arquivo README.md.
Copiar e Colar o Conteúdo: Cole o conteúdo que organizei acima diretamente no arquivo
