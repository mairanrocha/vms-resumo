🔧 1. Escolha do Tamanho da Máquina Virtual (VM Size)
A Azure oferece diversos tamanhos de VMs, agrupados em séries, cada uma voltada para cenários diferentes:

Série B (Burstable): ideal para cargas leves e intermitentes.

Série D (Geral): equilibrada entre CPU e memória, boa para aplicações de uso geral.

Série E: mais memória, para bancos de dados e cache.

Série F: mais CPU, para cargas com uso intenso de processamento.

Série N: com GPU, voltadas para gráficos, IA e machine learning.

Série H: computação de alto desempenho (HPC).

Série L: para armazenamento e bancos de dados com alto IOPS.

👉 Dica: você pode trocar o tamanho da VM depois, desde que ela esteja desligada e dentro da mesma família compatível.

⚙️ 2. Recursos Configuráveis
Durante a criação ou atualização de uma VM, você pode configurar:

CPU (vCPU): núcleos virtuais atribuídos à VM.

Memória RAM: varia com o tamanho escolhido.

Disco OS: disco do sistema operacional, geralmente SSD (Standard ou Premium).

Disco de dados: para armazenar arquivos ou bases de dados.

Rede (NIC): configurações de IP público, VNet e NSG (Security Group).

Extensões e scripts de inicialização: para automação.

📈 3. Dimensionamento Vertical e Horizontal
Dimensionamento vertical: aumentar os recursos da mesma VM (ex: mais RAM ou CPU).

Feito manualmente ou com escalonamento automático baseado em métricas.

Dimensionamento horizontal (escalabilidade):

VM Scale Sets: permite criar um conjunto de VMs que aumentam/diminuem conforme a demanda.

Ideal para aplicações distribuídas (como web servers, microsserviços).

🔄 4. Autoescala (Autoscaling)
Pode ser configurado para escalar com base em:

CPU, uso de memória, fila de mensagens, etc.

Defina:

Regras de escalonamento (ex: “se CPU > 70% por 5 min, criar nova instância”)

Mínimo e máximo de instâncias

💰 5. Custo e Otimização
Escolher o tamanho correto impacta diretamente no custo.

Azure oferece reservas de instâncias (VM Reserved Instances) com desconto para uso de longo prazo.

Ferramentas como o Azure Advisor sugerem otimizações de recursos.

📋 Resumo das Boas Práticas
Recurso	Boas Práticas
Tamanho da VM	Escolha baseado na carga da aplicação
Disco	Use Premium SSDs para alto desempenho
Autoescala	Configure em VMs para aplicações variáveis
Custo	Revise uso com Azure Advisor e Budget
Rede	Use NSG e VNet para segurança e performance
