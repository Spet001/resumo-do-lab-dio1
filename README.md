# Microsoft Azure: Guia Completo para Iniciantes

## Introdução Rápida
O **Microsoft Azure** é a plataforma de **computação em nuvem** da Microsoft, oferecendo serviços de armazenamento, processamento, redes, IA e muito mais. Permite criar e gerenciar aplicações e infraestrutura sem servidores locais, com cobrança baseada no uso.

---

## Computação em Nuvem: Benefícios e Malefícios

### Benefícios da Nuvem: Escalabilidade e Elasticidade
- **Escalabilidade**: aumenta ou reduz recursos conforme a demanda, sem investimento físico.
- **Elasticidade**: ajuste automático de capacidade para atender picos de uso.

### Benefícios da Nuvem: Confiabilidade, Previsibilidade e Segurança
- **Confiabilidade**: alta disponibilidade e recuperação rápida em falhas.
- **Previsibilidade**: custos e desempenho controláveis.
- **Segurança**: múltiplas camadas de proteção, padrões internacionais e monitoramento constante.

### Benefícios da Nuvem: Governança e Gerenciabilidade
- **Governança**: políticas para controle de custos, uso e conformidade.
- **Gerenciabilidade**: ferramentas integradas para administrar e monitorar recursos.

### Possíveis Malefícios
- **Dependência de Internet**: sem conexão, os serviços ficam inacessíveis.
- **Custos mal geridos**: uso excessivo ou má configuração pode gerar despesas altas.
- **Privacidade e compliance**: atenção a leis e regulamentações sobre dados.

---

## Modelos de Nuvem
1. **Nuvem Pública**: recursos compartilhados entre clientes, gerenciados pelo provedor.
2. **Nuvem Privada**: infraestrutura dedicada a uma organização.
3. **Nuvem Híbrida**: combinação de nuvem pública e privada.

---

## Serviços do Azure: Como Encontrar a Opção de Criar uma VM
1. Acesse o portal do Azure: [https://portal.azure.com](https://portal.azure.com)
2. No menu lateral ou na barra de busca, digite **"Máquinas Virtuais"**.
3. Clique em **“+ Criar”** → **Máquina Virtual do Azure**.

---

## Como Criar uma VM no Azure
1. **Portal do Azure → Criar Recurso → Computação → Máquina Virtual**.
2. Escolha:
   - **Assinatura** e **Grupo de Recursos**.
   - **Nome da VM**.
   - **Região** (data center mais próximo do seu público).
   - **Zona de Disponibilidade** (1, 2 ou 3) para redundância física dentro da mesma região.
3. Em **Imagem** selecione o sistema operacional (Windows Server, Ubuntu, etc.).
4. Configure:
   - **Tamanho** da VM (CPU, memória).
   - **Usuário e senha** ou **chave SSH**.
5. Ajuste:
   - Rede virtual, sub-rede e IP público.
   - Armazenamento (tipo de disco).
   - Segurança (firewall, portas).
6. Clique em **Revisar + Criar** e depois em **Criar**.

---

## Opções da VM do Azure

### Séries de Máquinas Virtuais
- **B** – baixo custo, uso esporádico.
- **D** – uso geral, equilíbrio CPU/memória.
- **E** – otimizado para memória.
- **F** – otimizado para CPU.
- **N** – otimizado para GPU (IA e gráficos).

### Sistemas Operacionais (Imagem)
- Windows Server, Ubuntu, CentOS, Red Hat, Debian, etc.

### Discos
- **HDD padrão**: mais barato, menor desempenho.
- **SSD padrão**: mais rápido.
- **SSD premium**: alto desempenho.

### Rede
- IP público ou privado.
- Regras de firewall.
- Balanceadores de carga.

---

## Mais Informações sobre VM do Azure
- **Escalabilidade**: aumentar recursos (vertical) ou criar múltiplas instâncias (horizontal).
- **Backup e Recovery**: snapshots e restauração nativa.
- **Monitoramento**: integração com Azure Monitor para métricas e alertas.
- **Custos**: cobrança por hora de uso, com desconto para reservas.
- **Segurança**: criptografia de disco, firewalls, VPNs e Azure Defender.

t Learn** para aprofundar seus conhecimentos em serviços específicos.
