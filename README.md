# Teste Prático - Processo Seletivo

## Objetivo
Implementar melhorias no sistema `FI.WebAtividadeEntrevista` para avaliação técnica.

## Requisitos
- Visual Studio 2022 (Community aceita)
- .NET Framework 4.8
- SQL Server Express 2019 LocalDB  
- Solution: [Download](http://atende.funcao.com.br/download/FI.WebAtividadeEntrevista.zip)

## Implementações

### 1. Campo CPF no Cliente
- Adicionar campo **CPF** (formato `999.999.999-99`) no cadastro/edição.
- Obrigatório, validar CPF, não permitir duplicados.
- Alterar tabela `CLIENTES` para incluir `CPF`.

### 2. Botão Beneficiários
- Adicionar botão que abre modal para gerenciar beneficiários (CPF e Nome).
- Grid com inclusão, edição e exclusão.
- Validar CPF e impedir duplicados por cliente.
- Criar tabela `BENEFICIARIOS` (`ID`, `CPF`, `NOME`, `IDCLIENTE`).

## Execução
1. Abrir a solution no Visual Studio.
2. Restaurar pacotes, compilar e executar.
3. Testar na aba **Clientes**.
