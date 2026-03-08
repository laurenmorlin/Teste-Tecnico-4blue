Bug 1

Título: Login realizado com sucesso sem preenchimento de credenciais

Descrição: Ao acessar a tela de login e selecionar o botão Entrar sem preencher os campos de e-mail e senha, o sistema informa que o login foi realizado com sucesso.

Passos para reproduzir:

1 - Acessar a tela de login

2 - Deixar os campos E-mail e Senha em branco.

3 - Selecionar o botão "Entrar"

<img width="2536" height="1220" alt="image" src="https://github.com/user-attachments/assets/ce12e713-3b38-4304-a409-c2260e2fe1c0" />
<img width="651" height="531" alt="image" src="https://github.com/user-attachments/assets/198efbd7-3010-4e7b-a8e3-15a3553c0f33" />

Resultado atual: No canto inferior direito da tela o sistema informa que ocorreu um "Erro inesperado", mas também informa “Login realizado com sucesso”.

Resultado esperado: O sistema deve impedir o login e exibir uma mensagem de validação "Informe e-mail e senha".

Severidade: Crítico

Prioridade: Alta



Bug 2

Título: Login realizado com sucesso sem preenchimento correto de credenciais

Descrição: Ao acessar a tela de login e selecionar o botão Entrar sem preencher os campos de e-mail e senha corretamente, o sistema informa que o login foi realizado com sucesso.

Passos para reproduzir:

1 - Acessar a tela de login

2 - Preencher o campo e-mail com espaços em branco e não preencher o campo senha.

3 - Selecionar o botão "Entrar"

<img width="2536" height="1220" alt="image" src="https://github.com/user-attachments/assets/ce12e713-3b38-4304-a409-c2260e2fe1c0" />
<img width="651" height="531" alt="image" src="https://github.com/user-attachments/assets/198efbd7-3010-4e7b-a8e3-15a3553c0f33" />

Resultado atual: No canto inferior direito da tela o sistema informa que ocorreu um "Erro inesperado", mas também informa “Login realizado com sucesso”.

Resultado esperado: O sistema deve impedir o login e exibir uma mensagem "Email ou senha inválidos". O ideal também seria o sistema bloquear a inclusão de espaços no campo e-mail, garantindo que apenas e-mails válidos sejam aceitos.

Severidade: Crítico

Prioridade: Alta




Bug 3

Título: Mensagem de erro inadequada ao inserir e-mail ou senha inválidos

Descrição: Ao inserir um formato inválido de e-mail, com ou sem senha, ou ao preencher apenas a senha e clicar no botão "Entrar", o sistema exibe a mensagem "Conta não encontrada. Crie uma conta primeiro."

Passos para reproduzir:

1 - Acessar a tela de login.

2 - Inserir um formato de e-mail inválido.

3 - Deixar o campo de senha vazio ou preenchê-lo com uma senha inválida.

4 - Clicar no botão Entrar.

<img width="542" height="598" alt="image" src="https://github.com/user-attachments/assets/c3828091-4ace-4f1a-8fb4-a1d8641b9397" />
<img width="546" height="725" alt="image" src="https://github.com/user-attachments/assets/73a0f06c-bd89-4335-8ee3-ba2a6165ff68" />


Ou

1 -Acessar a tela de login.

2 - Preencher o campo de senha e deixar o campo de e-mail vazio.

3 - Clicar no botão Entrar.

<img width="838" height="906" alt="image" src="https://github.com/user-attachments/assets/c4cf7aa3-8403-45ca-b438-41cfad6e1f56" />
<img width="698" height="946" alt="image" src="https://github.com/user-attachments/assets/194ebe13-ae0b-450d-9b6e-ac982abe76a1" />

Resultado atual: O sistema exibe a mensagem: "Conta não encontrada. Crie uma conta primeiro."

Resultado esperado: O comportamento ideal seria que o sistema exibisse uma mensagem mais genérica e segura, como: "Email ou senha inválidos", evitando a exposição de informações sobre a existência de contas registradas no banco de dados.

Severidade: Alto

Prioridade: Alta



Bug 4
Título: Mensagem de erro inadequada ao inserir e-mail ou senha inválidos

Descrição: Ao inserir um formato inválido de e-mail, com ou sem senha, ou ao preencher apenas a senha e clicar no botão "Entrar", o sistema exibe a mensagem "Conta não encontrada. Crie uma conta primeiro."

Passos para reproduzir:

1 - Acessar a tela de login.

2 - Inserir um formato de e-mail inválido.

3 - Deixar o campo de senha vazio ou preenchê-lo com uma senha inválida.

4 - Clicar no botão Entrar.

<img width="542" height="598" alt="image" src="https://github.com/user-attachments/assets/c3828091-4ace-4f1a-8fb4-a1d8641b9397" />
<img width="546" height="725" alt="image" src="https://github.com/user-attachments/assets/73a0f06c-bd89-4335-8ee3-ba2a6165ff68" />


Ou

1 -Acessar a tela de login.

2 - Preencher o campo de senha e deixar o campo de e-mail vazio.

3 - Clicar no botão Entrar.

<img width="838" height="906" alt="image" src="https://github.com/user-attachments/assets/c4cf7aa3-8403-45ca-b438-41cfad6e1f56" />
<img width="698" height="946" alt="image" src="https://github.com/user-attachments/assets/194ebe13-ae0b-450d-9b6e-ac982abe76a1" />

Resultado atual: O sistema exibe a mensagem: "Conta não encontrada. Crie uma conta primeiro."

