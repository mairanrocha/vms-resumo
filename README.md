☁️ Azure VM – Configuração e Dimensionamento
Este projeto utiliza Máquinas Virtuais (VMs) na Azure, com foco em performance, escalabilidade e controle de custos.

🔧 Recursos Configuráveis
Tamanho da VM: escolha entre séries como B, D, E, F, N, de acordo com a carga de trabalho.

vCPU e RAM: definidas pelo tipo da VM.

Discos:

Sistema operacional: SSD (Standard/Premium)

Dados: discos adicionais conforme a necessidade

Rede:

IP público/privado

VNet (rede virtual)

NSG (grupo de segurança de rede)

Extensões e scripts: para automação no provisionamento.

📊 Dimensionamento (Scaling)
Vertical (Scale-up): aumento de CPU/memória na mesma VM.

Horizontal (Scale-out):

Uso de VM Scale Sets para replicar instâncias.

Ideal para aplicações com alta demanda e distribuição de carga.

⚙️ Autoescala (Autoscale)
Baseada em métricas como uso de CPU, memória ou fila de mensagens.

Regras configuráveis (ex: criar nova instância se CPU > 70% por 5 min).

Definição de mínimo e máximo de instâncias.

💸 Otimização de Custos
Azure Advisor: recomendações automáticas de desempenho e economia.

Instâncias Reservadas: até 72% de economia para uso contínuo.

Monitoramento de consumo com Azure Cost Management.
