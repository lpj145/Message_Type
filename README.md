# Message_Type
Este é uma especificação interna de mensagens de trocas (WampV2)


Uma mensagem é composta por:

`channel` string - Canal onde a mensagem será publicada.

`payload` array - conteúdo da mensagem.

`type` string - que indique que tipo de pacote é aquele.

`code` int - 200 - OK ou 400 - ERROR.

`action` string - que ação os escritos devem tomar com aquela mensagem.

`meta` array - em caso de comentários adicionais, ou informações que possam serem uteis, ou de uso futuro.

