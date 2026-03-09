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

3 - Preencher o campo com senha incorreta ou deixa o campo senha vazio

4 - Clicar no botão Entrar

<img width="675" height="732" alt="image" src="https://github.com/user-attachments/assets/2a46e7dd-1f71-4dc5-8d24-c8c1690db7ed" />
<img width="586" height="661" alt="image" src="https://github.com/user-attachments/assets/16e19fe9-aa28-45dc-87f8-3f8a464e89b0" />

Resultado atual: O sistema exibe a mensagem: "Conta não encontrada. Crie uma conta primeiro."

Resultado esperado: O sistema não deve mostrar mensagem "Conta não encontrada" quando o e-mail está cadastrado
Severidade: Médio

Prioridade: Média

------

Bug 4

Título: Retirar mensagem "A senha precisa ter no mínimo 8 caracteres e 1 caractere especial." na tela de login

Descrição: Na tela de login aparece a mensagem "A senha precisa ter no mínimo 8 caracteres e 1 caractere especial.", não manter essa mensagem como boa prática de segurança.

Passos para reproduzir:

1 - Acessar a tela de login

<img width="886" height="972" alt="image" src="https://github.com/user-attachments/assets/acfb2125-24d9-4d1a-bc24-3b727fd3e8d4" />

Resultado atual: Na tela de login aparece a mensagem "A senha precisa ter no mínimo 8 caracteres e 1 caractere especial."

Resultado esperado: Manter a mensagem "A senha precisa ter no mínimo 8 caracteres e 1 caractere especial." apenas na tela de Criar conta

Severidade: Médio

Prioridade: Baixa

------

Bug 5

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

Bug 6

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

Bug 7

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

Bug 8

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

------

Bug 9

Título: Criar um campo Confirmar E-mail

Descrição: O sistema não possui um campo que ajude a confirmar o e-mail e assim evitar erros ao cadastrar uma contra, incluir um campo Confirmar E-mail.

Passos para reproduzir:

1 - Na tela Login, clicar em "Criar conta"

2 - O sistema vai exibir a tela Crie sua conta

<img width="734" height="817" alt="image" src="https://github.com/user-attachments/assets/0da17b01-774c-4b0f-9ae8-9595e977ba93" />

Resultado atual: Na tela Crie sua conta existe apenas o campo E-mail.

Resultado esperado: Na tela Crie sua conta apresentar um campo Confirmar E-mail

Severidade: 

Prioridade:

------

Bug 10

Título: Criar uma máscara no campo Telefone

Descrição: Aplicar uma máscara automática no campo Telefone para guiar o usuário

Passos para reproduzir:

1 - Na tela Login, clicar em "Criar conta"

2 - O sistema vai exibir a tela Crie sua conta

<img width="734" height="817" alt="image" src="https://github.com/user-attachments/assets/0da17b01-774c-4b0f-9ae8-9595e977ba93" />

Resultado atual: Na tela Crie sua conta o campo Telefone que está aceitando mais do que 11 números.

Resultado esperado: Na tela Crie sua conta apresentar uma máscara como guia no campo Telefone Ex.: (00) 00000-0000

Severidade: 

Prioridade:


