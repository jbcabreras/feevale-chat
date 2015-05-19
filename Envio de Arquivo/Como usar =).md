# COMO USAR

No seu form de chat, implemente a interface ``IFileDownloadHandler.java``.

Utilize a thread ``FileSender.java`` para enviar um arquivo.

    - hostAddress: o endereço do novo socket de envio de arquivo.
    - port: a porta do novo socket de envio de arquivo.
    - filePathToSend: o caminho do arquivo a ser enviado.
    - fileDownloadHandler: o form que implementou ``IFileDownloadHandler.java``


Utilize a thread ``FileReceiver.java`` para receber um arquivo.

    - socket: o novo socket para recebimento do arquivo.
    - fileSize: o tamanho do arquivo que está sendo enviado.
    - filePathToSave: o caminho onde deve salvar o arquivo.
    - fileDonwloadHandler: o form que implementou ``IFileDownloadHandler.java``


**Desculpe a descrição rápida, estou no trabalho e não tive tempo de detalhar =).**
