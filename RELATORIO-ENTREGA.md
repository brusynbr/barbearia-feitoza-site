# Relatório de entrega — Barbearia Feitoza

## Implementação

Site institucional estático em HTML, CSS e JavaScript puro, organizado para publicação direta na Vercel. A página possui cinco seções: apresentação, empresa, serviços, avaliações e contato/localização.

Dados utilizados exclusivamente a partir do arquivo de referência: Barbearia Feitoza, Rua Amazonas 567, Serrana/SP, WhatsApp `(16) 98122-3087`, serviços apresentados e avaliações do Google Maps.

## Testes executados

| Área | Resultado |
| --- | --- |
| Sintaxe do JavaScript (`node --check`) | Aprovado |
| Integridade estática de HTML, CSS e JavaScript | Aprovado |
| Links internos e âncoras | Aprovado |
| Links de WhatsApp | Aprovado com o número confirmado e mensagem codificada |
| Telefone e rota para mapa | Aprovados |
| Menu responsivo | Aprovado em viewport móvel; estado ARIA alterna corretamente |
| Acessibilidade estrutural | Aprovada: título único, hierarquia de seções, rótulos, link de pular conteúdo, foco visível e redução de movimento |
| Segurança aplicável a site estático | Aprovada: não há formulários, armazenamento de dados, `innerHTML`, `eval`, `document.write` ou dependências JavaScript externas |
| Responsividade visual | Aprovada em layout móvel |

## Pendências para confirmação do cliente

- Confirmar se nota e quantidade de avaliações do Google Maps permanecem em `5,0` e `7` antes da publicação final.
- Confirmar serviços, disponibilidade e horários de atendimento.
- Informar o perfil oficial do Instagram caso queira incluí-lo.
- Aprovar ou fornecer fotografias oficiais, se for desejada uma galeria visual.

## Publicação na Vercel

Importe a pasta do projeto e publique como site estático. Não há dependências, variáveis de ambiente ou comando de build.
