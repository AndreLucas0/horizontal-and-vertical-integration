# Plano Orçamentário – Implantação de Rede Industrial  

---

## 1. Objetivo do Plano

Este plano orçamentário tem como objetivo apresentar o levantamento técnico dos equipamentos necessários para compor a **infraestrutura de comunicação e automação** em uma indústria de produção de tijolos ecológicos.

O documento contempla:

- Identificação dos dispositivos (CLP, switches industriais, cabeamento, IHMs, fontes, etc.);
- Pesquisa de fornecedores online no Brasil;
- Cotação de valores;
- Prazos de entrega estimados;
- Especificações técnicas;
- Análise de adequação ao ambiente industrial;
- Avaliação da escalabilidade da solução;
- Compatibilidade com futuras integrações com sistemas corporativos (MES/ERP);
- Estimativa de investimento.

---

## 2. Levantamento Técnico de Equipamentos

### 2.1 Controlador Lógico Programável (CLP)

| **Equipamento** | **Origem/Fornecedor** | **Preço Estimado (R$)** | **Especificações Técnicas** | **Prazo de Entrega** |
|------------------|-----------------------|---------------------------|-----------------------------|------------------------|
| CLP Siemens SIMATIC S7-1200 | FourServ (distribuidor) | ~R$ 2.300,00 | CPU com comunicação Ethernet integrada, 14 I/O embarcados | 10–20 dias úteis |
| CLP WEG CLIC02 | Orçamentos online | ~R$ 1.200–2.000 | CLP compacto até 16 I/O, programação Flow Chart | 10–30 dias úteis |
| CLP Allen-Bradley CompactLogix | ProInd Eletrônica | R$ 7.000–15.000 | Plataforma escalável, comunicação industrial | 10–30 dias úteis |

✔︎ *Justificativa:* CLPs robustos e industriais permitem automação confiável e integração com redes Ethernet industriais, fundamentais para conectividade com supervisórios e sistemas corporativos.

---

### 2.2 Switches Industriais

| **Equipamento** | **Fornecedor / Fonte** | **Preço Estimado (R$)** | **Especificações** | **Prazo Entrega** |
|------------------|------------------------|---------------------------|----------------------|--------------------|
| Switch Industrial 8 portas | HSMA Automação | R$ 1.500 – 3.000 | 8 portas RJ45, montagem DIN | 10–20 dias úteis |
| Switch Gerenciável Industrial 16 portas | HSMA Automação | R$ 7.000 – 15.000 | Suporte VLAN, QoS e rede segmentada | 15–30 dias úteis |

✔︎ *Especificação:* Deve suportar **temperaturas industriais**, montagem em trilho DIN e proteção contra interferências eletromagnéticas.

---

### 2.3 Cabeamento e Conectores

| **Item** | **Fornecedor / Fonte** | **Preço Estimado** | **Especificação Técnica** |
|------------|------------------------|----------------------|-----------------------------|
| Cabo Ethernet Industrial CAT6 blindado | Fornecedores automação | R$ 50–80 / metro | Blindado para ruído industrial |
| Conectores RJ45 metálicos | Fornecedores automação | R$ 10–30 / unidade | Compatível com cabo blindado |
| Patch Panel industrial | Fornecedores automação | R$ 300–800 | Organização de cabos |

✔︎ *Observação:* Cabeamento blindado minimiza ruído elétrico e falhas de comunicação no ambiente industrial.

---

### 2.4 Interface Homem-Máquina (IHM)

| **Item** | **Fornecedor / Fonte** | **Preço Estimado (R$)** | **Especificações** |
|------------|------------------------|--------------------------|--------------------|
| HMI Siemens KTP400 | FourServ | ~R$ 2.200 | Interface para supervisão local |
| HMI Schneider Magelis | FourServ | R$ 5.500–6.500 | Tela touch com CPU embarcada |

IHMs permitem monitoramento e controle de parâmetros diretamente no chão de fábrica.

---

### 2.5 Fontes, Proteções e Painéis

| **Item** | **Preço Estimado (R$)** | **Descrição** |
|------------|--------------------------|--------------|
| Fonte industrial 24 VDC | R$ 300 – 900 | Alimentação de controladores e sensores |
| Disjuntores e proteções | R$ 1.000 – 3.000 | Proteção elétrica do sistema |
| Painel elétrico industrial | R$ 5.000 – 12.000 | Acomoda CLPs, fontes e equipamentos |

---

### 2.6 Software Supervisório / SCADA

