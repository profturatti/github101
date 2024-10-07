# GITHUB 101: Desvendando o versionamento na prática

## O que é o controle de versão?

O controle de versão de um software é o gerenciamento das mudanças do código fonte de um programa.

No início do controle de projetos, os desenvolvedores não tinham acesso a um sistema de controle de versão e, assim, trabalhavam com uma única pessoa que possuía a versão principal do código e essa pessoa só compartilhava a parte específica em que fosse necessária alterações ou atualizações. Somente quando um desenvolvedor retornava o código finalizado é que o trabalho era então verificado quanto a padrões, assertividade e então o novo código substituía a versão antiga pelo novo conteúdo.

Somente em 1972 é que esse fluxo começou a mudar, quando o desenvolvedor Marc Rochkind resolveu que não conseguia mais lidar com isso e criou o Sistema de Controle de Código Fonte (Source Code Control System, SCCS), o primeiro sistema de controle de versão.

As gerações seguintes trouxeram outras ferramentas para sistemas de controle de versão (VCS), tais como RCS (Revision Control System), CVS (Concurrent Versions System), GIT, entre outras [1].

## Versionamento Semântico

O versionamento semântico, quando realizado de forma correta, ajuda os usuários a entenderem o estágio em que a aplicação está. Em desenvolvimento de software, nós versionamos aplicações seguindo o Versionamento Semântico (Semantic Versioning), o que nada mais é que um modelo geral em que todos usuários possam entender [2].

## Regras do versionamento

O versionamento semântico propõe um conjunto simples de regras de como os números das versões são atribuídos e incrementados.

Considere o formato de versão X.Y.Z (Major.Minor.Patch, ou seja, Maior, Menor, e Correção, respectivamente). Os valores de X, Y, e Z são números inteiros não negativos. Cada elemento deve ser incrementado em 1. Por exemplo: 1.9.0 -> 1.10.0 -> 1.11.0.

Verificando a versão do git instalado em seu computador, como exemplo:

> git --version
git version 2.46.2

Essa informação é referente a versão mais atual disponível durante a redação deste material.

Para cada lançamento do software, ele deve ter um número único da versão e, uma vez lançado, o código dessa versão não pode mais ser alterado. Qualquer necessidade de alteração no software, ele deverá ser lançado com um novo número de versão.


## O que é GIT?

Git é um sistema de controle de versões distribuído, usado principalmente no desenvolvimento de software. Foi inicialmente projetado e desenvolvido por Linux Torvalds para o desenvolvimento do Kernel do Linux e posteriormente utilizado para registrar o histórico de edições de qualquer tipo de arquivo [3].

Aqui podemos mencionar o compartilhamento de materiais didáticos até o controle de notas de aula ou indo além, como para a distribuição de outros materiais digitais como livros (que podem ser mantidos, revisados e ampliados a qualquer momento). O controle sobre os conteúdos pode ser feito de forma pública (mais comum) como também de forma privada (compartilhamento de projetos em empresas, por exemplo).

Nosso material se limitará a explicar o uso de conteúdos públicos para fins didáticos.

## O que é GITHUB?

GitHub é uma plataforma de hospedagem de código-fonte [4] e arquivos com controle de versão usando o Git. Ele permite que pessoas cadastradas na plataforma contribuam em projetos de qualquer lugar do mundo.

Foi desenvolvido por Chris Wanstrath, J. Hyett, Tom Preston-Werner e Scott Chacon usando Ruby on Rails. A empresa, GitHub, Inc., surgiu em 2007 e está localizada em São Francisco. Desde então atraiu até 2013 cerca de 3 milhões de usuários alcançando na época 10 milhões de repositórios. Em 2015 captou aproximadamente 250 milhões de dólares americanos e valorizou para cerca de 2 bilhões de dólares. Em 2016 ficou em 14º lugar na lista Forbes Cloud 100. Tal sucesso chamou a atenção de investidores e em 2018 foi adquirida pela Microsoft por 7.5 bilhões de dólares. Desde então vem trazendo novidades e alcançando mais pessoas como através do GitHub Education (destinado para escolas), assim como a ferramenta de inteligência artificial, o GitHub CoPilot (desenvolvida pela OpenAI).

## Git e Github são a mesma coisa?

Não! O git e GitHub não são a mesma coisa. Git é uma ferramenta de controle de versão de código aberto criada em 2005 por desenvolvedores que trabalham no sistema operacional Linux; GitHub é uma empresa fundada em 2007 que faz ferramentas que se integram com git. Você não precisa do GitHub para usar git, mas não pode usar GitHub sem usar git. Existem muitas outras alternativas ao GitHub, como GitLab, BitBucket e soluções para hospedagem própria de um gerenciador de versões, como gogs e gittea. Todos eles são chamados na linguagem git de "remotos", e todos são completamente opcionais. Você não precisa usar um remoto para usar git, mas isso tornará o compartilhamento do seu código com outras pessoas mais fácil.


## Criando uma conta no github

## Usando github com navegador

## Instalando a ferramenta no Windows

## Pratica com CLI

## Referências
[1] Comparação de software de controle de versão
https://en.wikipedia.org/wiki/Comparison_of_version-control_software

[2] Versionamento Semântico
https://zup.com.br/blog/versionamento-semantico

[3] Git é um sistema de controle de versão distribuído, gratuito e de código aberto
https://git-scm.com/

[4] Github
https://github.com


