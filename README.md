# WhatsPainel/WhaTicket Saas</br>
Funcionando com Baileys 6.3.0 - 17 de Junho de 2023 </br>
</br> Atualizado referencias para a bilioteca @WhiskeySockets/Baileys</br>
Modificado AnyWASocket, WALegacySocket, LegacyAuthenticationCreds</br>

Tipo de Chatbort = Somente Texto <br>
Usar o WhatsApp Bussines, não o WhatsApp <br>

Testado no WhatsApp Business 2.23.11.78 - Androi 11</br>
Recebimento e repostas ok - salvo exceções de aparelhos com app aberto, 
</br>Recomendamos o uso do whatsapp business somente para para manter a conexão ativa, sem uso simultâneo. envitar a versão normal
</br> Não é necessário estar com celular ativo e conectado a internet para receber mensagens.
Envio de mídia ok.</br>
Agendamento de mensagens ok.</br>
Importar contatos do telefone ok. </br>
Envio de campanhas ok. </br>
Download e Importação de Lista de Contatos em Campanhas. OK </br>
Criar contatos de campanha direto no painel. Ok </br>
CallBack GerenciaNet via Insomnia. OK

Midia no Chat. OK</br>
Escutar Audios OK </br>
Localização Fixa. OK - Não funciona em tempo real, mesmo na api oficial</br>

Planos Futuros:
Atualização de Material UI 4 para MUI 5
Instruções de  e Webhook Facebook (Messenger e Direct).

Bugs:
Chat Interno ao criar fila só aparece a nova no refresh da página. (intermitente)
- Esperado solução com atualização do frontend
Pode repertir o menu de sub-opção se uma resposta é invalida, ou escolher a opção e digitar a seguir
Envio para grupos em alguns servidores - avaliando que se trocar o dns do servidor resolve

Em Observação:
Tickets de Admin são fechados automaticamente na avaliação </br>
Tickets de usuários recebem a nota e só fecham e enviam disparo da mensagem de encerramento quando clica novamente em resolver.
Adcionar Módulo de Tarefas
Ao modificar gerenciamento de horários limpe as configurações anteriores primeiro.
