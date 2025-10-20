Caso de Uso – RF1: Leitura biométrica para registro de presença

Ator principal: Docente

Objetivo: Registrar presença de forma automática via leitura biométrica.

Descrição: O sistema permite que o docente registre sua presença utilizando a biometria digital.

Fluxo principal:

O docente acessa o leitor biométrico.

O sistema solicita a leitura digital.

O docente posiciona o dedo no leitor.

O sistema valida a biometria e registra a presença.

O sistema confirma o registro com uma imagem (✅).

Fluxo alternativo:

Se a leitura falhar, o sistema solicita nova tentativa.

O sistema também retorna uma imagem de erro (❌)

____________________________________________________________________

Caso de Uso – RF2: Acesso ao sistema por meio de aplicativo mobile

Ator principal: Discente e Docente

Objetivo: Permitir o acesso ao sistema via aplicativo móvel.

Descrição: Usuários podem acessar o sistema por um app no celular.

Fluxo principal:

O usuário abre o aplicativo.

Insere suas credenciais (login e senha).

O sistema valida os dados e libera o acesso.

O usuário navega pelas funções disponíveis.

Fluxo alternativo:

Se as credenciais forem inválidas, o sistema exibe uma mensagem de erro (Tente Novamente 🌀).

____________________________________________________________________

Caso de Uso – RF3: Função de localização do docente

Ator principal: Discente

Objetivo: Permitir que os alunos visualizem a localização do professor.

Descrição: O sistema mostra a localização atual do docente dentro do campus.

Fluxo principal:

O aluno acessa o aplicativo.

Seleciona “Localizar docente”.

O sistema exibe a posição do professor (sala).

Fluxo alternativo:

Caso o docente não esteja disponível, o sistema informa “Localização indisponível”.

____________________________________________________________________

Caso de Uso – RF4: Sistema de avisos e notificações

Ator principal: Docente e Discente

Objetivo: Enviar e receber avisos e notificações do sistema.

Descrição: O sistema notifica usuários sobre eventos, avisos de aula ou mensagens administrativas.

Fluxo principal:

O docente cria um aviso no sistema.

O sistema envia notificações aos alunos.

O aluno visualiza a notificação no aplicativo.

Fluxo alternativo:

Se o aviso não puder ser entregue, o sistema registra a falha e mensagem de erro (Mensagem NÃO entregue 📭).

____________________________________________________________________
 
Caso de Uso – RF5: Instalação do software pelos discentes

Ator principal: Discente

Objetivo: Permitir que os alunos instalem o software em seus dispositivos.

Descrição: O sistema disponibiliza um instalador simples para os alunos.

Fluxo principal:

O aluno acessa o site do sistema.

Faz o download do instalador.

Executa a instalação seguindo o assistente.

O sistema confirma a instalação bem-sucedida.

Fluxo alternativo:

Em caso de erro, o sistema exibe mensagem para seguir as instruções do suporte (Acesse o link de suporte 🔗).

____________________________________________________________________

Caso de Uso – RF6: Acompanhamento de presença

Ator principal: Docente e Discente

Objetivo: Permitir o acompanhamento da frequência dos Docentes.

Descrição: O sistema exibe a presença dos docentes no dia.

Fluxo principal:

O docente/discente acessa o menu “Acompanhamento de presença”.

O sistema mostra a lista de docentes presentes.

____________________________________________________________________
 
Caso de Uso – RF7: Cadastro e gerenciamento de docentes

Ator principal: Administrador e Docente

Objetivo: Cadastrar, editar ou remover dados de docentes.

Descrição: O sistema permite o docente gerenciar informações dos discentes da instituição.

Fluxo principal:

O docente/administrador acessa o módulo de discentes.

Escolhe alterar informações do discente.

Altera os dados (Nota, Mensagens enviadas, etc).

O sistema grava as novas informações.

Fluxo alternativo:

Caso algum dado seja inválido, o sistema solicita correção (Dado inválido. Tente novamente ❌🌀).

____________________________________________________________________

Caso de Uso – RF8: Gerenciamento de turmas

Ator principal: Administrador e Docente

Objetivo: Criar e administrar turmas no sistema.

Descrição: O sistema permite que o administrador e o docente realizem o gerenciamento das turmas, podendo editá-las, alterá-las, movê-las, entre outros.

Fluxo principal:

O administrador/docente acessa o módulo “Turmas”.

Cadastra uma nova turma com nome e curso.

Adiciona alunos.

O sistema salva e exibe a turma criada.

Fluxo alternativo:

Caso algum campo esteja incompleto, o sistema impede o cadastro (Cadastro inválido 📄❌).
