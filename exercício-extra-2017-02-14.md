# Apache HTTP Server 2.3/2.4
#
# MPMs de carga em tempo de execução
# Múltiplos MPMs agora podem ser criados como módulos carregáveis em tempo de compilação. O MPM de escolha pode ser configurado em tempo de execução via LoadModulediretiva.
# Evento MPM
# O Event MPM não é mais experimental, mas agora é totalmente suportado.
# Suporte assíncrono
# Melhor suporte para leitura / gravação assíncrona para suporte de MPMs e plataformas.
# Configuração LogLevel por módulo e por diretório
# O LogLevelagora pode ser configurado por módulo e por diretório. Novos níveis trace1 de trace8foram adicionados acima do debugnível de log.
# Seções de configuração por solicitação
# <If>, <ElseIf>E as <Else> seções podem ser usadas para configurar a configuração com base em critérios por solicitação.
# Analisador de expressão de propósito geral
# Um novo analisador de expressão permite especificar condições complexas usando uma sintaxe comum em directivas como SetEnvIfExpr, RewriteCond, Header, <If>, e outros.
# KeepAliveTimeout em milissegundos
# Agora é possível especificar KeepAliveTimeoutem milissegundos.
# Diretriz NameVirtualHost
# Não é mais necessário e agora está obsoleto.
# Substituir a Configuração
# A nova AllowOverrideList diretiva permite um controle mais fino que as diretivas são permitidas nos .htaccess arquivos.
# Variáveis do arquivo de configuração
# Agora é possível definir variáveis na configuração, permitindo uma representação mais clara se o mesmo valor for usado em muitos lugares na configuração.
# Redução de uso de memória
# Apesar de muitos novos recursos, 2.4 tende a usar menos memória do que 2.2.
#
# NGINX 1.13.3/1.13.4
#
# Mudanças com nginx 1.13.4 de 08 de agosto de 2017
# Característica: o ngx_http_mirror_module.
# Bugfix: as conexões do cliente podem ser descartadas durante a configuração
# Teste ao usar o parâmetro "reuseport" do "listen"
# Diretiva no Linux.
# Bugfix: o corpo do pedido pode não estar disponível nas subsequências se fosse
# Salvo em um arquivo e o proxy foi usado.
# Bugfix: o cache de limpeza com base no parâmetro "max_size" não funcionou
# No Windows.
# Bugfix: qualquer alocação de memória compartilhada exigiu 4096 bytes no Windows.
# Bugfix: o trabalhador nginx pode ser encerrado de forma anormal ao usar o
# Diretiva de "zona" dentro do bloco "upstream" no Windows.
#
# WordPress 4.8/4.8.1
#
#Esta nova versão contém 29 reparos de manutenção e aprimoramentos, o principal entre eles são correções para o widget rich Text e a introdução do widget HTML personalizado
