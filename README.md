<h1>
    <a href="https://www.dio.me/">
     <img align="center" width="40px" src="https://hermes.digitalinnovation.one/assets/diome/logo-minimized.png"></a>
    <span> Desafio de Projeto - DIO</span>
</h1>

O projeto é referente ao desafio de projeto **Modelando o Sistema Bancário em POO com Python** do módulo **Dominando Python e Suas Estruturas de dados** do Python AI Backend Developer - **Bootcamp Coding The Future Vivo - Python AI Backend Developer 2024** da [Digital Innovation One](https://www.dio.me/).

O **objetivo** é aprimorar a estrutura e a eficiência do sistema, implementando as operações de depósito, saque e extrato em funções específicas. Além da chance de refatorar o código existente, dividindo-o em funções reutilizáveis, facilitando a manutenção e o entendimento do sistema como um todo.

Durante o desafio foi aplicado conhecimentos em programação Python e criado um sistema funcional que permitiu simular as operações bancárias. Permitindo aprimorar habilidades e demonstrar minha capacidade de desenvolver soluções práticas e eficientes.

---

**Separar as operações existentes em funções:**
- **saque, depósito e extrato:**

**Função →** Saque: receber argumentos → nome (keyword only)
**Sugestão →** Argumentos: saldo, valor, extrato, limite, numero_saques, limite_saques.
**Sugestão →** Retorno: saldo, estrato.

**Função →** Depósito: receber argumentos → posição (positional only)
**Sugestão →** Argumento: saldo, valor, extrato.
**Sugestão →** Retorno: saldo, extrato.

**Função →** Extrato: receber argumentos → posição/nome (positional only / keyword only)
**Sugestão →** Argumento posicionais: saldo.
**Sugestão →** Argumento nomeados: extrato.
<br>

**Criar duas novas funções:**
- **cadastrar usuário (cliente)**
- **cadastrar conta bancária.**

**Função →** Criar usuário (cliente)
-   armazenar os usuários em uma lista.
-   Usuário: nome, data de nascimento, cpf e endereço.
-   Endereço: String com formato: logradouro, nro bairro - cidade/sigla estado.
-   CPF: armazenar somente números.
-   Obs: não pode cadastrar 2 usuários com mesmo CPF.

**Função →** Conta corrente
-   armazenar contas em uma lista.
-   Conta: agência, número da conta e usuário.
-   Número: sequencial, iniciando em 1.
-   Agência: número fixo em “0001”.
-   Usuário: pode ter mais de uma conta.
-   Conta: só pode ter um usuário.



**Links Úteis:**

- **Slides:** [Desafio: Criando Um Sistema Bancário](http://academiapme-my.sharepoint.com/:p:/g/personal/kawan_dio_me/Ef-dMEJYq9BPotZQso7LUCwBJd7gDqCC2SYlUYx0ayrGNQ?e=G79e2L)
- **Estruturas de controle em Python:** [Acesso aqui!](https://www.w3schools.com/python/python_conditions.asp)
- **Manipulação de strings em Python:** [Acesso aqui!](https://www.w3schools.com/python/python_strings.asp)
- **Funções em Python:** [Acesso aqui!](https://www.w3schools.com/python/python_strings.asp)
