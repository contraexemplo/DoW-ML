# Erros persistentes no wiki.tainacan.org
## Perda de dados na sessão
### Mensagem de erro:
> Pedimos desculpas, mas não foi possível processar a sua edição devido à perda de dados da sua sessão. Por favor, verifique se você ainda está autenticado e tente novamente. Caso continue não funcionando, tente sair e voltar a entrar na sua conta, e cheque se seu navegador permite cookies desse site.
### Instruções para reprodução do erro
1. Acesse qualquer página, e edite-a.
2. Clique em "Mostrar previsão".
3. Submeta a sua edição.
4. A submissão será impedida pela mensagem de erro.

Em algumas ocasiões, no entanto, a criação de páginas ou a edição delas será impedida pelo mesmo erro ainda que não se tenha requisitado a exibição da pré-visualização.
### Processo de debugging
Realizado conforme instruções descritas [na documentação do MediaWiki](https://www.mediawiki.org/wiki/Manual:How_to_debug/Login_problems).
### Procedimentos realizados e seus resultados
Limpou-se os dados do site e cookies no navegador em uso, Firefox Quantum 66.0.2 (64-bit), instalado no Ubuntu 18.10. Não houve mudança nos resultados; a mensagem de erro continua a surgir.
