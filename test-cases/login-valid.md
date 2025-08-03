# Caso de Teste: TC01 - Login com credenciais válidas

## Objetivos
Verificar se o usuário consegue realizar login com credenciais válidas no site [SauceDemo](https://www.saucedemo.com).

--- 
 ## Pré-condições
 - Acesso à internet
 - Navegador instalado (Chrome, Firefox, etc.)
 - Site SauceDemo acessível
 - Usuário de teste existente:
 - **Usuário:** `standard_user`
 - **Senha:** `secret_sauce`

   ---

   ## Passos para execução

   1. Acessar o site [https://www.saucedemo.com]
   2. Inserir o nome de usuário `standard_user`
   3. Inserir a senha `secret_sauce`
   4. Clicar no botão **Login**
  
   ---

   ## Resultado Esperado
   Usuário é redirecionado para página de produtos: `https://www.saucedemo.com/inventory.html`

   ---

   ## Resultado Obtido
   *(Preencher após executar o teste)*

   ---

   ## Status
   - [] passou
   - [] Falhou
  
   ---

   ## Evidências
<img width="1235" height="731" alt="Captura de Tela 2025-08-03 às 20 40 42" src="https://github.com/user-attachments/assets/025375a8-9d8d-48d6-b22a-09b6bdc21efe" />
<img width="838" height="663" alt="Captura de Tela 2025-08-03 às 20 42 23" src="https://github.com/user-attachments/assets/c70da278-e2dc-4483-93ad-78609eb412f0" />

   ## Observações
  -Para nome de usuários, existem mais opções, como: standard_user, locked_out_user, problem_user, performance_glitch_user. Mas, apenas standard_user é valida
