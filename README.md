⚙️ Configuração de Recursos e Dimensionamento na Azure

Este projeto considera o uso de Máquinas Virtuais (VMs) na Microsoft Azure, com foco em desempenho, escalabilidade e otimização de custos.

🔧 Recursos Configuráveis

Tamanho da VM: escolha baseado no tipo de carga (ex: séries B, D, E, F, N).

CPU e Memória: definidos pelo tamanho da VM.

Discos: SSDs para sistema e dados (Standard ou Premium).

Rede: configuração de IP, VNet e regras de segurança (NSG).

Extensões/Scripts: automação de inicialização e gerenciamento.

📈 Dimensionamento

Vertical (Scale-up): ajuste manual de CPU/RAM para uma VM.

Horizontal (Scale-out): uso de VM Scale Sets com autoescala conforme demanda.

🔄 Autoescala

Configurável por métricas (ex: uso de CPU).

Definição de regras e limites (mínimo e máximo de instâncias).

💰 Otimização de Custo

Utilização de Azure Advisor para sugestões de economia.

Opção de Instâncias Reservadas para workloads previsíveis.
