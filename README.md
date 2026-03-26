# Cria-o-de-Novo-Usu-rio-no-Active-Directory
Criação de Novo Usuário no Active Directory
Fluxo para a criação de novos usuários no Active Directory, fazendo uso de credenciais de administração do domínio.

Elimine a atividade de criar usuário no AD, usando esse fluxo para automatizar esse processo.

Sobre este fluxo de automação:
Este fluxo permite a criação de usuários no Active Directory (AD) tendo como entrada os seguintes dados de input:
Nome do usuário, Nome completo, CPF, RG, Gestor Imediato, Cargo, Departamento, Empresa, Centro de Custo , Local (Path na UO) e Senha sugerida.
O processo primeiro verifica se o usuário ja existe no AD, caso não existe prossegue para a criação respeitando o DE PARA que está no step Adicionando Atributos dos dados do usuário e os atributos do AD.

<img width="417" height="332" alt="image" src="https://github.com/user-attachments/assets/d3b1d8af-5c90-4308-8ed3-462ed9dddae6" />
