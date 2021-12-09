# Ransomware_Excel
Ransomware criado em Excel para mostrar o risco de deixar a execução de macros ativada.

## Histórico
| Versão | Data     | Descrição                                 |
| ------ | -------- | ------------------------------------------|
| 1.0    | 02/11/17 | Versão Inicial.                           |
| 2.0    | 22/02/18 | Realizado ajustes no script.              |
| 2.1    | 08/12/21 | Criação do manual de uso.                 |
| 2.2    | 08/12/21 | Alteração de variáveis para evasão de AV. |




[![](https://res.cloudinary.com/marcomontalbano/image/upload/v1639009471/video_to_markdown/images/youtube--sgPyjPMKbZ0-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/sgPyjPMKbZ0 "")


## O que o arquivo faz?

- Inclui senha nos arquivos do Word e Excel que estao na area de trabalho (pode ser editado para buscar em outras pastas, como Meus Documentos, etc. Tambem pode ser configurado para outros arquivos, como ppt/pptx, etc (necessario incrementar o arquivo).

![](https://l2r1.com.br/llll/rw/word.png)

![](https://l2r1.com.br/llll/rw/excel2.png)


- Gera um arquivo HTA para reverter o processo e um arquivo TXT com as instrucoes para desbloqueio.

![](https://l2r1.com.br/llll/rw/arquivos.PNG)

![](https://l2r1.com.br/llll/rw/leiame.hta.PNG)

![](https://l2r1.com.br/llll/rw/leiame.txt.PNG)

- Importante se for inserida 4 senhas incorretas no arquivo HTA, o mesmo se apagara, dificultando ainda mais a recuperacao (esta acao tem como objetivo inibir o processo de tentativas aleatorias de recuperacao

![](https://l2r1.com.br/llll/rw/senhaerrada.png)


- Ao informar a senha correta, os arquivos serão restaurados.

![](https://l2r1.com.br/llll/rw/final.png)

- Ao reverter o arquivo, um outro arquivo excel sera criado no diretorio %TMP% e uma tarefa sera criada no gerenciador de Tarefas com o nome 1ntrud3r programando a execucao do codigo em datas futuras.

![](https://l2r1.com.br/llll/rw/taskschedule.png)

- Apos a infeccao, se nada for feito os arquivos serao automaticamente recuperados em 5 dias (ao abrir novamente o hta)

### Importante:
      Este arquivo tem como objetivo orientar sobre os riscos de execucao de arquivos com macros, 
      podendo afetar Word, Excel, Powerpoint ou qualquer ser embedded em qualquer executavel causando
      um potencial estrago.
      
      O autor nao se responsabiliza pelo uso indevido desta aplicacao e recomenda o uso em ambiente 
      domestico, controlado e por pessoas habilitadas. JAMAIS utilize em um ambiente corporativo.


Bom divertimento a todos e utilizem com cuidado!

## Configuração
 - Renomeie o arquivo de new.zip.xpto para new.zip
 - Descompactar o arquivo
 - Abrir o arquivo em modo protegido
 - Editar a macro (Alt+F11)
 - Utiliza a senha acaditi para desbloqueio
 - Customize a planilha como achar melhor... (Relatório Financeiro, Vídeos eróticos, Lista de Filmes, ou qualquer outro tema que acione a curiosidade do usuário para ativar a macro)
