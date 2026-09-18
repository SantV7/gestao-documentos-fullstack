# Task Full Stack Manager

## 1. Configuração inicial

- [X] Criar estrutura `frontend` e `backend`
- [] Inicializar projeto React + TypeScript no frontend
- [X] Inicializar projeto Node.js + TypeScript no backend
- [ ] Instalar Express
- [ ] Instalar Prisma
- [ ] Instalar PostgreSQL
- [ ] Instalar React Router
- [ ] Instalar Lucide React / React Icons
- [X] Configurar `.gitignore`
- [X] Criar README inicial

## 2. Frontend — estrutura

- [ ] Criar estrutura de pastas do frontend
- [ ] Configurar React Router
- [ ] Criar página `Documents`
- [ ] Criar página `Upload`
- [ ] Criar página `DocumentDetails`
- [ ] Criar componente `Sidebar`
- [ ] Criar componente `Header`
- [ ] Criar componente `DocumentCard` / `DocumentRow`
- [ ] Criar componente `CommentList`
- [ ] Criar componente `CommentForm`
- [ ] Criar componente `FileUpload`
- [ ] Criar estados de loading
- [ ] Criar estados de erro
- [ ] Criar estados de lista vazia

## 3. Backend — configuração

- [ ] Configurar servidor Express
- [ ] Configurar TypeScript
- [ ] Configurar CORS
- [ ] Configurar middleware de JSON
- [ ] Criar estrutura de pastas do backend
- [ ] Criar pasta para arquivos enviados
- [ ] Configurar variáveis de ambiente
- [ ] Criar rota principal `/api`

## 4. Banco de dados — Prisma

- [ ] Configurar Prisma
- [ ] Conectar Prisma ao PostgreSQL
- [ ] Criar model `Document`
- [ ] Criar model `Comment`
- [ ] Criar relacionamento `Document 1:N Comment`
- [ ] Criar migration
- [ ] Testar conexão com banco
- [ ] Criar Prisma Client

## 5. Upload de documentos

- [ ] Instalar/configurar Multer
- [ ] Criar endpoint `POST /api/documents`
- [ ] Receber título
- [ ] Receber descrição opcional
- [ ] Receber arquivo
- [ ] Validar PDF/JPG/PNG
- [ ] Validar arquivo obrigatório
- [ ] Salvar arquivo localmente
- [ ] Salvar metadados no PostgreSQL
- [ ] Retornar documento criado
- [ ] Testar upload pelo Postman/Insomnia

## 6. Documentos

- [ ] Criar endpoint `GET /api/documents`
- [ ] Buscar documentos no PostgreSQL
- [ ] Retornar título
- [ ] Retornar data de upload
- [ ] Retornar informações necessárias para visualizar/baixar
- [ ] Criar endpoint para visualizar documento
- [ ] Criar endpoint para download
- [ ] Testar listagem
- [ ] Testar visualização
- [ ] Testar download

## 7. Comentários

- [ ] Criar endpoint `POST /api/documents/:id/comments`
- [ ] Receber texto do comentário
- [ ] Validar comentário vazio
- [ ] Verificar se documento existe
- [ ] Salvar comentário no PostgreSQL
- [ ] Salvar data/hora automaticamente
- [ ] Criar endpoint `GET /api/documents/:id/comments`
- [ ] Retornar comentários relacionados ao documento
- [ ] Testar criação de comentário
- [ ] Testar histórico de comentários

## 8. Frontend — Documentos

- [ ] Criar layout da página de documentos
- [ ] Buscar documentos pela API
- [ ] Mostrar título
- [ ] Mostrar data de upload
- [ ] Criar botão para visualizar
- [ ] Criar botão para download
- [ ] Criar estado de carregamento
- [ ] Criar mensagem quando não houver documentos
- [ ] Tratar erros da API

## 9. Frontend — Upload

