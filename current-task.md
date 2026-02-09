# Freshdesk to Docs Migration

## Goal
Migrate all documentation from Freshdesk (knowledge base) to the local Mintlify project at `docs/`.

## Phase 1: Extract HTML from Freshdesk — COMPLETE ✅

All 44 articles extracted from Freshdesk via internal API and saved as `.md` files.

## Phase 2: Convert to Mintlify MDX — COMPLETE ✅

All 44 articles converted:
- [X] Downloaded 44 images from Freshdesk S3 to `/images/`
- [X] Converted HTML to Mintlify-flavored Markdown
- [X] Added frontmatter (title) to all articles
- [X] Replaced Freshdesk image URLs with local `/images/img-{id}.{ext}` paths
- [X] Replaced Freshdesk article links with local doc paths
- [X] Used Mintlify components: `<Note>`, `<Tip>`, `<Warning>` for blockquotes
- [X] Converted tables to Markdown tables
- [X] Stripped all inline styles and HTML attributes
- [X] Zero remaining Freshdesk URLs

### Articles (44 total)

#### Primeiros passos > Visão geral (3)
- [X] Boas Vindas → `primeiros-passos/visao-geral/boas-vindas.md`
- [X] Visão geral → `primeiros-passos/visao-geral/visao-geral.md`
- [X] Aplicativo e celular → `primeiros-passos/visao-geral/aplicativo-e-celular.md`

#### Contas a pagar e receber > Contas a pagar e receber (4)
- [X] Contas a pagar e a receber → `contas-a-pagar-e-receber/contas-a-pagar-e-receber/contas-a-pagar-e-a-receber.md`
- [X] Realizar baixa com valores realizados → `contas-a-pagar-e-receber/contas-a-pagar-e-receber/realizar-baixa-com-valores-realizados.md`
- [X] Lista de contas → `contas-a-pagar-e-receber/contas-a-pagar-e-receber/lista-de-contas.md`
- [X] Anexos de contas → `contas-a-pagar-e-receber/contas-a-pagar-e-receber/anexos-de-contas.md`

#### Contas a pagar e receber > Contas recorrentes (3)
- [X] Cadastrar contas recorrentes → `contas-a-pagar-e-receber/contas-recorrentes/cadastrar-contas-recorrentes.md`
- [X] Editar conta recorrente → `contas-a-pagar-e-receber/contas-recorrentes/editar-conta-recorrente.md`
- [X] Deletar conta recorrente → `contas-a-pagar-e-receber/contas-recorrentes/deletar-conta-recorrente.md`

#### Contas a pagar e receber > Contas parceladas (1)
- [X] Contas parceladas → `contas-a-pagar-e-receber/contas-parceladas/contas-parceladas.md`

#### Contas a pagar e receber > Opções avançadas (4)
- [X] Salvar para Excel → `contas-a-pagar-e-receber/opcoes-avancadas/salvar-para-excel.md`
- [X] Bloqueio mensal de contas → `contas-a-pagar-e-receber/opcoes-avancadas/bloqueio-mensal-de-contas.md`
- [X] Categorias de Contas → `contas-a-pagar-e-receber/opcoes-avancadas/categorias-de-contas.md`
- [X] Usando os recursos de auditoria → `contas-a-pagar-e-receber/opcoes-avancadas/usando-os-recursos-de-auditoria.md`

#### Contas a pagar e receber > Envio de cobrança PIX e Recibos (2)
- [X] Envio de cobrança por PIX ou Dados Bancários → `contas-a-pagar-e-receber/envio-de-cobranca-pix-e-recibos/envio-de-cobranca-por-pix-ou-dados-bancarios.md`
- [X] Gerar e enviar recibos por e-mail → `contas-a-pagar-e-receber/envio-de-cobranca-pix-e-recibos/gerar-e-enviar-recibos-por-e-mail.md`

#### Contratos > Contratos (2)
- [X] Cadastrar Contrato → `contratos/contratos/cadastrar-contrato.md`
- [X] Receber parcela relacionada a contrato → `contratos/contratos/receber-parcela-relacionada-a-contrato.md`

