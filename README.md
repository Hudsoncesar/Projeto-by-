# Banco Py

"Banco Py, inovando cada vez mais"

## Descrição

O Banco Py é um sistema de banco fictício criado para o projeto do curso (Senac-Análise de Dados). Este sistema simula funcionalidades bancárias básicas, como a criação de contas, gestão de saldos, transferências, empréstimos e investimentos em moedas criptografadas. O Banco Py também oferece suporte ao cliente com informações sobre como usar as funcionalidades do sistema.

## Funcionalidades Principais

O Banco Py possui as seguintes funcionalidades principais:

1. **Cadastro de Contas e Login:** Os usuários podem criar novas contas fornecendo um nome de usuário, senha e uma renda informada pelo usuário. Cada conta recebe o valor inicial de R$1000, para fazer as operações no banco. Os usuários podem fazer login em suas contas fornecendo os dados corretos, sendo redirecionados ao menu principal.

2. **Menu Conta:**
   - **Consulta de Saldo:** Os usuários podem verificar o saldo disponível em sua conta.
   - **Pagamento de Fatura:** Os usuários podem pagar suas faturas pendentes, que são calculadas com base em empréstimos anteriores.
   - **Esperar:** Uma função relacionada ao valor das criptomoedas, faz com que os valores mudem.

3. **Empréstimos:** Os usuários podem solicitar empréstimos, desde que o valor solicitado não exceda o dobro de sua renda. O valor do empréstimo é adicionado ao saldo da conta, e uma fatura é criada com juros.

4. **Transferências:** Os usuários podem transferir dinheiro entre contas cadastradas no sistema.

5. **Investimentos em Moedas Criptografadas:** Os usuários podem investir em moedas criptografadas disponíveis no mercado. Eles podem comprar moedas com seu saldo e retirar moedas para convertê-las em saldo. Use a função "Esperar" (Localizada no menu Conta) para alterar seu valor.

6. **Suporte ao Cliente:** Um menu de explicação para cada opção no menu.

## Estrutura de Arquivos

O código-fonte do Banco Py está organizado em vários arquivos, cada um com funções específicas:

- `suporte.py`: Um menu de suporte ao cliente com informações sobre as funcionalidades do banco.
- `investimento.py`: Implementa as funcionalidades relacionadas a investimentos em criptomoedas.
- `emprestimo.py`: Permite aos usuários solicitar empréstimos e pagar faturas pendentes.
- `transferencia.py`: Contém funções relacionadas a transferências de dinheiro entre contas.
- `conta.py`: Gerencia as funcionalidades de consulta de saldo e pagamento de faturas.
- `menu.py`: É o menu principal do banco que direciona o usuário para as diferentes funcionalidades.
- `login.py`: Lida com o login e criação de contas de usuário.

## Como Executar

Para executar o Banco Py, siga estas etapas:

1. Certifique-se de ter o Python instalado em seu sistema.
2. Clone este repositório em sua máquina local.
3. Abra um terminal e navegue até o diretório do repositório clonado.
4. Execute o arquivo `pybank.py` com o comando:

## Equipe do Projeto

Aqui estão os membros da equipe e suas respectivas funções:

- **Luana** (Co-Facilitadora)
- **Cássio** (Gestora de Gente e Engajamento)
- **Luís Felipe** (Gestora de Conhecimento)
- **Hudson** (Colaboradora I)
- **Renan** (Colaboradora II)
