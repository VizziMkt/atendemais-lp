# AtendeMais — LP com Talkify

Substitua index.html no mesmo repositório GitHub. A configuração vercel.json permanece igual. Aguarde o deploy automático na Vercel.

Incluído:
- Talkify Analytics no head, com o identificador fornecido.
- POST JSON ao webhook do workspace fornecido.
- Nome, telefone normalizado, e-mail, provedor, ERP, equipe e desafio.
- Resumo da qualificação em notes, campos originais e parâmetros UTM, fbclid e gclid.
- Bloqueio de envio duplicado enquanto a requisição está em andamento.
- Confirmação após resposta bem-sucedida; erros preservam os campos.
- Evento dataLayer demo_request_success após sucesso, sem dados pessoais.

Validação: contrato mínimo consultado no endpoint (nome e telefone obrigatórios); cenários locais de sucesso e falha testados. Nenhum lead de teste foi criado na conta.
Após publicar, confirme um envio real e a visualização dos campos de qualificação no Talkify; a retenção de campos adicionais depende do mapeamento do serviço. Confirme também a visita no Analytics (bloqueadores de rastreamento podem impedir o carregamento).
Não foram adicionados GTM ou Meta Pixel.
