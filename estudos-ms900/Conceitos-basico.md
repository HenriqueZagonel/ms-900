# -Estudos-MS-900
 Estudos MS-900

## Conceitos de computação em nuvem 
### O que é computação em nuvem
Computação em nuvem, ou simplemente "nuvem", refere-se à entrega de serviçõs de computação pela internet(a "nuvem"). Isso inclui uma variedade de recursos, como armazenamento, servidores, banco de dados, redes, software e mais, tudo fornecido de forma remota por provedores de nuvem como Microsoft Azure, AWS(Amazon Web Service) e Google Cloud.

#### Conceitos básicos:
- **On-demand self-service**: Usuários podem acessar recursos de computação sob demanda sem a necessidade de interação humana com o provedor de serviço.
- **Broad network acess**: Os serviço são acessiveis pela rede através de dispositivos padrões, como laptops, smartphones e tablets.
- **Resource pooling**: Provedores de nuvem usam o modelo de multitenant para servir múltiplos clientes, alocando dinamicamente e realocando recursos físicos e virtuais de acordo com a demanda dos clientes.
- **Rapid elasticity**: Capacidade de escalar rapidamente para fora e para dentro conforme necessário. Para o consumidor, os recursos muitas vezes parecem ilimitados e podem ser comprados em qualquer quantidade a qualquer momento.
- **Measured service**: Sistemas de nuvem automaticamente controlam e otimizam o uso de recursos através de uma capacidade de medição, fornecendo transparência tanto para o provedor quanto para o consumidor dos serviços utilizados.

![Descrição da Imagem](./images/cloud_computing_wide_resized.png)
## Tipos de serviços
### Infrastructure as a Service (IaaS):
  - **Descrição**: Fornece infraestrutura virtualizada pela internet. Inclui recursos como servidores, armazenamento e redes.
  - **Exemplos**: Microsoft Azure, Amazon Web Services (AWS) EC2.
  - **Uso Comum**: Hospedagem de sites, desenvolvimento e testes, análise de dados, backup e recuperação.

### Platform as a Service (PaaS):
  - **Descrição**: Fornece uma plataforma e ambiente para desenvolver, testar e gerenciar aplicativos. Inclui infraestrutura e também ferramentas de desenvolvimento.
  - **Exemplos**: Microsoft Azure App Services, Google App Engine.
  - **Uso Comum**: Desenvolvimento e implantação rápida de aplicativos, análise de dados em tempo real, serviços de middleware.

### Software as a Service (SaaS):
  - **Descrição**: Fornece software por meio da internet. Usuários acessam aplicações diretamente pela web, sem necessidade de instalação.
  - **Exemplos**: Microsoft Office 365, Google Workspace.
  - **Uso Comum**: E-mail, gerenciamento de relacionamento com clientes (CRM), aplicativos empresariais e colaboração.

## Responsabilidades
![Descrição da Imagem](./images/Responsabilidades.png)

## Benéficios da computação em nuvem
### Economia de de Custos: 
  - Redução de despesas com hardware e manutenção;
  - Pagamento apenas pelos recursos utilizados(modelo pay-as-you-go)
  - Eliminação de custos associados a atualizações e manutenção de infraestrutura.
### Escalabilidade:
  - Capacidade de escalar rapidamente os recursos conforme a demanda.
  - Facilita o crescimento da empresa sem grandes investimentos em infraestrutura.
### Flexibilidade e Mobilidade:
  - Acesso a recursos e dados de qualquer lugar, a qualquer momento, com uma conexão à internet.
  - Facilita o trabalho remoto e a colaboração entre equipes distribuídas geograficamente.
### Desempenho e Confiabilidade:
  - Infraestrutura robusta e de alta performance fornecida por grandes provedores.
  - Melhorias constantes em hardware e software, sem interrupções para o usuário.
### Segurança:
  - Implementações de segurança avançadas e atualizações automáticas.
  - Provedores de nuvem investem pesadamente em segurança para proteger os dados dos clientes.
### Recuperação de  desastres:
  - Soluções integradas de backup e recuperação de desastres.
  - Maior resiliência a falhas e perda de dados.
### Inovação e Agilidade:
  - Acesso rápido a novas tecnologias e ferramentas.
  - Capacidade de experimentar e implementar novas soluções com rapidez.

## Tipos de nuvem
### Nuvem Pública:
  - **Descrição**: A infraestrutura de nuvem é propriedade de um provedor de serviços de nuvem e é oferecido ao público em geral ou a uma grande indústria.
  - **Exemplos**: Microsoft Azure, Amazon Web Services(AWS), Google Cloud.
  - **Benefícios**: Custo reduzido, alta escalabilidade e manutenção gerenciada pelo provedor.
### Nuvem Privada:
  - **Descrição**: A infraestrutura de nuvem é operada exclusivamente para uma única organização. Pode ser gerenciada pela própria organização ou por um terceiro e pode estar dentro do local(on-premises) ou fora do local.
  - **Exemplos**: Nuvens privadas construídas com tecnologias como Microsoft Azure Stack, VMware.
  - **Benefícios**: Maior controle e segurança, conformidade com regulamentos e personalização de acordo com as necessidade específicas da organização.
### Nuvem Híbrida:
  - **Descrição**: Combina nuvens públicas e privadas, permitindo que dados e aplicações sejam compartilhadas entre elas.
  - **Exemplos**: Implantações que utilizem tanto nuvem privada como pública.
  - **Benefícios**: Flexibilidade, permitindo que as organizações aproveitem a escalabilidade da nuvem pública enquanto mantêm a segurança e o controle da nuvem privada. Ideal para cargas de trabalho dinâmicas e mutáveis.

## Vantagens dos serviços em nuvem
### Custo Reduzido:
  - Economia de despesas de capital(capex)com hardware e infraestrutura.
  - Modelo de pagamento conforme o uso(pay-as-you-go).
### Escalabilidade:
  - Fácil aumento ou diminuição de recursos conforme necessário.
  - Capacidade de lidar com picos de demanda sem problemas.
### Flexibilidade e Mobilidade:
  - Acesso a dados e aplicativos de qualquer lugar com uma conexão à interneet.
  - Suporte para trabalho remoto e colaboração.
### Desempenho e confiabilidade:
  - Infraestrutura de alta qualidade mantida por grandes provedores.
  - Garantia de disponibilidade e backups automáticos.
### Segurança:
  - Provedores investem em medidas de segurança avançadas.
  - Acesso a tecnologias de segurança mais recentes.
### Inovação Rápida:
  - Acesso a novas tecnologias e atualizações sem precisar fazer upgrades manuais.
  - Capacidade de testar e implementar soluções rapidamente.
## Desvantagens dos Serviços em Nuvem
### Dependência de Conexão à Internet:
  - Necessidade de uma conexão estável e rápida à internet para acessar serviços.
  - Possíveis problemas de latência.
### Controle Limitado:
  - Menor controle sobre a infraestrutura subjacente.
  - Dependência do provedor para manutenção e suporte.
### Custo Contínuo:
  - Custo de operação continuos que podem aumentar com o tempo.
  - Possíveis surpresas com cobranças adicionais.
### Downtime:
  - Risco de interrupções de serviço devido a problemas no provedor.
  - Dependência do provedor para resolver problemas rapidamente.

## Conceito de trabalho hibrido e flexivel
### Trabalho Híbrido
  - **Definição**: O Trabalho híbrido é um modelo de trabalho que combina trabalho remoto e trabalho no local de trabalho físico. Os funcionários têm a flexibilidade de trabalhar em casa ou de outro lugar remoto, assim como no escritório, dependendo das necessidades da empresa e das preferências pessoais.
### Características:
  - **Flexibilidade de Localização**: Permite que os funcionários escolham onde trabalhar, seja em casa, em um café ou no escritório.
  - **Horários de Trabalho Ajustáveis**: Possibilidades de ajustar horários de trabalho para equilibrar melhor a vida pessoal e profissional.
  - **Uso de Tecnologia**: Requer ferramentas digitais e plataformas de colaboração para conectar equipe remotas e no escritório.
### Trabalho Flexível
   - **Definição**:O trabalho flexível é um conceito mais amplo que inclui qualquer forma de flexibilidade no trabalho, seja em termos de horário, local ou carga de trabalho. Pode incluir teletrabalho, trabalho por horas flexiveis, trabalho por projeto, entre outros.
### Características:
  - **Flexibilidade de Horário**: Permite que os funcionários ajustem suas horas de trabalho de acordo com suas necessidades pessoais e demandas do trabalho. 
  - **Localização Variável**: Inclui a opção de trabalhar remotamente ou em diferente locais.
  - **Adaptabilidade**: Pode incluir a capacidade de ajustar a carga de trabalho ou responsabilidades com base em circunstâncias pessoais ou profissionais.

## Benefícios de Ambos os Modelos
  - **Equilíbrio entre Vida Pessoal e Profissional**: Ajuda funcionários a gerenciarem melhor suas responsabilidades pessoais e profissionais.
  - **Aumento de produtividade**: Flexibilidade pode levar a uma maior satisfação no trabalho e produtividade.
  - **Atraçãoe Rentenção de Talentos**: Empresas que oferecem opções de trabalho híbrido e flexível tendem a atrair e reter melhores talentos.
    
  - 