- [ ] Criar formulário de upload
- [ ] Campo de título
- [ ] Campo de descrição
- [ ] Campo para arquivo
- [ ] Mostrar arquivo selecionado
- [ ] Validar campos
- [ ] Validar extensão/tipo do arquivo
- [ ] Enviar `FormData` para API
- [ ] Mostrar loading durante upload
- [ ] Mostrar mensagem de sucesso
- [ ] Redirecionar para documentos após upload

## 10. Frontend — Detalhes do documento

- [ ] Criar página de detalhes
- [ ] Buscar documento pela API
- [ ] Exibir documento
- [ ] Exibir título
- [ ] Exibir descrição
- [ ] Exibir data de upload
- [ ] Criar botão de download
- [ ] Buscar comentários
- [ ] Exibir histórico de comentários
- [ ] Exibir data/hora dos comentários
- [ ] Criar formulário para novo comentário
- [ ] Enviar comentário pela API
- [ ] Atualizar histórico após adicionar comentário

## 11. React Router

- [ ] Criar rota `/documents`
- [ ] Criar rota `/upload`
- [ ] Criar rota `/documents/:id`
- [ ] Criar navegação Sidebar → Documentos
- [ ] Criar navegação Sidebar → Upload
- [ ] Criar navegação Documentos → Detalhes
- [ ] Criar botão de voltar para documentos
- [ ] Testar navegação entre todas as páginas

## 12. UI / UX

- [ ] Criar layout responsivo
- [ ] Adicionar ícones com Lucide/React Icons
- [ ] Criar estados de hover
- [ ] Criar estados de loading
- [ ] Criar mensagens de erro
- [ ] Criar mensagens de sucesso
- [ ] Criar feedback durante upload
- [ ] Ajustar espaçamentos
- [ ] Revisar tipografia
- [ ] Revisar responsividade mobile

## 13. Integração Full Stack

- [ ] Conectar frontend com backend
- [ ] Testar upload completo
- [ ] Testar persistência no PostgreSQL
- [ ] Testar listagem de documentos
- [ ] Testar visualização
- [ ] Testar download
- [ ] Testar criação de comentários
- [ ] Testar histórico de comentários
- [ ] Testar atualização do histórico
- [ ] Corrigir erros de integração

## 14. Validação final

- [ ] Testar PDF
- [ ] Testar JPG
- [ ] Testar PNG
- [ ] Testar arquivo inválido
- [ ] Testar título vazio
- [ ] Testar descrição opcional
- [ ] Testar comentário vazio
- [ ] Testar documento inexistente
- [ ] Testar banco de dados
- [ ] Testar página sem documentos
- [ ] Testar responsividade

## 15. Git / GitHub

- [ ] Fazer primeiro commit — estrutura inicial
- [ ] Commit — configuração frontend
- [ ] Commit — configuração backend
- [ ] Commit — Prisma/PostgreSQL
- [ ] Commit — upload de documentos
- [ ] Commit — endpoints de documentos
- [ ] Commit — comentários
- [ ] Commit — integração frontend/backend
- [ ] Commit — UI/UX
- [ ] Commit — correções finais
- [ ] Subir projeto para GitHub

## 16. Deploy

- [ ] Escolher plataforma de deploy
- [ ] Configurar banco PostgreSQL de produção
- [ ] Configurar variáveis de ambiente
- [ ] Fazer deploy do backend
- [ ] Fazer deploy do frontend
- [ ] Configurar URL da API
- [ ] Testar upload em produção
- [ ] Testar listagem em produção
- [ ] Testar visualização/download
- [ ] Testar comentários
- [ ] Confirmar que URL está pública e funcionando

## 17. README

- [ ] Descrever o projeto
- [ ] Descrever funcionalidades
- [ ] Listar tecnologias utilizadas
- [ ] Explicar estrutura do projeto
- [ ] Explicar como executar localmente
- [ ] Explicar configuração do `.env`
- [ ] Adicionar URL do deploy
- [ ] Adicionar limitações conhecidas
- [ ] Adicionar instruções para PostgreSQL
- [ ] Revisar README
- [ ] Adicionar screenshots