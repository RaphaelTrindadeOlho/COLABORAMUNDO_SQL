# COLABORAMUNDO_SQL
Utilizando SQL Server para escrever o script do banco de dados do site ColaboraMundo

# Projeto SQL Server - ColaboraMundo

Este projeto define o banco de dados **ColaboraMundo**, desenvolvido para gerenciar colaborações em projetos relacionados aos Objetivos de Desenvolvimento Sustentável (ODS). O banco modela usuários, especialistas, projetos, colaborações e diversas atividades associadas.

## Estrutura do Banco de Dados

### Principais Tabelas
- **USUARIO_COMUM**: Contém informações sobre os usuários do sistema (nome, e-mail, país e senha).
- **PROJETO**: Representa projetos, incluindo nome, descrição, status e prazos.
- **COLABORACAO**: Detalha as colaborações feitas pelos usuários, com descrições e datas.
- **ESPECIALISTA**: Registra especialistas e suas informações básicas (nome, e-mail, país e senha).
- **EXPERTISE**: Relaciona especialistas com suas áreas de atuação, nível de expertise e certificações.
- **MENTORIA**: Relaciona colaborações com sessões de mentoria realizadas por especialistas.
- **VOLUNTARIADO**: Descreve atividades voluntárias realizadas em colaborações.
- **FINANCEIRO**: Detalha colaborações financeiras, incluindo valores e destinos.
- **ODS**: Lista os Objetivos de Desenvolvimento Sustentável vinculados aos projetos.
- **TAREFA**: Registra tarefas associadas aos projetos, com detalhes e prazos.
- **DOCUMENTO**: Gerencia documentos relacionados aos projetos.

### Relacionamentos Importantes
- **PROJETO_USUARIO**: Associa usuários a projetos.
- **ODS_PROJETO**: Relaciona projetos aos ODS.

## Scripts
O arquivo de script SQL completo pode ser utilizado para criar o banco de dados e todas as tabelas com suas relações e constraints. Basta executar o código no SQL Server Management Studio (SSMS).

## Como Usar
1. Execute o script SQL para criar o banco de dados e suas tabelas.
2. Insira os dados necessários para iniciar o gerenciamento de colaborações e projetos.
3. Realize consultas para extrair informações como usuários, projetos, colaborações e atividades.

---

**Nota**: Este projeto é apenas um modelo inicial para o gerenciamento de colaborações em projetos e pode ser adaptado conforme necessário.
