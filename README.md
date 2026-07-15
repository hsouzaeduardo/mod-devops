# mod-devops
Modulo aula devops lowcode

## Informações sobre APIs

APIs (Application Programming Interfaces) permitem que diferentes aplicações se comuniquem de forma padronizada.

### Principais Conceitos
- **REST (Representational State Transfer):** O padrão mais comum na web, utilizando métodos HTTP (GET, POST, PUT, DELETE).
- **Endpoint:** O endereço (URL) onde o serviço da API pode ser acessado.
- **JSON (JavaScript Object Notation):** O formato de dados mais utilizado para troca de informações entre o cliente e o servidor.
- **Autenticação:** Geralmente feita via tokens (ex: JWT ou API Keys) para garantir a segurança dos dados.

### APIs em Low-code e DevOps
No contexto de ferramentas Low-code e práticas de DevOps, as APIs são essenciais para:
1. **Integração:** Conectar ferramentas de automação (como GitHub Actions) com serviços de nuvem.
2. **Extensibilidade:** Permitir que plataformas low-code consumam dados de bancos de dados externos ou microserviços.
3. **Monitoramento:** Coletar métricas de performance e logs de execução.
### Gerenciamento de APIs
Além da integração, o uso de um **API Gateway** é uma prática comum em DevOps para centralizar o controle de tráfego, aplicar políticas de segurança (como rate limiting) e facilitar a governança das APIs consumidas por aplicações low-code. Isso garante que a comunicação entre sistemas seja resiliente e escalável.
