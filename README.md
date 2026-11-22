# Portal de Estágios IFC — Campus Araquari

Trabalho em Dupla desenvolvido na disciplina de **Desenvolvimento Web I (RCC0218)**  
**Curso:** Tecnologia em Redes de Computadores — Instituto Federal Catarinense (IFC)  
**Equipe:** Jairuzalôn Maguidiel Vieira & Colega de Dupla  

---

## 1. Descrição do Projeto

O **Portal de Estágios IFC** é uma aplicação web estática institucional criada para aproximar empresas da região norte de Santa Catarina e os estudantes dos cursos técnicos e superiores do IFC Campus Araquari.

O site centraliza o quadro de vagas abertas, permite que concedentes cadastrem novas oportunidades com travas da Lei nº 11.788/2008 e fornece orientações claras sobre Termos de Compromisso (TCE) e relatórios de estágio.

---

## 2. Estrutura do Site (5 Páginas Interligadas)

A navegação foi estruturada em 5 páginas completas:

1. **Início (`index.html`):** Apresentação institucional do portal, links rápidos e destaques de vagas recentes por área (Redes, Web e Agropecuária).
2. **Vagas Abertas (`vagas.html`):** Quadro com cards estilizados em Flexbox contendo detalhes de bolsa, carga horária, empresa e requisitos.
3. **Cadastrar Vaga (`empresas.html`):** Formulário completo voltado para empresas parceiras com validações nativas do HTML5 (CNPJ, e-mail corporativo, horas semanais e atividades).
4. **Orientações Legais (`sobre.html`):** Guia explicativo sobre direitos do estagiário, limites de carga horária e passo a passo de homologação no SIGAA.
5. **Atendimento & Dúvidas (`contato.html`):** Formulário direto para contato com a Coordenação de Estágios e informações de horário de atendimento presencial no campus.

---

## 3. Padrões Técnicos Aplicados (Versão 1)

- **HTML5 Semântico:** Uso rigoroso de `header`, `nav`, `main`, `section`, `article`, `aside` e `footer`.
- **CSS3 com Flexbox:** Alinhamento de menus, grades responsivas de cards (`flex-wrap: wrap`) e distribuição de colunas utilizando espaçamento por `gap`.
- **Identidade Visual IFC:** Aplicação das cores institucionais do Instituto Federal (verde `#15803d` e vermelho `#dc2626`).
- **Responsividade:** Layout adaptável para telas desktop, tablets e celulares sem quebras de layout.

---

## 4. Funcionalidades Planejadas para a Versão 2 (JavaScript)

Para a próxima etapa do trabalho (interatividade com JavaScript), foram planejadas as seguintes 3 funcionalidades:

| Funcionalidade | Página | Elementos Envolvidos | Ação do Usuário | Comportamento Esperado |
| :--- | :--- | :--- | :--- | :--- |
| **Filtro Dinâmico de Vagas** | `vagas.html` | Campo `<select>` de cursos e cards | Selecionar uma área (ex: Redes de Computadores) | Filtrar e exibir apenas as vagas da área selecionada sem recarregar a página. |
| **Validador de Regras da Lei no Formulário** | `empresas.html` | Campos de bolsa, modalidade e botão | Alterar modalidade para "Não-obrigatório" | Bloquear o envio e alertar em tempo real se o valor da bolsa for preenchido com R$ 0,00 (garantindo a Lei 11.788). |
| **Simulador de Horas e Dias de Estágio** | `sobre.html` | Inputs de horas diárias e calculadora | Digitar a carga horária pretendida | Calcular automaticamente o total semanal e alertar caso ultrapasse o limite legal de 30 horas. |

---

## 5. Como Executar Localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/Academico-JZ/Portal-de-Est-gios-IFC.git
   ```
2. Abra a pasta no VS Code.
3. Abra qualquer arquivo `.html` no navegador ou com a extensão **Live Server**.
