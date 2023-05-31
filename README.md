# Pipeline-Dados-Telegram
Este projeto é um fluxo completo de análise de dados, indo desde a coleta de dados crus até a análise dos dados tratados.As etapas deste fluxo ou pipeline são: 

 - Captura de dados com o aplicativo Telegram, que permite a criação de *bots* que automaticamente interagem com usuários;
 - Programar as mensagens do *bot* com AWS Lambda e enviá-las ao para um *bucket* no AWS S3;
 - Utilizar outra função do AWS Lambda para ler os dados crus, processa-los e envia-los para outro *bucket* no AWS S3;
 - Gerar tabelas SQL com os dados e realizar análises com AWS Athena.
