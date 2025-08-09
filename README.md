# Configuração de uma Instância de Banco de Dados no Azure

## Introdução Rápida
O **Microsoft Azure Database** é um serviço gerenciado de banco de dados em nuvem que elimina a necessidade de instalar, configurar e manter servidores manualmente. Ele oferece suporte a **MySQL**, **PostgreSQL**, **MariaDB** e **SQL Server**, com escalabilidade, segurança e alta disponibilidade integradas.

---

## O que é SQL? (Resumo)
**SQL** (*Structured Query Language*) é a linguagem padrão para criar, consultar, atualizar e gerenciar bancos de dados relacionais.  
Com ela é possível:
- Criar tabelas e estruturas de dados.
- Inserir, atualizar e excluir registros.
- Consultar dados usando filtros, ordenações e agrupamentos.
- Gerenciar permissões e segurança no banco.

---

## Benefícios de Usar Banco de Dados na Nuvem
- **Alta Disponibilidade**: redundância automática para evitar downtime.
- **Escalabilidade**: ajuste de capacidade de forma simples.
- **Segurança**: criptografia, firewall e autenticação avançada.
- **Backup Automático**: retenção configurável e restauração rápida.
- **Gerenciamento Simplificado**: manutenção e patching automáticos.

---

## Como Criar e Configurar uma Instância de Banco de Dados no Azure

### 1. Acessar o Portal do Azure
- Entre em: [https://portal.azure.com](https://portal.azure.com)
- Na barra de busca, digite o tipo de banco desejado:
  - **Azure Database for MySQL**
  - **Azure Database for PostgreSQL**
  - **Azure SQL Database**

---

### 2. Criar a Instância
1. Clique em **+ Criar** → escolha o tipo de banco.
2. Na aba **Básico**:
   - **Assinatura** e **Grupo de Recursos**.
   - **Nome do Servidor** (único globalmente).
   - **Região** (data center mais próximo do seu público).
   - **Zona de Disponibilidade** (1, 2 ou 3) para maior resiliência.
   - **Versão do Banco** (MySQL 8.0, PostgreSQL 15, etc.).
3. Escolha o **Tipo de Computação**:
   - Número de vCores.
   - Memória.
   - Armazenamento inicial (pode ser expandido depois).

---

### 3. Configurar Autenticação e Segurança
- **Usuário Administrador** e **Senha**.
- **Firewall**:
  - Adicionar **IP do cliente** para permitir acesso.
  - Restringir acesso apenas a IPs autorizados.
- **Conexão Segura (SSL)**:
  - Ativar criptografia para conexões externas.

---

### 4. Ajustar Rede e Backup
- **Rede Virtual**: conectar a instância apenas a recursos internos.
- **Backups Automáticos**:
  - Período de retenção (7 a 35 dias).
  - Possibilidade de restauração pontual.

---

### 5. Revisar e Criar
- Verifique as configurações na aba **Revisar + Criar**.
- Clique em **Criar**.
- Aguarde a implantação (pode levar alguns minutos).

---

## Opções Importantes na Configuração
- **Escala Vertical**: aumentar CPU e memória sem recriar a instância.
- **Escala Horizontal (Read Replicas)**: criar réplicas para leitura.
- **Monitoramento**: usar **Azure Monitor** e **Log Analytics**.
- **Alertas**: configurar notificações para consumo, CPU e armazenamento.

---

## Como Conectar à Instância Criada
1. Localize o banco no portal do Azure.
2. Pegue o **Hostname** e a **Porta**.
3. Use um cliente compatível (DBeaver, Azure Data Studio, MySQL Workbench, psql, etc.).
4. Exemplo MySQL:
   ```bash
   mysql -h meu-servidor.mysql.database.azure.com -u admin@meu-servidor -p
ofundar seus conhecimentos em serviços específicos.
