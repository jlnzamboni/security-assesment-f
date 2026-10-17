Security Assessment Framework (PMEs)

Framework prático e metodológico para levantamento de inventário, mapeamento de vulnerabilidades e endurecimento (hardening) de infraestruturas de tecnologia para pequenas e médias empresas (PMEs).

🎯 Objetivo do Projeto
Demonstrar a aplicação de metodologias de Blue Team e análise de riscos corporativos, estruturando uma auditoria preventiva para mitigar ameaças como ransomware, acessos não autorizados e falhas de configuração em ambientes corporativos e de logística.

🔍 Fases da Metodologia de Assessment

1. Descoberta e Inventário de Ativos (Discovery)
Mapeamento de hosts, IPs ativos e serviços expostos na rede local e perímetro.
Identificação de endpoints (computadores, servidores, roteadores, dispositivos móveis).
Ferramentas de Apoio: Nmap, inventário de diretório ativo e varredura de portas.

2. Análise de Vulnerabilidades (Vulnerability Scanning)
Varredura profunda em busca de desatualizações de sistema, softwares obsoletos e falhas conhecidas (CVEs).
Verificação de configurações incorretas (misconfigurations) em serviços de rede e compartilhamentos.
Ferramentas de Apoio: Nessus, Greenbone OpenVAS, Microsoft Defender Vulnerability Management.

3. Proteção de Identidades e Acesso (Identity & Access Management)
Implementação de políticas de Acesso Condicional.
Obrigatoriedade de Autenticação Multifator (MFA / 2FA).
Monitoramento de comportamentos anômalos e tentativas de login suspeitas via ecossistema de identidade em nuvem.

4. Resposta e Contenção (Endpoint Detection & Response - EDR)
Isolamento automático de máquinas comprometidas.
Monitoramento contínuo de processos maliciosos e tráfego lateral na rede.
Ferramentas de Apoio: Microsoft Defender for Endpoint, Wazuh (SIEM).
📊 Matriz de Criticidade de Riscos

Nível de Risco
Descrição Técnica
Ação Imediata de Remediação
Crítico
Falhas que permitem execução remota de código ou acesso irrestrito a bancos de dados.
Correção de patch imediata e isolamento do ativo.
Alto
Contas sem MFA, portas administrativas expostas para a internet sem proteção.
Aplicação de regras de Acesso Condicional e hardening.
Médio/Baixo
Softwares com atualizações pendentes sem exploração ativa conhecida.
Cronograma de atualização regular planejado.

🛠️ Como Utilizar este Framework
Este repositório serve como modelo padrão de escopo para consultorias de segurança preventiva em ambientes corporativos enxutos.
