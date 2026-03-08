Bug 1

Título: Login realizado com sucesso sem preenchimento de credenciais

Descrição: Ao acessar a tela de login e selecionar o botão "Entrar" sem preencher os campos de e-mail e senha, o sistema informa que o login foi realizado com sucesso.

Passos para reproduzir:

1 - Acessar a tela de login

2 - Não preencher o campo e-mail

4 - Não preencher o campo senha

3 - Selecionar o botão "Entrar"

<img width="669" height="724" alt="image" src="https://github.com/user-attachments/assets/b5bc8e6e-954b-433a-a0e5-f376d19e9c3d" />
<img width="2536" height="1220" alt="image" src="https://github.com/user-attachments/assets/ce12e713-3b38-4304-a409-c2260e2fe1c0" />

Resultado atual: No canto inferior direito da tela o sistema informa que ocorreu um "Erro inesperado", mas também informa “Login realizado com sucesso”.

Resultado esperado: O sistema deve impedir o login e exibir uma mensagem de validação "Informe e-mail e senha".

Severidade: Crítico

Prioridade: Alta



Bug 2

Título: Login realizado com sucesso sem preenchimento correto de credenciais

Descrição: Ao acessar a tela de login e selecionar o botão "Entrar" sem preencher os campos de e-mail e senha com valores válidos, o sistema informa que o login foi realizado com sucesso.

Passos para reproduzir:

1 - Acessar a tela de login

2 - Preencher o campo e-mail apenas com espaços em branco

3 - Não preencher o campo senha

4 - Selecionar o botão "Entrar"

<img width="663" height="722" alt="image" src="https://github.com/user-attachments/assets/a3683588-ccae-4409-8d64-a2f40e30a58e" />
<img width="2536" height="1220" alt="image" src="https://github.com/user-attachments/assets/ce12e713-3b38-4304-a409-c2260e2fe1c0" />

Resultado atual: No canto inferior direito da tela o sistema informa que ocorreu um "Erro inesperado", mas também informa “Login realizado com sucesso”.

Resultado esperado: O sistema deve impedir o login e exibir uma mensagem "Informe sua senha". O ideal também seria o bloquear a inclusão de espaços no campo e-mail, garantindo que apenas e-mails válidos sejam aceitos.

Severidade: Crítico

Prioridade: Alta



Bug 3

Título: Mensagem de erro inadequada ao deixar o campo Senha vazio

Descrição: Ao preencher o campo e-mail, deixar o campo senha vazio e clicar no botão "Entrar", o sistema exibe a mensagem: "Conta não encontrada. Crie uma conta primeiro."

Passos para reproduzir:

1 - Acessar a tela de login

2 - Inserir qualquer valor no campo e-mail Ex.: Preencher apenas com números. Ex. 2: Preencher com um formato de e-mail válido, como teste1@gmail.com

3 - Deixar o campo de senha vazio

4 - Clicar no botão Entrar

Ex.: Preenchido apenas com números
<img width="671" height="728" alt="image" src="https://github.com/user-attachments/assets/e1068ebd-bf98-4171-bb2e-d8c4070faaa8" />
<img width="582" height="778" alt="image" src="https://github.com/user-attachments/assets/38e0fab0-eef8-4c3d-9520-7cbb53c9bc85" />

Ex. 2: Preenchido com um formato de e-mail válido
<img width="485" height="527" alt="image" src="https://github.com/user-attachments/assets/feeb6f4f-7755-419b-b33a-290dfe272d45" />
<img width="483" height="763" alt="image" src="https://github.com/user-attachments/assets/c0a8b79a-531f-49d3-851a-2e9ae7bab6ab" />

Resultado atual: O sistema exibe a mensagem: "Conta não encontrada. Crie uma conta primeiro."

Resultado esperado: O comportamento adequado seria o sistema primeiramente validar se os campos foram preenchidos, e então informar uma mensagem: "Informe sua Senha".

Severidade: Médio

Prioridade: Média



Bug 4

Título: Mensagem de erro inadequada ao deixar campo e-mail vazio

Descrição: Ao inserir uma senha, não preencher o e-mail e clicar no botão "Entrar" o sistema exibe a mensagem "Conta não encontrada. Crie uma conta primeiro."

Passos para reproduzir:

1 - Acessar a tela de login

2 - Deixar o campo de e-mail vazio

3 - Preencher o campo senha com qualquer valor

4 - Clicar no botão Entrar

<img width="838" height="906" alt="image" src="https://github.com/user-attachments/assets/c4cf7aa3-8403-45ca-b438-41cfad6e1f56" />
<img width="698" height="946" alt="image" src="https://github.com/user-attachments/assets/194ebe13-ae0b-450d-9b6e-ac982abe76a1" />

Resultado atual: O sistema exibe a mensagem: "Conta não encontrada. Crie uma conta primeiro."

Resultado esperado: O comportamento adequado seria o sistema primeiramente validar se os campos e-mail e senha foram preenchidos, e então informar que o campo de e-mail está vazio com uma mensagem: "Informe seu E-mail".

Severidade: Médio

Prioridade: Média



Bug 5

Título: Mensagem de erro inadequada ao inserir senha inválida

Descrição: Ao inserir um formato válido de e-mail, com senha inválida, o sistema exibe a mensagem "Conta não encontrada. Crie uma conta primeiro."

Passos para reproduzir:

1 - Acessar a tela de login

2 - Inserir um formato de e-mail válido Ex.: teste1@gmail.com

3 - Preencher o campo senha com até 8 caracteres 

4 - Clicar no botão Entrar

<img width="663" height="725" alt="image" src="https://github.com/user-attachments/assets/3f55c7d6-f3b0-4513-ba1d-5f6c01152d3d" />
<img width="583" height="792" alt="image" src="https://github.com/user-attachments/assets/eed535b0-54b9-42d1-8d38-6cb4a31c77a1" />

Resultado atual: O sistema exibe a mensagem: "Conta não encontrada. Crie uma conta primeiro."

Resultado esperado: O comportamento ideal seria que o sistema fizesse uma validação da senha uma vez que "A senha precisa ter no mínimo 8 caracteres e 1 caractere especial.", e então exibir uma mensagem genérica como "Email ou senha inválidos" 

Severidade: Médio

Prioridade: Média



Bug 6

Título: Mensagem de erro inadequada ao inserir senha inválida

Descrição: Ao inserir um formato válido de e-mail, preencher a senha e depois clicar no botão "Entrar", o sistema exibe a mensagem "Conta não encontrada. Crie uma conta primeiro."

Passos para reproduzir:

1 - Acessar a tela de login.

2 - Inserir um formato de e-mail válido Ex.: teste1@gmail.com

3 - Preencher o campo senha com pelo menos 8 caracteres e 1 caracter especial

4 - Clicar no botão Entrar.

<img width="659" height="722" alt="image" src="https://github.com/user-attachments/assets/1cd3fd86-f385-4793-863b-3c237410412c" />
<img width="583" height="788" alt="image" src="https://github.com/user-attachments/assets/3194ea15-469a-4d9b-bf78-75815b711f93" />

Resultado atual: O sistema exibe a mensagem: "Conta não encontrada. Crie uma conta primeiro."

Resultado esperado: O comportamento ideal seria que o sistema exibisse uma mensagem genérica e segura, como: "Email ou senha inválidos", evitando a exposição de informações sobre a existência de contas registradas no banco de dados.

Severidade: Alto

Prioridade: Alta



------

 

Bug 7

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



