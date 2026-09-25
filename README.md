# Akrai - Gestão e Precificação de Ateliê

Aplicativo móvel desenvolvido com arquitetura híbrida (Capacitor + Web Components) para ateliês artesanais. Permite o cálculo dinâmico de precificação por composição de insumos, rateio de horas de produção, controle de estoque persistente e geração de demonstrativos contábeis em PDF.

## 🚀 Funcionalidades

- **Precificação Parametrizada:** Cálculo proporcional por peso de rolo/gramatura e rateio de custo/hora da artesã com margem configurável.
- **Inventário:** Rastreamento de consumo de matéria-prima (fios, cordas e aviamentos) com baixa automática na finalização de peças.
- **Catálogo Integrado:** Registro fotográfico via câmera do dispositivo ou galeria com despacho formatado para WhatsApp via API nativa de compartilhamento.
- **Gestão Financeira:** Demonstrativo de entradas/saídas por competência temporal e geração de relatório contábil em `.pdf`.
- **Sincronização em Nuvem:** Replicação relacional via PostgreSQL (Supabase) com redundância local offline (IndexedDB).

## 🛠️ Tecnologias

- **Frontend:** Vanilla JavaScript (ES6+), HTML5, CSS3 Custom Properties
- **Banco de Dados & Sync:** Supabase (PostgreSQL / PostgREST), IndexedDB
- **Ambiente Nativo:** Capacitor Engine (Android runtime)
- **Bibliotecas:** jsPDF (renderização vetorial de extratos)

## 📦 Configuração

1. Clone o repositório:
```bash
git clone [https://github.com/SEU-USUARIO/akrai-app.git](https://github.com/SEU-USUARIO/akrai-app.git)