#### Clientes e Fornecedores > Clientes e Fornecedores (1)
- [X] Integração com WhatsApp → `clientes-e-fornecedores/clientes-e-fornecedores/integracao-com-whatsapp.md`

#### Usuários e Permissões > Usuários e Permissões (4)
- [X] Alterar sua senha → `usuarios-e-permissoes/usuarios-e-permissoes/alterar-sua-senha.md`
- [X] Cadastrar novos usuários → `usuarios-e-permissoes/usuarios-e-permissoes/cadastrar-novos-usuarios.md`
- [X] Permissões de usuários → `usuarios-e-permissoes/usuarios-e-permissoes/permissoes-de-usuarios.md`
- [X] Como Recuperar sua senha → `usuarios-e-permissoes/usuarios-e-permissoes/como-recuperar-sua-senha.md`

#### Dashboard e Relatórios > Dashboard e Relatórios (4)
- [X] Dashboard → `dashboard-e-relatorios/dashboard-e-relatorios/dashboard.md`
- [X] Relatório de Fluxo de caixa → `dashboard-e-relatorios/dashboard-e-relatorios/relatorio-de-fluxo-de-caixa.md`
- [X] Calendário de contas → `dashboard-e-relatorios/dashboard-e-relatorios/calendario-de-contas.md`
- [X] Relatório resultado anual → `dashboard-e-relatorios/dashboard-e-relatorios/relatorio-resultado-anual.md`

#### Financeiro > Financeiro (3)
- [X] Como realizar a assinatura → `financeiro/financeiro/como-realizar-a-assinatura.md`
- [X] O que acontece se eu atrasar o pagamento → `financeiro/financeiro/o-que-acontece-se-eu-atrasar-o-pagamento.md`
- [X] Como cancelar a assinatura → `financeiro/financeiro/como-cancelar-a-assinatura.md`

#### FAQs > Perguntas frequentes (4)
- [X] Esqueci minha senha → `faqs/perguntas-frequentes/esqueci-minha-senha.md`
- [X] Problema com certificado → `faqs/perguntas-frequentes/problema-com-certificado.md`
- [X] Como reportar um erro no sistema → `faqs/perguntas-frequentes/como-reportar-um-erro-no-sistema.md`
- [X] Resolvendo problema de datas → `faqs/perguntas-frequentes/resolvendo-problema-de-datas.md`

#### Internal > Gifts (2)
- [X] Gift vouchers for birthdays → `internal/gifts/gift-vouchers-for-birthdays.md`
- [X] Gift vouchers for anniversaries → `internal/gifts/gift-vouchers-for-anniversaries.md`

#### Internal > Coupons (2)
- [X] Coupons for members → `internal/coupons/coupons-for-members.md`
- [X] Coupons for non-members → `internal/coupons/coupons-for-non-members.md`

#### Internal > Internal (3)
- [X] Convertendo mpeg to gif → `internal/internal/convertendo-mpeg-to-gif.md`
- [X] Script → `internal/internal/script.md`
- [X] Importar dados usando excel → `internal/internal/importar-dados-usando-excel.md`

#### Inteligência Artificial > Assistente Virtual (1)
- [X] Assistente Virtual → `inteligencia-artificial/assistente-virtual/assistente-virtual.md`

#### Inteligência Artificial > Importar extrato/fatura (1)
- [X] Importar extrato/fatura → `inteligencia-artificial/importar-extrato-fatura/importar-extrato-fatura.md`

## Notes
- 44 images downloaded to `/images/` (named `img-{freshdesk-attachment-id}.{ext}`)
- Mintlify components used: `<Note>`, `<Tip>`, `<Warning>` for blockquotes
- All Freshdesk S3 image URLs replaced with local paths
- All Freshdesk article cross-links replaced with local doc paths
- Some "Internal" articles (Gifts, Coupons) have empty content — placeholder articles in Freshdesk