Resultado esperado: O comportamento ideal seria que o sistema exibisse uma mensagem mais genérica e segura, como: "Email ou senha inválidos", evitando a exposição de informações sobre a existência de contas registradas no banco de dados.

Severidade: Alto

Prioridade: Alta

Bug 4
Título: Mensagem de erro inadequada ao inserir e-mail ou senha inválidos

Descrição: Ao inserir um formato inválido de e-mail, com ou sem senha, ou ao preencher apenas a senha e clicar no botão "Entrar", o sistema exibe a mensagem "Conta não encontrada. Crie uma conta primeiro."

Passos para reproduzir:

1 - Acessar a tela de login.

2 - Inserir um formato de e-mail inválido.

3 - Deixar o campo de senha vazio ou preenchê-lo com uma senha inválida.

4 - Clicar no botão Entrar.

<img width="542" height="598" alt="image" src="https://github.com/user-attachments/assets/c3828091-4ace-4f1a-8fb4-a1d8641b9397" />
<img width="546" height="725" alt="image" src="https://github.com/user-attachments/assets/73a0f06c-bd89-4335-8ee3-ba2a6165ff68" />


Ou

1 -Acessar a tela de login.

2 - Preencher o campo de senha e deixar o campo de e-mail vazio.

3 - Clicar no botão Entrar.

<img width="838" height="906" alt="image" src="https://github.com/user-attachments/assets/c4cf7aa3-8403-45ca-b438-41cfad6e1f56" />
<img width="698" height="946" alt="image" src="https://github.com/user-attachments/assets/194ebe13-ae0b-450d-9b6e-ac982abe76a1" />

Resultado atual: O sistema exibe a mensagem: "Conta não encontrada. Crie uma conta primeiro."

Resultado esperado: O comportamento ideal seria que o sistema exibisse uma mensagem mais genérica e segura, como: "Email ou senha inválidos", evitando a exposição de informações sobre a existência de contas registradas no banco de dados.

Severidade: Alto

Prioridade: Alta



Bug 3

Título: Mensagem de erro inadequada ao deixar o campo de senha vazio no login

Descrição: Ao preencher o campo e-mail e deixar o campo de senha vazio, ao clicar no botão "Entrar", o sistema exibe a mensagem: "Conta não encontrada. Crie uma conta primeiro."

Passos para reproduzir:

1 - Acessar a tela de login.

2 - Preencher o campo e-mail com um e-mail válido (existente ou não).

3 - Deixar o campo senha vazio.

4 - Clicar no botão Entrar.

<img width="485" height="527" alt="image" src="https://github.com/user-attachments/assets/feeb6f4f-7755-419b-b33a-290dfe272d45" />
<img width="483" height="763" alt="image" src="https://github.com/user-attachments/assets/c0a8b79a-531f-49d3-851a-2e9ae7bab6ab" />

Resultado atual: O sistema exibe a mensagem: "Conta não encontrada. Crie uma conta primeiro."

Resultado esperado: O sistema deve exibir a mensagem: "Informe sua Senha". O comportamento adequado seria o sistema primeiramente validar se o campo senha foi preenchido e então informar que o campo de senha está vaziocom uma mensagem: "Informe sua Senha".

Severidade: Médio

Prioridade: Média




Título: Conta criada com sucesso sem preenchimento de dados obrigatórios

Descrição: Na tela de Criar Conta, ao clicar no botão Criar Conta sem preencher nenhum campo, o sistema informa que a conta foi criada com sucesso.

Passos para reproduzir:

1 - Acessar a tela Criar Conta

2 - Não preencher nenhum campo

3 - Clicar no botão "Criar Conta"
<img width="681" height="775" alt="image" src="https://github.com/user-attachments/assets/3440368c-56a2-48bf-bc6c-a3e3e0c12364" />
<img width="681" height="510" alt="image" src="https://github.com/user-attachments/assets/c2d6f489-f4d6-4dce-b135-4bf0440ade27" />

Resultado atual: O sistema exibe a mensagem “Conta criada com sucesso” mesmo sem dados informados.

Resultado esperado: O sistema deve impedir o cadastro e solicitar o preenchimento dos campos obrigatórios.

Severidade: Crítico

Prioridade: Alta



Bug 4

Título: Campo de E-mail aceita espaços e apresenta mensagem inadequada.

Descrição:
Na tela de login, o campo de e-mail está permitindo a entrada de espaços em branco no início ou final do e-mail. Quando o e-mail é inserido com formato inválido (com espaços) e o botão "Entrar" é clicado, o sistema apresenta a mensagem:

“Conta não encontrada. Crie uma conta primeiro.”
O comportamento adequado seria exibir a mensagem:
“Email ou senha inválidos”
para evitar a exposição de informações sobre contas existentes e impedir que um atacante descubra quais e-mails existem no sistema.

Passos para reproduzir:

Acessar a tela de login.

Inserir um e-mail com espaços em branco (exemplo: " teste@email.com ").

Deixar o campo senha em branco.

Clicar em Entrar.

Resultado atual:
O sistema exibe a mensagem:

“Conta não encontrada. Crie uma conta primeiro.”

Resultado esperado:
O sistema deve exibir a mensagem:

“Email ou senha inválidos”

Severidade:
Alto – O comportamento atual pode permitir que um atacante saiba se um e-mail está registrado no sistema, violando princípios de segurança.

Prioridade:
Alta – Esse bug compromete a segurança do sistema e deve ser corrigido antes do lançamento.

