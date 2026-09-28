# semana16modelagem


aula 3

Atomicidade: Significa que uma operação na base de dados acontece toda de uma vez ou não acontece. Se der algum erro no meio, tudo volta ao estado anterior.

Consistência: Significa que os dados da base de dados têm de continuar corretos e de acordo com as regras definidas, antes e depois de uma operação.

Isolamento: Significa que várias operações podem acontecer ao mesmo tempo sem uma interferir de forma errada com a outra. Cada operação funciona como se estivesse sozinha.

Durabilidade: Significa que, depois de uma operação ser concluída e guardada, os dados não se perdem, mesmo que o sistema vá abaixo ou falte a luz.

4.1
As transações e o ACID ajudam a manter os dados corretos e seguros. Num e-commerce, isso é importante para evitar erros em pagamentos, stock e pedidos.

4.2
O ROLLBACK serve para desfazer as alterações quando acontece um erro, deixando os dados como estavam antes.

4.3
O COMMIT confirma e guarda as alterações da transação. Assim, os dados ficam guardados de forma permanente.
