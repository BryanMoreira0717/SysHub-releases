# Privacidade

O SysHub roda inteiramente no seu PC.

- **Sem telemetria, sem contas, sem anúncios.** Nenhuma leitura de hardware, histórico, processo ou dispositivo é enviada para fora do computador.
- **Dados locais:** configurações em `%AppData%\SysHub\settings.json`; histórico, perfis e alertas em `%LocalAppData%\SysHub\syshub.db`; logs em `%LocalAppData%\SysHub\logs` (sem dados pessoais além de nomes de dispositivos e programas). O histórico é apagado automaticamente depois do período escolhido (1 a 30 dias).
- **Conexões de rede que o app faz:**
  - **Ping** para o endereço configurado (padrão `1.1.1.1`), só enquanto a tela Rede ou o overlay com a métrica Ping estão abertos.
  - **IP público**, só se você ligar essa opção (desligada por padrão).
  - **Atualizações:** consulta às releases do repositório público de downloads (`github.com/BryanMoreira0717/SysHub-releases`) ao iniciar e a cada 24 h (pode ser desligada em Configurações → Atualizações). Nada é baixado sem você pedir.
- **Desinstalação:** remove o app e a tarefa de "Iniciar com o Windows". Para apagar também os seus dados, exclua as pastas `%AppData%\SysHub` e `%LocalAppData%\SysHub`.
