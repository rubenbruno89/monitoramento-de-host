# monitoramento-de-host

Este é um script em lote que verifica a disponibilidade de um endereço IP (192.168.1.131) usando o comando ping. Se o endereço estiver offline, o script envia uma notificação para ntfy.sh/monitoramento informando que o IP está fora do ar. Caso contrário, o script envia uma notificação informando que o IP está online. O comando ping é executado cinco vezes com um intervalo de 100 milissegundos entre cada tentativa. O script usa um loop infinito para continuar verificando a disponibilidade do endereço IP.
