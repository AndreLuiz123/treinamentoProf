Tutorial Git - Treinamento Profissional

O que é Git e para que ele serve?

Git é um sistema de controle de versão, ou seja, um sistema que permite o gerenciamento das modificações feitas em um arquivo ou conjunto de arquivos ao longo do tempo.  Esse tipo de ferramenta permite mais organização, velocidade e fluidez no andamento de projetos em equipe, dado que cada participante do projeto faz sua parte independente de seus colegas.

Um sistema de controle de versão funciona baseado em Estações de Trabalho e um Repositório. As estações de trabalho são os locais onde cada membro da equipe trabalha, ao passo que o repositório é onde as modificações feitas no projeto são concentradas.

O Git se diferencia dos outros Sistemas de controle de versão por dois motivos:
---------------------------------------------------------------------------------------------------------------------------------
1-Ao contrario de outros Sistemas de Controle de Versão, o Git é do tipo Distribuido:

  A maioria dos Sistemas de Controle de Versão são do tipo Concentrados. Isso quer dizer que as modificações feitas no projeto são concentradas apenas no repositório e as estações de trabalho só possuem acesso às modificações feitas nelas mesmas. Um Sistema de Controle de Versão Distribuido permite que não só o repositório, mas também as estações de trabalho, tenham acesso a todas as modificações feitas no projeto.

2-A forma como se trabalha em um projeto através do Git:

  O Git possui três estágios, o Working Directory, a Staging Area e o Git Directory.

   O Working Directory é o diretório onde se esta trabalhando. Nesse estágio que são feitas as modificações propriamente ditas no projeto.

   A Staging Area é o "local" onde as modificações feitas no Working Directory ficam antes de serem enviadas para o Repositório. É como se fosse uma sala de espera dessas modificações.

   O Git Directory é o destino final do projeto, o repositório. ------------------------------------------------------------------------------------------------------------------------------

 Ok, agora tendo em mente o motivo de o Git ser importante e como ele funciona, é necessário saber como utiliza-lo. Para isso, vá ao site

  http://git-scm.com

   e clique em "Downloads". Baixe a versão do sistema mais adequada ao seu computador.


  Como usar o Git?

O sistema baixado no site http://git-scm.com permite o uso dessa ferramenta através do terminal. Para iniciar o trabalho, abra o git bash(pode ser através do botão direito do mouse, procurando no seu sistema, etc...). Abrindo o git bash, haverá sempre o nome de usuário @ nome da sua máquina, seguido da localização.

 exemplo:

  fulano@beltrano1cak331 documentos/estudos/git

Para iniciar seu projeto com Git, é necessário primeiro entrar na pasta que você irá trabalhar. Para isso, digite

cd nome da pasta

O git se encaminhará para a referida pasta.

Após isso, através do comando "git init" é criado um repositório na pasta que esta sendo trabalhada para o git. Essa criação de repositório pode ser confirmada com a pasta .git que aparecerá na localização onde foi digitado "git init".

É interessante notar que, ao lado do "nome de usuário @ nome da sua máquina, seguido da localização" haverá um "(master)"

exemplo:

  fulano@beltrano1cak331 documentos/estudos/git (master)

Isso indica que o
