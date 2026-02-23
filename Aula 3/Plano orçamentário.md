# Plano Orçamentário  

---

# 1. Introdução

Este documento apresenta um **plano orçamentário técnico** para implantação de uma **rede industrial** em uma indústria de produção de tijolos ecológicos.

A proposta contempla:

- Levantamento técnico dos equipamentos de automação;
- Infraestrutura de comunicação industrial;
- Sistemas de supervisão e controle;
- Infraestrutura elétrica e de rede;
- Estimativa orçamentária preliminar.

O objetivo é estruturar uma base tecnológica que permita **monitoramento em tempo real, controle automatizado do processo produtivo, rastreabilidade e aumento da eficiência operacional**.

---

# 2. Caracterização do Processo Produtivo

A produção de tijolos ecológicos normalmente envolve:

1. Recebimento e dosagem de matéria-prima (solo, cimento e água);
2. Mistura mecânica;
3. Prensagem hidráulica;
4. Cura e armazenamento;
5. Controle de qualidade.

Cada etapa exige monitoramento de variáveis como:

- Peso e dosagem;
- Umidade;
- Pressão hidráulica;
- Tempo de prensagem;
- Produção por turno.

---

# 3. Arquitetura Proposta da Rede Industrial

## 3.1 Nível de Campo (Chão de Fábrica)

Dispositivos responsáveis pela coleta de dados e atuação no processo.

### Equipamentos Necessários

| Equipamento | Quantidade Estimada | Valor Unitário (R$) | Valor Total (R$) |
|-------------|--------------------|---------------------|------------------|
| Sensores de umidade industrial | 4 | 1.200 | 4.800 |
| Sensores de pressão hidráulica | 4 | 1.500 | 6.000 |
| Células de carga (balança industrial) | 2 | 3.500 | 7.000 |
| Sensores indutivos/fim de curso | 10 | 250 | 2.500 |
| Atuadores/solenóides | 6 | 400 | 2.400 |

**Subtotal Nível de Campo: R$ 22.700**

---

## 3.2 Nível de Controle (CLPs e Painéis)

Responsável pelo processamento lógico e controle das máquinas.

| Equipamento | Quantidade | Valor Unitário (R$) | Valor Total (R$) |
|-------------|------------|---------------------|------------------|
| CLP modular industrial | 2 | 8.000 | 16.000 |
| Módulos de entradas/saídas (I/O) | 4 | 2.000 | 8.000 |
| IHMs (Interfaces Homem-Máquina) | 2 | 4.000 | 8.000 |
| Painel elétrico industrial completo | 2 | 6.000 | 12.000 |

**Subtotal Nível de Controle: R$ 44.000**

---

## 3.3 Rede de Comunicação Industrial

Proposta de rede baseada em Ethernet Industrial (ex: Profinet ou Ethernet/IP).

| Equipamento | Quantidade | Valor Unitário (R$) | Valor Total (R$) |
|-------------|------------|---------------------|------------------|
| Switch industrial gerenciável | 3 | 3.000 | 9.000 |
| Roteador industrial | 1 | 4.000 | 4.000 |
| Cabos industriais blindados (média 500m) | 1 lote | 5.000 | 5.000 |
| Conectores industriais | 20 | 50 | 1.000 |
| Rack de rede | 1 | 2.500 | 2.500 |

**Subtotal Comunicação: R$ 21.500**

---

## 3.4 Sistema Supervisório (SCADA)

Permite monitoramento, histórico de dados e geração de relatórios.

| Item | Quantidade | Valor Unitário (R$) | Valor Total (R$) |
|------|------------|---------------------|------------------|
| Licença SCADA | 1 | 15.000 | 15.000 |
| Servidor industrial | 1 | 12.000 | 12.000 |
| Estação de operação | 1 | 6.000 | 6.000 |
| Nobreak industrial | 2 | 3.000 | 6.000 |

**Subtotal Supervisão: R$ 39.000**

---

## 3.5 Infraestrutura Elétrica e Segurança

| Item | Valor Estimado (R$) |
|------|--------------------|
| Cabeamento elétrico | 8.000 |
| Disjuntores e proteção elétrica | 5.000 |
| Sistema de aterramento | 4.000 |
| Sistema de proteção contra surtos | 3.000 |

**Subtotal Infraestrutura Elétrica: R$ 20.000**

---

## 3.6 Serviços Técnicos

| Serviço | Valor Estimado (R$) |
|----------|--------------------|
| Projeto elétrico e de automação | 15.000 |
| Programação CLP e SCADA | 20.000 |
| Instalação e montagem | 18.000 |
| Testes e comissionamento | 10.000 |
| Treinamento operacional | 7.000 |

**Subtotal Serviços: R$ 70.000**

---

# 4. Investimento Total Estimado

| Categoria | Valor (R$) |
|------------|------------|
| Nível de Campo | 22.700 |
| Controle | 44.000 |
| Comunicação | 21.500 |
| Supervisão | 39.000 |
| Infraestrutura Elétrica | 20.000 |
| Serviços Técnicos | 70.000 |

## 💰 Investimento Total Estimado: **R$ 217.200**

*(Valores aproximados para fins acadêmicos/simulados.)*

---

# 5. Benefícios Esperados

- Monitoramento em tempo real da produção;
- Redução de desperdício de matéria-prima;
- Controle preciso da prensagem;
- Aumento da produtividade;
- Rastreabilidade de lotes;
- Base para futura integração com ERP ou sistema MES.

---

# 6. Retorno sobre Investimento (ROI)

Com aumento estimado de:

- 15% na produtividade;
- 10% de redução de desperdícios;
- 20% de redução de paradas não planejadas;

O investimento pode ser amortizado em aproximadamente **18 a 24 meses**, dependendo do volume produtivo da indústria.
