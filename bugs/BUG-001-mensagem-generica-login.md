# CT-001 – Validar login com campo senha em branco

## Descrição
Validar o comportamento do sistema ao tentar realizar login sem o preenchimento do campo obrigatório Senha, garantindo que o acesso seja negado e que o usuário receba uma mensagem clara e orientativa.

## Pré-condições
- Usuário não autenticado
- Sistema disponível

## Ambiente
- Sistema: Portal do Servidor – Prefeitura de São Paulo do Potengi  
- Plataforma: Web  
- Acesso: Página de login  

## Passos para reprodução
1. Acessar o site da Prefeitura de São Paulo do Potengi  
2. Clicar na aba **Portal do Servidor**  
3. Informar um número de matrícula válido  
4. Deixar o campo **Senha** em branco  
5. Clicar no botão **Entrar**

## Resultado esperado
- O sistema deve negar o acesso  
- Deve ser exibida uma mensagem clara informando que o campo **Senha** é obrigatório  

## Resultado obtido
- O sistema nega o acesso  
- É exibida uma mensagem genérica, sem indicar qual campo está incorreto ou ausente  

## Observações
O comportamento atende parcialmente à funcionalidade de bloqueio de acesso, porém falha na comunicação com o usuário, impactando a experiência de uso.