| **Software** | **Fornecedor / Observação** | **Preço Estimado (R$)** | **Função** |
|---------------|-----------------------------|--------------------------|-------------|
| Software SCADA (ex: Elipse E3) | Distribuidores autorizados | R$ 20.000 – 50.000 | Supervisão, alarmes, histórico |

✔︎ *Observação:* Licenças podem variar conforme número de pontos a serem monitorados.

---

## 3. Especificações Técnicas e Compatibilidade

### 3.1 Ambiente Industrial

Os equipamentos selecionados devem possuir características para:

- Operação em **temperaturas elevadas e poeira**;
- **Resistência a interferências eletromagnéticas**;
- **Montagem em trilho DIN**;
- **Proteção física adequada** (IP20 ou superior).

Dispositivos industriais garantem durabilidade e robustez.

---

### 3.2 Escalabilidade da Solução

A solução foi concebida para permitir:

- Adição de módulos I/O extra nos CLPs;
- Segmentação de rede com switches gerenciáveis;
- Integração futura com sensores IIoT;
- Conexão com sistemas corporativos MES/ERP;
- Coleta de dados via Ethernet industrial.

A arquitetura garante suporte a expansão da planta sem necessidade de reestruturação.

---

### 3.3 Compatibilidade com Sistemas Corporativos

Com comunicação **Ethernet Industrial (Modbus TCP, Profinet, etc.)**, a infraestrutura facilita:

- Integração com MES (Manufacturing Execution System);
- Conexão com sistema ERP;
- Extração de dados históricos para BI (Business Intelligence).

Suporte a padrões industriais é essencial para integração corporativa.

---

## 4. Cotações de Valores e Prazos de Entrega

| **Categoria** | **Intervalo de Preço (R$)** | **Prazo Entrega Estimado** |
|---------------|------------------------------|-----------------------------|
| CLPs | 1.200 – 15.000 | 10–30 dias úteis |
| Switches Industriais | 1.500 – 15.000 | 10–30 dias úteis |
| Cabeamento e conectores | 3.000 – 10.000 | 7–20 dias úteis |
| IHMs | 2.200 – 6.500 | 10–30 dias úteis |
| Fontes & proteção | 6.000 – 16.000 | 7–20 dias úteis |
| Software SCADA | 20.000 – 50.000 | 15–40 dias úteis |

*(Todos os valores são estimativas com base em cotações médias de distribuidores brasileiros de automação industrial.)*

---

## 5. Análise da Adequação dos Equipamentos

### 5.1 Adequação ao Ambiente Industrial

- CLPs industriais e switches com grau de proteção garantem operação contínua;
- Cabeamento blindado reduz falhas de comunicação em ambientes com ruído elétrico;
- Painéis elétricos organizados protegem equipamentos contra intempéries internas.

---

### 5.2 Escalabilidade da Solução

- CLPs modulares permitem ampliar pontos de I/O;
- Switches gerenciáveis suportam novas VLANs e segmentação;
- Supervisório escalável com licenças para pontos adicionais.

A solução cresce com a planta sem alterações estruturais significativas.

---

### 5.3 Compatibilidade com Integrações Futuras

Equipamentos com comunicação Ethernet industrial suportam:

- Integração com MES;
- Conexão ao ERP da empresa;
- Exportação de dados para análises avançadas (Big Data / BI).

---

## 6. Estimativa Total de Investimento

| **Categoria** | **Valor Estimado (R$)** |
|----------------|--------------------------|
| CLPs | 1.200 – 15.000 |
| Switches Industriais | 1.500 – 15.000 |
| Cabeamento & Conectores | 3.000 – 10.000 |
| IHMs | 2.200 – 6.500 |
| Fontes e Painéis | 6.000 – 16.000 |
| Software SCADA | 20.000 – 50.000 |
| **Total Estimado** | **R$ 33.900 – R$ 112.500** |

*(Intervalo considera opções de equipamentos mais econômicos até opções mais robustas e escaláveis.)*

---

## 7. Conclusão

O plano orçamentário apresentado oferece um panorama técnico e financeiro para a implantação de uma rede industrial em uma indústria de produção de tijolos ecológicos.

A solução proposta é:

- **Adequada ao ambiente industrial**;
- **Escalável para necessidades futuras**;
- **Compatível com integrações corporativas (MES/ERP)**;
- **Financeiramente viável**, com base em cotações de mercado.

A infraestrutura tecnológica proporcionará maior controle da produção, monitoramento em tempo real, redução de falhas e suporte à estratégia digital de manufatura da empresa.
