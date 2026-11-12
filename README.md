# AtendeMais — Landing page

Versão com identidade visual oficial: A+, azul-marinho, azul e laranja.

## Publicação
1. Extraia este ZIP.
2. Envie index.html, vercel.json e README.md para a raiz do repositório GitHub (não envie o ZIP).
3. Importe o repositório na Vercel como site estático (Framework Preset: Other).
4. Não é necessário instalar dependências nem executar build. A saída é a raiz do projeto.
5. Faça o deploy e teste a página no endereço gerado.
6. Adicione o domínio desejado no projeto Vercel. Envie ao responsável pelo DNS os registros exibidos pela Vercel; os valores dependem do domínio configurado.

## Status do formulário
O formulário possui qualificação e validação, mas ainda está sem integração de recebimento de leads.
Sem endpoint, exibe indisponibilidade temporária e não transmite nem registra dados. Não ativar campanhas antes da integração e do teste de recebimento.
Talkify Analytics, webhook, GTM e Meta Pixel ainda não estão instalados.
A configuração ATENDEMAIS_CONFIG.leadEndpoint está vazia por intenção. A próxima atualização deverá adequar o envio ao contrato real do webhook Talkify e validar CORS, resposta e evento de sucesso.
O evento demo_request_success só é disparado após resposta HTTP bem-sucedida do endpoint configurado.

## Arquivos
- index.html: HTML, CSS e JavaScript da LP, em arquivo único.
- vercel.json: configuração estática sem build.
- README.md: estas instruções.

A fonte Plus Jakarta Sans é carregada pelo Google Fonts. O restante da página não depende de bibliotecas externas. A interface ilustrativa usa dados fictícios e está identificada como tal.

## Atualizações
Após conectar GitHub e Vercel, substitua os arquivos no mesmo repositório. O deploy automático depende da integração Git estar habilitada no projeto.
