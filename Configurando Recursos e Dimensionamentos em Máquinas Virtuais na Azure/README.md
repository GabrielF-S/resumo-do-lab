# Desafio de Projeto Microsoft Azure
## Configurando Recursos e Dimensionamentos em Máquinas Virtuais na Azure

## Computação e Serviço de Rede
A computação em nuvem e os serviços de rede têm sido pilares da transformação digital, e o Azure oferece ferramentas robustas para atender a diversas demandas empresariais. Entre os principais recursos destacam-se as Máquinas Virtuais, que facilitam a instanciação e o gerenciamento de ambientes virtuais. O processo de criação é simplificado com opções predefinidas, sugestões baseadas em cenários de uso e a possibilidade de definir imagens padronizadas para empresas, garantindo conformidade com normas internas. Além disso, a escolha de regiões, como US East 2, oferece vantagens financeiras devido aos custos reduzidos.
Outra funcionalidade interessante são as instâncias Azure Spot, que permitem alocar recursos a um custo menor, embora sujeitas a desligamento em caso de maior demanda por outros usuários. O Azure também apresenta escalabilidade, ferramentas de monitoramento configuráveis e suporte para múltiplos backups diários, tornando o ambiente mais eficiente e seguro. Para facilitar a identificação de custos, a utilização de tags é altamente recomendada, além de boas práticas como a exclusão de discos ao remover máquinas virtuais.
No âmbito das áreas de trabalho virtuais, o Azure possibilita a criação de imagens personalizadas que oferecem acesso direto aos aplicativos necessários. Há também flexibilidade na configuração, seja para uso pessoal, destinado a usuários com necessidades específicas, ou em pool, com múltiplos usuários compartilhando o mesmo host dentro de limites predefinidos.
Já os Aplicativos de Função destacam-se por sua versatilidade, permitindo a escolha de pilhas de runtime otimizadas para diferentes linguagens de programação e sistemas operacionais. Com diversas opções de hospedagem, esses aplicativos demandam uma conta de armazenamento, integrando funcionalidades que atendem aos mais diversos requisitos técnicos.
Com essas ferramentas, o Azure se consolida como uma solução abrangente e eficiente para empresas que buscam impulsionar suas operações na nuvem, com economia, segurança e flexibilidade

### Máquinas Virtuais - Máquina Virtual do Azure
- Instanciação simplificada com campos predefinidos e sugestões de tipos de máquina para cenários específicos.
- Requer um grupo de recursos para criação.
- Permite criar imagens padrão seguindo as normas e padrões da empresa.
- Região US East 2 oferece menor custo.
- Suporte para escalonamento padrão adicionado.
- Instâncias Azure Spot: alocação de recursos por menor custo, sujeitas a desligamento caso haja demanda pelo preço cheio.
- Visualização de tamanhos e famílias recomendados para uso ideal.
- Recomenda-se apagar o disco ao excluir a VM.
- Criação automática de sub-rede caso não exista na mesma região.
- Capacidade de configurar múltiplos backups diários.
- Habilitação de regras de monitoramento disponível.
- Utilização de tags para identificar produtos cobrados com facilidade.

### Área de Trabalho no Azure
- Criação de imagens que permitem acesso direto aos aplicativos.
- Configuração de área de trabalho pessoal ou em pool:- Pessoal: Aplicações específicas exclusivas para um usuário.
- Pool: Limite máximo de usuários por host.


### Aplicativo de Função
- Seleção de pilha de runtime que sugere o sistema operacional ideal.
- Opções de hospedagem disponíveis.
- Exige conta de armazenamento.



