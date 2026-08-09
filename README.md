# Sistema de Atendimento em Saúde

Sistema web desenvolvido para organizar e centralizar o fluxo de atendimento de uma unidade de saúde, conectando recepção, triagem, consultórios, raio-X, sala de espera e relatórios em uma única experiência operacional.

> Projeto desenvolvido com foco em fluxo assistencial, organização de filas e atualização em tempo real.

---

## Visão geral

O sistema foi pensado para reduzir controles paralelos e melhorar a visibilidade do atendimento, permitindo que diferentes etapas da operação trabalhem de forma integrada.

Entre os principais objetivos estão:

- centralizar o fluxo de atendimento;
- organizar filas e prioridades;
- melhorar a comunicação entre recepção, triagem e consultórios;
- exibir chamadas de pacientes em tempo real;
- acompanhar movimentações por unidade;
- consolidar indicadores e relatórios operacionais.

---

## Principais funcionalidades

### Recepção e triagem
- registro e encaminhamento de pacientes;
- organização da fila de atendimento;
- separação por unidade;
- apoio ao fluxo entre recepção e triagem.

### Consultórios e setores
- acompanhamento de pacientes por consultório;
- direcionamento para raio-X e demais etapas;
- atualização do status do atendimento;
- controle do fluxo entre setores.

### Chamadas em tempo real
- atualização instantânea das filas;
- exibição das chamadas em TV/painel;
- suporte a voz para chamada de pacientes;
- sincronização dos dados via realtime.

### Relatórios
- visão consolidada do atendimento;
- acompanhamento por unidade;
- indicadores operacionais;
- apoio à análise do fluxo e da demanda.

---

## Stack

<div align="left">

![HTML](https://img.shields.io/badge/HTML-111111?style=for-the-badge&logo=html5&logoColor=E34F26)
![JavaScript](https://img.shields.io/badge/JavaScript-111111?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![Supabase](https://img.shields.io/badge/Supabase-111111?style=for-the-badge&logo=supabase&logoColor=3ECF8E)
![Vercel](https://img.shields.io/badge/Vercel-111111?style=for-the-badge&logo=vercel&logoColor=white)

![Realtime](https://img.shields.io/badge/Realtime-2F80FF?style=for-the-badge)
![Web Speech API](https://img.shields.io/badge/Web%20Speech%20API-2F80FF?style=for-the-badge)
![Patient Flow](https://img.shields.io/badge/Patient%20Flow-2F80FF?style=for-the-badge)

</div>

---

## Arquitetura do fluxo

```txt
Recepção
   ↓
Triagem
   ↓
Fila de atendimento
   ↓
Consultório / Setor
   ↓
Raio-X ou continuidade
   ↓
Finalização / Relatório
```

---

## Realtime

O projeto utiliza recursos de atualização em tempo real para manter filas, chamadas e status sincronizados entre as diferentes telas do sistema.

Isso permite que alterações feitas em uma etapa do atendimento sejam refletidas rapidamente nas demais interfaces da operação.

---

## Deploy

O projeto possui deploy configurado na Vercel.

A URL pública disponível no repositório pode ser usada para homologação e demonstração do fluxo.

---

## Objetivo

Transformar um processo operacional com múltiplas etapas em um fluxo digital mais organizado, rastreável e fácil de acompanhar.

A proposta é concentrar informações importantes em um único ambiente e reduzir dependência de controles paralelos.

---

## Desenvolvedor

**Nathan Mendes**  
Founder @ **NM LABS**

Sistemas • Automações • Integrações • Produtos digitais

GitHub: [nathanlmendes17](https://github.com/nathanlmendes17)

---

> **BUILD • AUTOMATE • SCALE**
