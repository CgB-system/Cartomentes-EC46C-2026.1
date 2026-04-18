
## 1. Requisitos Funcionais

A Tabela 1, tem como função, exibir todo os Requisitos Funcionais (RF) presentes nos componentes de login do sistema.

| ID   | Requisito                                                                               | Prioridade | Requisitos Relacionados |
| ---- | --------------------------------------------------------------------------------------- | ---------- | ----------------------- |
| RF01 | O sistema deve permitir o cadastro de usuários com e-mail e senha.                      | Alta       | RF02                    |
| RF02 | O sistema deve validar se o e-mail informado já está cadastrado no momento do registro. | Alta       | RF01                    |
| RF04 | O sistema deve permitir autenticação de usuários via e-mail e senha.                    | Alta       | RF05                    |
| RF05 | O sistema deve validar as credenciais informadas durante o login.                       | Alta       | RF04                    |
| RF06 | O sistema deve permitir o encerramento de sessão (logout) do usuário autenticado.       | Média      | RF04, RF05              |
| RF08 | O sistema deve exibir mensagens de erro em caso de credenciais inválidas.               | Média      | RF05                    |
| RF09 | O sistema deve manter a sessão ativa enquanto o usuário estiver autenticado.            | Média      | RF04, RF05              |

**Tabela 1:** Requisitos Funcionais do Sistema de Login.

[Retornar para Requisitos de Usuário](RequisitosUsuario) 
