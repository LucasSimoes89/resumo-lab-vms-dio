# resumo-lab-vms-dio
Este é um repositório que contém um resumo do que foi aprendido no lab de máquinas virtuais da DIO

Abaixo seguem os tópicos importantes abordados durante o lab;

Valores SLA
Importante saber quanto cada SLA pode ter de inatividade aceitável por semana/mês/ano. Não necessariamente o serviço vai ficar disponível, mas caso fique este é um tempo aceitável.
Caso o tempo seja maior, Microsoft ressarce o valor através de voucher.

Máquinas Virtuais
Ao criar uma máquina virtual a Microsoft oferece opções de gerenciamento de disponibilidade onde é possível definir uma configuração onde protege os aplicativos e dados de interrupções.
Cada opção de disponibilidade irá implicar em uma SLA diferente. Para que seja consultada a SLA é necessário ir até a documentaçãoa através do link no helper da opção de Opções de Disponibilidade.

Contas de armazenamento
Há opções de amazenamento de dados divididos em: Armazenamento com redundância local, geográfica e redundância de zona.
Esta replicação de dados em datacenter e/ou regiões faz com que a SLA aumente e haja um menor tempo de indisponibilidade do serviço.
Isto implica diretamente em custo pois haverá uma alta disponibilidade do serviço contratado, dessa forma é preciso avaliar datalhadamente o propósito da criação do recurso para que seja utilizado o orçamento com eficiência

