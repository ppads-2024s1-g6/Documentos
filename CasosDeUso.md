![Use case diagram](https://github.com/ppads-2024s1-g6/Documentos/assets/85592905/b65caf3c-282d-44a0-a4e1-ec491f68e36f)

# Logar no Sistema

|**Nome**|Logar no sistema|
| :- | :- |
|**Atores**| Usuário |
|**Sumário**|O usuário cria um perfil na plataforma|
|**Complexidade**|Simples|
|**Pré-condições**|O Usuário tem dados suficientes para a criação da conta|
|**Pós-condição**||

## Fluxo Principal

|**Fluxo Principal**||
| :-: | :- |
|**Ações do Ator**|**Ações do Sistema**|
|1\. O Usuário acessa o site| |
|2\. O Usuário acessa a página de login.||
| |3\. O Sistema mostra ao usuário os dados que devem ser preenchidos.|
|4\. O Usuário preenche os dados necessários.| |
|5\. O Usuário confirma a ação.||
||6\. O Sistema valida os dados.|

## Fluxo de Exceção 1

|**Fluxo de Exceção 1: 4a) Sistema não reconhece algum dado do usuário como válido**||
| :-: | :- |
|**Ações do Ator**|**Ações do Sistema**|
| |4\.1. O Sistema informa o usuário que tal dado está errado|
| |4\.2. Enquanto o usuário não corrigir o dado, o fluxo é interrompido|


# Criar Conta

|**Nome**|Criar conta|
| :- | :- |
|**Atores**| Usuário|
|**Sumário**|O usuário criará sua conta no site|
|**Complexidade**|Fácil|
|**Pré-condições**||
|**Pós-condição**||
## <a name="_ih2ttmwxlfyb"></a>Fluxo Principal

|**Fluxo Principal**||
| :-: | :- |
|**Ações do Ator**|**Ações do Sistema**|
|1\. O Usuário acessa o site||
|2\. O usuário seleciona a opção de criar uma conta||
||3\. O sistema apresenta os campos para o usuário preencher com os dados necessários.|
|4\.. O Usuário preenche os dados necessários.||
|5\. O Usuário confirma a ação.||
||6\. O Sistema valida os dados.|
| |7\. O Sistema armazena os dados e ativa a conta.|
## <a name="_8mt7zwlo36bs"></a>Fluxo de Exceção 1

|**Fluxo de Exceção 1: 5a O Sistema não reconhece algum dado do usuário como válido**||
| :-: | :- |
|**Ações do Ator**|**Ações do Sistema**|
| |1\. O Sistema informa o usuário que tal dado está errado|
| |2\. Enquanto o usuário não corrigir o dado, o fluxo é interrompido|

# Consultar Obras

|**Nome**|Consultar obras|
| :- | :- |
|**Atores**|Usuário|
|**Sumário**|O usuário cria um perfil na plataforma|
|**Complexidade**|Simples|
|**Pré-condições**|O Usuário tem dados suficientes para a criação da conta|
|**Pós-condição**||

## Fluxo Principal

|**Fluxo Principal**||
| :-: | :- |
|**Ações do Ator**|**Ações do Sistema**|
|1\. O usuário acessa o site.||
||2\. O sistema apresenta obras cadastradas no banco de dados.|
|3\. O usuário escolhe a obra que deseja.||
||4\. O sistema leva o usuário a outra página que apresenta informações detalhadas sobre a obra.|

## Fluxo Alternativo 1

|**Fluxo Alternativo 1: 3a Usuário pesquisa uma obra pelo nome**||
| :-: | :- |
|**Ações do Ator**|**Ações do Sistema**|
|1\. O usuário digita o nome da obra pesquisa.||
||2\. O sistema apresenta as obras cadastradas no banco de dados.|
|3\. O usuário escolhe a obra que deseja.||

# Visualizar Perfil de Usuários

|**Nome**|Visualizar Perfil de Usuários|
| :- | :- |
|**Atores**|Usuário|
|**Sumário**|O usuário pode consultar o perfil de outros usuários|
|**Complexidade**|Simples|
|**Pré-condições**||
|**Pós-condição**||
## Fluxo Principal

|**Fluxo Principal**||
| :-: | :- |
|**Ações do Ator**|**Ações do Sistema**|
|1\. O usuário pesquisa pelo nome de outro usuário.||
|2\. O usuário acessa a página de configuração de conta.||
||3\. O sistema apresenta os dados do usuário|
|4\. O usuário altera as informações desejadas.||
||5\. O sistema armazena as alterações do usuário.|

# Adicionar Amigos

|**Nome**|Adicionar amigos|
| :- | :- |
|**Atores**|Usuário|
|**Sumário**|O usuário adiciona outro usuário como amigo|
|**Complexidade**|Médio|
|**Pré-condições**|O usuário necessita saber o username do usuário solicitado|
|**Pós-condição**|O usuário solicitado precisa aceitar a solicitação|
## <a name="_ruj6umi80ldk"></a>Fluxo Principal

