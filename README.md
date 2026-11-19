# Apoio Urbano — Protótipo Interativo de Atendimento Social em Campo

Estudo de caso de **UI/UX Design, Arquitetura de Informação e Prototipação Interativa** desenvolvido no Figma, focado em apoiar assistentes sociais e voluntários durante abordagens e encaminhamentos de pessoas em situação de vulnerabilidade nas ruas.

---

## 1. O Problema e a Validação de Premissas
Durante a conceção do projeto, avaliou-se inicialmente a criação de uma interface dupla (uma aba para pessoas em situação de rua e outra para assistentes sociais). Contudo, através da **validação de premissas de usuário**, identificou-se que grande parte da população em situação de rua não possui acesso contínuo a smartphones ou internet móvel.

O escopo foi então redirecionado para quem opera a ferramenta diretamente na ponta: **o assistente social ou voluntário em campo**, que precisa consultar vagas disponíveis em tempo real, registar abordagens rapidamente e realizar encaminhamentos com uma mão, muitas vezes em movimento e sob luz solar intensa.

---

## 2. Engenharia de Requisitos (MVP)
* **RF01 — Autenticação Institucional:** Acesso rápido via e-mail institucional ou biometria para garantir a segurança dos dados sensíveis das pessoas atendidas.
* **RF02 — Mapa e Busca de Serviços:** Visualização georreferenciada de abrigos, restaurantes populares e pontos de apoio com filtros rápidos (`Abrigos`, `Vagas`, `Comida`) e indicadores visuais de lotação.
* **RF03 — Detalhes e Encaminhamento:** Consulta de endereço, regras de acolhimento (aceitação de pets e famílias), vagas livres e vínculo direto do encaminhamento à pessoa abordada.
* **RF04 — Ficha de Abordagem Rápida:** Registo simplificado em campo contendo local, necessidade principal, identificação/apelido e observações.
* **RF05 — Histórico de Atendimentos:** Rastreabilidade diária das abordagens e encaminhamentos efetuados pelo profissional.

---

## 3. Arquitetura de Informação e Telas
O fluxo foi desenhado em **wireframes de baixa fidelidade** para validar a hierarquia visual e a ergonomia mobile antes da aplicação estética:

1. **`01 - Login`:** Autenticação institucional e biometria.
2. **`02 - Mapa de Serviços`:** Tela principal com barra de busca, filtros horizontais, marcadores de disponibilidade e cartão de pré-visualização rápida.
3. **`03 - Nova Abordagem`:** Formulário objetivo de registo em campo com ação principal de busca imediata de vaga.
4. **`04 - Histórico`:** Resumo dos atendimentos realizados no turno e controle de sessão (`Sair`).
5. **`05 - Detalhes do Local`:** Subtela de consulta de disponibilidade e confirmação de encaminhamento.

### Wireframes do Fluxo
| Login | Mapa de Serviços | Nova Abordagem | Histórico | Detalhes do Local |
| :---: | :---: | :---: | :---: | :---: |
| ![Login](01%20-%20Login..png) | ![Mapa](02%20-%20Mapa%20de%20Servi%C3%A7os.png) | ![Abordagem](03%20-%20Nova%20Abordagem.png) | ![Historico](04%20-%20Hist%C3%B3rico.png) | ![Detalhes](05%20-%20Detalhes%20do%20Local.png) |

---

## 4. Protótipo Interativo
* **Ferramenta:** Figma (Wireframing, Grid Mobile e Prototipação Interativa)
* **Acesse e teste o protótipo navegável:** [Clique aqui para abrir no Figma](COLE_SEU_LINK_DO_FIGMA_AQUI)

---

## 5. Próximos Passos
* Evolução para **Alta Fidelidade** com *Design System* acessível (alto contraste e tipografia otimizada para uso externo).
* Implementação nativa mobile no **Android Studio**.
