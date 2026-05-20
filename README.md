# 🍃 EcoTech — Eficiência Energética na Tecnologia do Dia a Dia

O **EcoTech** é uma landing page interativa, moderna e responsiva focada em conscientização ecológica e educação financeira doméstica. O objetivo principal do projeto é ensinar os usuários a identificarem e combaterem o **"Consumo Invisível" (Vampire Load)** — a energia elétrica consumida por aparelhos eletrônicos cotidianos enquanto estão em modo de espera (*standby*) ou conectados ociosamente à tomada.

Este projeto foi desenvolvido como parte de uma atividade escolar integrada englobando conceitos de **Física (Eletricidade)**, **Sustentabilidade (Ecologia)** e **Programação Web (Tecnologia)**.

---

## 🎯 Finalidade do Projeto

Muitas pessoas não sabem que manter aparelhos como receptores de TV a cabo, videogames em modo de inicialização rápida e carregadores ociosos na tomada gera um desperdício constante de energia. Estudos apontam que o modo *standby* pode representar de **10% a 12% da conta de luz de uma residência**.

O **EcoTech** visa:
1. **Conscientizar:** Explicar de forma visual e intuitiva o que é o consumo invisível e quais são seus maiores vilões domésticos.
2. **Simular:** Fornecer uma calculadora dinâmica onde o usuário insere seus hábitos e vê instantaneamente o impacto financeiro (R$) e ecológico (CO₂ evitado).
3. **Educar:** Conectar a teoria física de eletrodinâmica estudada em sala de aula com a prática do cotidiano.

---

## 🛠️ Como o Projeto é Feito (Tecnologias)

Para garantir máxima portabilidade, facilidade de hospedagem e execução offline, o projeto foi construído **sem frameworks ou dependências externas**, utilizando exclusivamente tecnologias nativas da web:

- **HTML5 Semântico:** Estruturação organizada e acessível da página usando tags adequadas (`<header>`, `<main>`, `<section>`, `<article>`, `<footer()`).
- **CSS3 Personalizado (Vanilla CSS):**
  - Layout totalmente responsivo com **CSS Grid** e **Flexbox** (comportamento *mobile-first*).
  - Variáveis de CSS (Design Tokens) para fácil manutenção e consistência de cores (paleta baseada em branco/cinza claro com realces em verde ecológico e azul tecnológico).
  - Efeitos de profundidade suaves (sombras e filtros de desfoque/glassmorphism) e micro-interações animadas para melhorar a experiência do usuário (UX).
- **JavaScript Puro (ES6+):** Programação reativa que escuta as mudanças nos inputs e atualiza o DOM instantaneamente, realizando os cálculos matemáticos na máquina do próprio usuário.
- **Ícones em SVG Inline:** Todos os logotipos e ícones são arquivos vetoriais inseridos diretamente no código HTML, eliminando a dependência de fontes externas ou imagens de terceiros.

---

## 🧮 Lógica de Cálculo e Fórmulas Físicas

A simulação baseia-se nas equações de eletrodinâmica para cálculo de consumo energético:

1. **Consumo de Energia Mensal ($E$):**
   $$E \text{ (kWh)} = \frac{P \text{ (Watts)} \times t \text{ (Horas/Dia)} \times 30 \text{ dias}}{1000}$$
   *(Onde $P$ é a potência média de standby do aparelho selecionado e $t$ é o tempo diário de ociosidade).*

2. **Custo Mensal e Anual:**
   $$\text{Custo Mensal (R\$)} = E \text{ (kWh)} \times \text{Tarifa da Distribuidora (R\$/kWh)}$$
   $$\text{Custo Anual (R\$)} = \text{Custo Mensal} \times 12$$

3. **Métricas Ambientais:**
   - **Pegada de Carbono Evitada:** Multiplica o consumo anual de kWh por **$0,1\text{ kg CO}_2\text{/kWh}$** (fator médio brasileiro de emissão do SIN).
   - **Árvores Equivalentes:** Calcula quantas árvores da Mata Atlântica seriam necessárias para reabsorver o CO₂ desperdiçado (taxa média de **$15\text{ kg de CO}_2\text{/ano}$** absorvido por árvore jovem).
   - **Lâmpadas LED:** Converte a energia desperdiçada em dias inteiros de funcionamento de uma lâmpada LED altamente eficiente de **$9\text{ Watts}$**.

---

## 🚀 Como Usar o Projeto

### Rodar Localmente
Como o site é auto-contido em um único arquivo, você não precisa instalar servidores locais:
1. Faça o download ou clone este repositório.
2. Dê um duplo clique no arquivo **`index.html`** para executá-lo diretamente em qualquer navegador (Chrome, Firefox, Safari, Edge).

### Hospedagem na Web (Grátis)
Para disponibilizar o site na internet para qualquer pessoa acessar, você pode usar o **GitHub Pages**:
1. Faça o upload deste projeto em seu repositório pessoal do GitHub.
2. Acesse as **Settings** (Configurações) do repositório.
3. No menu lateral, selecione **Pages**.
4. Em *Build and deployment*, escolha o branch **`main`** e clique em **Save**.
5. Em instantes, o GitHub fornecerá o link público do seu site.

---

## 📝 Licença e Finalidade Acadêmica

Este projeto foi construído para fins estritamente didáticos e escolares, podendo ser livremente adaptado e distribuído para fins de educação pública, conscientização ambiental e física aplicada.
