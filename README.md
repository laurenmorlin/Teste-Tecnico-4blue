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

------

Bug 2

Título: Login realizado com sucesso sem preenchimento de e-mail

Descrição: Ao acessar a tela de login e selecionar o botão "Entrar" sem preencher os campos de e-mail e preenchendo com uma senha cadastrada, o sistema informa que o login foi realizado com sucesso.

Passos para reproduzir:

1 - Acessar a tela Criar Conta

2 - Preencher somente o campo senha

3 - Clicar no botão "Criar Conta"

4 - Na tela Login realizado com sucesso clicar em "Sair da Conta"

5 - Na tela de login não preencher o campo e-mail

6 - Preencher o campo senha com a senha cadastrada na tela Criar conta

7 - Selecionar o botão "Entrar"

<img width="900" height="814" alt="image" src="https://github.com/user-attachments/assets/224bdb92-c4b3-43a3-877c-1313bb591ba0" />
<img width="648" height="517" alt="image" src="https://github.com/user-attachments/assets/2aef05ed-07b9-40bc-9097-14442b33c6c6" />
<img width="676" height="726" alt="image" src="https://github.com/user-attachments/assets/70f282aa-326e-48d9-b4c8-0164d4c21e93" />
<img width="650" height="508" alt="image" src="https://github.com/user-attachments/assets/337620ec-167d-49a9-8789-fd126c5a89bf" />

Resultado atual: No canto inferior direito da tela o sistema informa que ocorreu um "Erro inesperado", mas também informa “Login realizado com sucesso”.

Resultado esperado: O sistema deve impedir o login e exibir uma mensagem "Informe seu e-mail".

Severidade: Crítico

Prioridade: Alta

------

Bug 3

Título: Mensagem de erro ao usar uma conta cadastrada

Descrição: Ao preencher o campo e-mail com uma conta cadastrada o sistema exibe a mensagem: "Conta não encontrada. Crie uma conta primeiro."

Passos para reproduzir:

1 - Acessar a tela de login

2 - Inserir um e-mail cadastrado no campo  Ex.: marilia.castanheira@gmail.com

3 - Deixar preencher ou não o campo senha

4 - Clicar no botão Entrar

Ex.: Preenchido apenas com números

<img width="675" height="732" alt="image" src="https://github.com/user-attachments/assets/2a46e7dd-1f71-4dc5-8d24-c8c1690db7ed" />
<img width="586" height="661" alt="image" src="https://github.com/user-attachments/assets/16e19fe9-aa28-45dc-87f8-3f8a464e89b0" />

Ex. 2: Preenchido com um e-mail cadastrado

<img width="664" height="730" alt="image" src="https://github.com/user-attachments/assets/d6eec609-5a7a-46af-b590-7e3523b4ebcb" />
<img width="581" height="661" alt="image" src="https://github.com/user-attachments/assets/b31e6431-80d3-48c1-9d49-dd60fdf77681" />

Resultado atual: O sistema exibe a mensagem: "Conta não encontrada. Crie uma conta primeiro."

Resultado esperado: O sistema deve primeiramente validar se os campos foram preenchidos e informar uma mensagem: "Informe sua Senha".

Severidade: Médio

Prioridade: Média

------

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

------

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

Resultado esperado: O comportamento ideal seria que o sistema fizesse uma validação da senha uma vez que "A senha precisa ter no mínimo 8 caracteres e 1 caractere especial.", e então exibir uma mensagem genérica como "Email ou senha inválidos".

Severidade: Médio

Prioridade: Média

------

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

Severidade: Médio

Prioridade: Média

------

Bug 7

Título: Ajustar nome do botão "Sair da conta"

Descrição: Na tela Login realizado com Sucesso há um botão escrito "Sair da Conta".

Passos para reproduzir:

1 - Acessar a tela Login

2 - Colocar um e-mail e senha válidos e clicar em "Entrar"

3 - O sistema vai exibir a tela Login realizado com sucesso
<img width="825" height="879" alt="image" src="https://github.com/user-attachments/assets/be9d330f-2bd3-401f-9732-1385b03ef97f" />
<img width="886" height="703" alt="image" src="https://github.com/user-attachments/assets/9b482517-280c-45fe-a5c6-e4a80900e41d" />

Resultado atual: Na tela Login realizado com sucesso há um botão escrito "Sair da Conta".

Resultado esperado: Ajustar o nome do botão "Sair da Conta" para algo como "Continuar para o sistema".

Severidade: 

Prioridade:

------

Bug 8

Título: Conta criada com sucesso sem preenchimento dos campos

Descrição: Na tela de Criar Conta, ao clicar no botão Criar Conta sem preencher nenhum campo, o sistema informa que a conta foi criada com sucesso.

Passos para reproduzir:

1 - Acessar a tela Criar Conta

2 - Não preencher nenhum campo

3 - Clicar no botão "Criar Conta"
<img width="681" height="775" alt="image" src="https://github.com/user-attachments/assets/3440368c-56a2-48bf-bc6c-a3e3e0c12364" />
<img width="681" height="510" alt="image" src="https://github.com/user-attachments/assets/c2d6f489-f4d6-4dce-b135-4bf0440ade27" />

Resultado atual: O sistema exibe a mensagem “Conta criada com sucesso” mesmo os sem dados informados.

Resultado esperado: O sistema deve impedir o cadastro e solicitar o preenchimento obrigatório dos campos.

Severidade: 

Prioridade: 

------

Bug 9

Título: Ajustar nome do botão "Sair da conta" na tela Conta criada com Sucesso

Descrição: Na tela Conta criada com Sucesso há um botão escrito "Sair da Conta".

Passos para reproduzir:

1 - Na tela Login, clicar em "Criar conta"

2 - Na tela Crie sua conta preencher os campos e clicar em "Criar Conta"

3 - O sistema vai exibir a tela Conta criada com Sucesso e o botão "Sair da Conta"
<img width="904" height="1052" alt="image" src="https://github.com/user-attachments/assets/50b60463-916f-48be-b061-141e55c99209" />
<img width="886" height="703" alt="image" src="https://github.com/user-attachments/assets/9b482517-280c-45fe-a5c6-e4a80900e41d" />

Resultado atual: Na tela Conta criada com Sucesso há um botão escrito "Sair da Conta".

Resultado esperado: Ajustar o nome do botão "Sair da Conta" para algo como "Continuar para o sistema".

Severidade: 

Prioridade:

------

Bug 10

Título: Ajustar a posição dos campos Telefone e Confirmar senha

Descrição: Na tela Crie sua conta os campos Telefone e Confirmar senha estão desalinhados.

Passos para reproduzir:

1 - Na tela Login, clicar em "Criar conta"

2 - O sistema vai exibir a tela Crie sua conta
<img width="1109" height="1059" alt="image" src="https://github.com/user-attachments/assets/a5ce751a-d20b-4de2-a53d-d011d09ea38f" />

Resultado atual: Na tela Crie sua conta os campos Telefone e Confirmar senha estão desalinhados.

Resultado esperado: Ajustar os campos Telefone e Confirmar senha na tela Crie sua conta.

Severidade: 

Prioridade:



