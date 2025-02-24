# 📚 resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO.

---

# ☁️ Tipos de Nuvem

## 🌐 Nuvem Pública
Infraestrutura compartilhada por múltiplos usuários e gerenciada por um único provedor.

**Exemplo:** AWS, Azure, Oracle, Google Cloud, ...

## 🏢 Nuvem Privada
Infraestrutura exclusiva para uma organização, podendo estar on-premises ou hospedada por terceiros.

**Exemplo:** VMware Private Cloud, OpenStack, Azure Stack

## 🔄 Nuvem Híbrida
Combinação de nuvem pública e privada, permitindo integração e migração de cargas de trabalho.

**Exemplo:** AWS Outposts, Azure Arc, Google Anthos

---

# 💰 Diferenças entre CapEx e OpEx

## 💸 Despesas de Capital (CapEx)
É o gasto inicial de dinheiro em infraestrutura física. As despesas de CapEx têm um valor que se reduz com o tempo.

## 🧾 Despesas Operacionais (OpEx)
Gastar com produtos e serviços conforme o necessário, pagamento conforme o uso. A cobrança é feita imediatamente.

# ⚡ Modelo baseado em Consumo (pay-as-you-go)
- Melhor previsão de custos.
- São fornecidos preços para recursos e serviços individuais.
- A cobrança é feita com base no seu uso real.

---

# 🧠 Conceitos Importantes

## 🔐 Alta Disponibilidade
Alta Disponibilidade se concentra em garantir a disponibilidade máxima (acordos de nível de serviço - SLA), independente de interrupções ou eventos que possam ocorrer.

## 📈 Escalabilidade
Escalabilidade refere-se à capacidade de ajustar recursos para atender à demanda. A capacidade de escalar significa que você poderá adicionar mais recursos para lidar melhor com o aumento da demanda.

## 🚀 Elasticidade
Elasticidade é o salto repentino acentuado na demanda, onde seus recursos implantados poderiam ser expandidos (automaticamente ou manualmente). Exemplo: **Black Friday**.

## ✅ Confiabilidade
Confiabilidade é garantir a alta disponibilidade, tolerância a falhas e escalabilidade para suportar cargas variáveis.

## 🔮 Previsibilidade
Previsibilidade permite que você avance com confiança, seja no desempenho ou no custo. Ambas são influenciadas pelo **Microsoft Azure Well Architected Framework**.

## 🛡️ Segurança em Nuvem
A segurança em nuvem fornecerá ferramentas que atendem às necessidades do cliente, mas a implementação de muitas delas deve ser feita pelo próprio cliente.

# 🛠️ Governança
São um conjunto de políticas, processos e controles que garantem o uso adequado e eficiente dos recursos na nuvem.

# ⚙️ Gerenciabilidade

- **Portal Web** 🌐
- **Linha de Comando** ⌨️
- **API** 💻
- **PowerShell** 🖥️

Exemplo: Escalar automaticamente a implantação de recursos com base na necessidade.

Implantar recursos com base em um modelo pré-configurado, removendo a necessidade de configuração manual.

---

🌐 **IaaS (Infraestrutura como Serviço):**

É um modelo de computação em nuvem que oferece recursos de infraestrutura como servidores, armazenamento e redes sob demanda. 🚀

Você configura e gerencia o hardware para seu aplicativo. 💻

**Ex:** Azure Virtual Machines

---

🛠️ **PaaS (Plataforma como Serviço):**

É um modelo de computação em nuvem que fornece uma plataforma pronta para o desenvolvimento. 📲

Focado no desenvolvimento de Aplicativos. 🔧

**Ex:** Azure App Services

---

☁️ **SaaS (Software como Serviço):**

É um modelo de distribuição de software onde os aplicativos são hospedados na nuvem e acessados pelos usuários via internet. 🌍

Os usuários pagam pelo software que utilizam em um modelo de assinatura. 💸

**Ex:** Office 365, Teams

---

# 🌍 REGIÕES

Nem todos os recursos estão disponíveis para todas as regiões.

- 📍 **As regiões** são compostas de um ou mais datacenters muito próximos.
- ⚡ **Elas fornecem flexibilidade e escala** para reduzir a latência do cliente.
- 🔒 **As regiões preservam a residência dos dados** com uma oferta abrangente de conformidade (LGPD).

**Região do Azure** = [Zona de Disponibilidade 1, Zona de Disponibilidade 2, Zona de Disponibilidade 3]

---

# 🛡️ ZONA DE DISPONIBILIDADE (CONJUNTO DE DISPONIBILIDADE)

- 🔗 **São agrupamentos lógicos de VMs**.
- 💥 **Fornecem proteção contra tempo de inatividade** devido à falha do datacenter.
- 🌐 **Separam fisicamente os datacenters** dentro da mesma região.
- 🔋 **Cada datacenter é equipado com alimentação, resfriamento e rede independentes**.

---

# 🇺🇸 REGIÕES SOBERANAS DO AZURE

- 🏛️ **Serviços Governamentais dos EUA**: Atende às necessidades de segurança e conformidade das agências federais, governos e seus provedores de soluções.
- 🇨🇳 **Azure China**: Primeiro provedor estrangeiro de nuvem pública da China e atende às necessidades governamentais. Mantida pela 21vianet.

---

# 💻 RECURSOS DO AZURE

- 📦 **Armazenamento**
- 🖥️ **Máquinas Virtuais (VMs)**
- 🌐 **Redes Virtuais**
- 🛠️ **Serviços de Aplicativos**
- 🗃️ **Banco de Dados**
- ⚙️ **Funções**
- … (Outros recursos)

---

# 🏷️ GRUPO DE RECURSOS

- ✏️ **Não é possível renomear um grupo de recursos**.
- 🗂️ **Um grupo de recursos é um contêiner** que você usa para gerenciar e agrupar recursos em uma única unidade.
- 🌍 **Os recursos podem existir em apenas um grupo de recursos**, mas podem estar em **regiões diferentes**.
- 🔄 **Os recursos podem ser movidos para diferentes grupos de recursos**.
- 🏗️ **Os aplicativos podem utilizar vários grupos de recursos**.

