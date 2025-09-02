# Instância de Banco de Dados no Microsoft Azure

Este projeto ensina como criar e configurar uma instância de Banco de Dados SQL no Azure.

## Requisitos
- Conta ativa no Azure
- Assinatura válida
- Permissões de administrador

## Etapas

1. **Criar o banco de dados**
   - Acesse o portal do Azure
   - Vá em “Criar recurso” > “Banco de Dados SQL”
   - Configure nome, servidor e redundância

2. **Definir performance**
   - Escolha entre DTU ou vCore na aba “Compute + Storage”

3. **Configurar acesso**
   - Vá em “Configurações de Firewall” e libere IPs necessários

4. **Conectar ao banco**
   - Use a string de conexão no formato ADO.NET (exemplo incluído no projeto)

## Referência
[Acesse o portal do Azure](https://learn.microsoft.com/pt-br/azure/azure-sql/managed-instance/instance-create-quickstart?view=azuresql&tabs=azure-portal)
