# EnergyCalc - Módulo 02

## 📋 Sobre o Projeto
Aplicação web desenvolvida para o Módulo 02, implementando a solução proposta no Módulo 01: dificuldade em gerenciar o consumo de energia elétrica residencial.

O EnergyCalc permite que o usuário calcule o valor estimado da conta de luz inserindo o consumo em kWh e a tarifa local, recebendo feedback imediato sobre seu nível de consumo.

## 🚀 Tecnologias Utilizadas

| Tecnologia | Justificativa |
| --- | --- |
| **Alpine.js** | Framework reativo moderno que atende ao requisito do módulo. Permite reatividade e gerenciamento de estado de forma declarativa diretamente no HTML, sem necessidade de build ou dependências complexas. |
| **HTML5** | Estruturação semântica com `<header>`, `<main>`, `<section>`, `<footer>`. Uso de `label` associado a `input` e `aria-live` para garantir acessibilidade. |
| **CSS3** | Estilização responsiva com abordagem Mobile-First. Media query em 600px adapta o layout para desktop, garantindo usabilidade em todos dispositivos. |

## ⚡ Funcionalidades

1. **Cálculo Dinâmico**: Calcula o valor da conta sem recarregar a página usando reatividade do Alpine.js
2. **Feedback de Consumo**: Classifica o consumo como Econômico, Normal ou Alto com cores diferentes
3. **Interface Responsiva**: Funciona em celular, tablet e desktop
4. **Acessível**: Navegável por teclado e compatível com leitores de tela

## 📱 Como Usar
1. Abra o arquivo `index.html` no navegador
2. Digite o consumo do mês em kWh
3. Ajuste a tarifa da sua cidade se necessário
4. Clique em "Calcular Valor"
5. Veja o resultado e as dicas para economizar

## 🎯 Requisitos Atendidos do Módulo 02
- [x] Uso de framework moderno: Alpine.js
- [x] HTML semântico e acessível
- [x] CSS responsivo com media queries
- [x] Funcionalidade dinâmica com JavaScript
- [x] Tema alinhado com a proposta do Módulo 01