|**Fluxo Principal**||
| :-: | :- |
|**Ações do Ator**|**Ações do Sistema**|
|1\. O usuário pesquisa o nome do perfil que ele deseja adicionar||
||2\. O sistema mostra o perfil desejado|
|3\. O usuário acessa o perfil que ele deseja adicionar.||
|4\. O usuário aperta o botão e envia a solicitação de amizade||
||5\. O sistema envia a solicitação para o perfil solicitado.|



**Fluxo de Exceção 1**

|**Fluxo Exceção 1: 2a O sistema não encontra o perfil**||
| :-: | :- |
|**Ações do Ator**|**Ações do Sistema**|
||1\. O sistema não encontra o perfil no banco de dados|

# Compartilhar Avaliação

|**Nome**|Compartilhar avaliação|
| :- | :- |
|**Atores**|Usuário|
|**Sumário**|O usuário compartilha a sua opinião sobre uma obra|
|**Complexidade**|Simples|
|**Pré-condições**|O usuário precisa estar logado.|
|**Pós-condição**||
## Fluxo Principal

|**Fluxo Principal**||
| :-: | :- |
|**Ações do Ator**|**Ações do Sistema**|
|1\. O usuário seleciona uma obra.||
||2\. O sistema apresenta todos os detalhes dessa obra escolhida.|
|3\. O usuário avalia a obra.||
||4\. O sistema registra a avaliação do usuário.|

## Fluxo Alternativo 1

|**Fluxo Alternativo 1: 3a O usuário comenta sobre sobre uma obra**||
| :-: | :- |
|**Ações do Ator**|**Ações do Sistema**|
|1\. O usuário digita seu comentário.||
|2\. O usuário confirma envio de comentário.||
||3\. Sistema registra resposta em banco de dados.|

# Visualizar Perfil Pessoal

|**Nome**|Visualizar Perfil Pessoal|
| :- | :- |
|**Atores**|Usuário|
|**Sumário**|O usuário pode visualizar seu próprio perfil|
|**Complexidade**|Simples|
|**Pré-condições**|O usuário precisa estar logado.|
|**Pós-condição**||
## Fluxo Principal

|**Fluxo Principal**||
| :-: | :- |
|**Ações do Ator**|**Ações do Sistema**|
|1\. O usuário acessa a sua página pessoal||
||2\. O sistema apresenta o nome de usuário, seus amigos e obras as quais o usuário avaliou.|
|3\. O usuário avalia a obra.||
||4\. O sistema registra a avaliação do usuário.|
# Alterar Dados Pessoais

|**Nome**|Alterar dados pessoais|
| :- | :- |
|**Atores**|Usuário|
|**Sumário**|O usuário altera informações sobre sua conta/perfil|
|**Complexidade**|Simples|
|**Pré-condições**|O usuário precisa estar logado.|
|**Pós-condição**|Os dados devem ser válidos.|
## <a name="_n54j225xer6b"></a>Fluxo Principal

|**Fluxo Principal**||
| :-: | :- |
|**Ações do Ator**|**Ações do Sistema**|
|1\. O usuário acessa sua página de perfil.||
|2\. O usuário acessa a página de configuração de conta.||
||3\. O sistema apresenta os dados do usuário|
|4\. O usuário altera as informações desejadas.||
||5\. O sistema verifica os dados atualizados.|
||6\. O sistema armazena as alterações do usuário.|

## Fluxo Alternativo 1

|**Fluxo Alternativo 1: 5a. Dados inválidos**||
| :-: | :- |
|**Ações do Ator**|**Ações do Sistema**|
||1 O sistema reconhece os dados atualizados como inválidos.|
||2 O sistema informa o usuário da invalidez, e solicita alteração.|


# Gerenciar Obras

|**Nome**|Gerenciar Obras|
| :- | :- |
|**Atores**|Administrador|
|**Sumário**|O administrador pode adicionar, alterar ou apagar obras.|
|**Complexidade**|Simples|
|**Pré-condições**|O administrador precisa estar logado.|
|**Pós-condição**||

**8.1**

|**Fluxo Principal**||
| :-: | :- |
|**Ações do Ator**|**Ações do Sistema**|
|1\. O Administrador acessa a página.||
|2\. O Administrador acessa sua conta de administração||
||3\. O sistema exibe a página inicial do site.|
|4\. O administrador acessa sua página de perfil.||
|5\. O administrador acessa a aba de administração||
||6\. O sistema exibe a página de administração|
|7\. O administrador adiciona, altera e remove filmes, séries e livros.||
||8\. O sistema armazena as alterações no banco de dados.|


