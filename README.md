# Ransonware_Excel
Ransonware criado em Excel para mostrar o risco de deixar a execução de macros ativada.

0 - Renomeie o arquivo de new.zip.xpto para new.zip
1 - Descompactar o arquivo
2 - Abrir o arquivo em modo protegido
3 - Editar a macro (Alt+F11)
4 - Utiliza a senha acaditi para desbloqueio

O que o arquivo faz?

- Inclui senha nos arquivos do Word e Excel que estao na area de trabalho (pode ser editado para buscar em outras pastas, como Meus Documentos, etc. Tambem pode ser configurado para outros arquivos, como ppt/pptx, etc (necessario incrementar o arquivo).
- Gera um arquivo HTA para reverter o processo e um arquivo TXT com as instrucoes para desbloqueio.
   - Importante se for inserida 4 senhas incorretas no arquivo HTA, o mesmo se apagara, dificultando ainda mais a recuperacao (esta acao tem como objetivo inibir o processo de tentativas aleatorias de recuperacao
- Ao reverter o arquivo, um outro arquivo excel sera criado no diretorio %TMP% e uma tarefa sera criada no gerenciador de Tarefas com o nome 1ntrud3r programando a execucao do codigo em datas futuras.
- Apos a infeccao, se nada for feito os arquivos serao automaticamente recuperados em 5 dias (ao abrir novamente o hta)

Importante:
Este arquivo tem como objetivo orientar sobre os riscos de execucao de arquivos com macros, podendo afetar Word, Excel, Powerpoint ou qualquer ser embedded em qualquer executavel causando um potencial estrago.
O autor nao se responsabiliza pelo uso indevido desta aplicacao e recomenda o uso em ambiente domestico, controlado e por pessoas habilitadas. JAMAIS utilize em um ambiente corporativo.


Bom divertimento a todos e utilizem com cuidado!
