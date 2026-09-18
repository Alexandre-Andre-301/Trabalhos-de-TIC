# 🎯 Quiz Interactivo — Sistemas de Autor

![PowerPoint](https://img.shields.io/badge/Desenvolvido%20com-Microsoft%20PowerPoint-D97706?style=for-the-badge&logo=microsoftpowerpoint&logoColor=white)
![Área](https://img.shields.io/badge/Área-Tecnologias%20de%20Informação%20e%20Comunicação-0EA5E9?style=for-the-badge)
![Turma](https://img.shields.io/badge/Turma-IG12A-2563EB?style=for-the-badge)
![Estado](https://img.shields.io/badge/Estado-Em%20desenvolvimento-F59E0B?style=for-the-badge)

## 📌 Sobre o projeto

O **Quiz Interactivo — Sistemas de Autor** é um projeto multimédia desenvolvido em **Microsoft PowerPoint**, no âmbito da disciplina de **Tecnologias de Informação e Comunicação (TIC)**.

O objetivo é criar uma experiência de aprendizagem interativa, na qual o utilizador responde a perguntas de escolha múltipla, recebe feedback visual e sonoro e percorre diferentes níveis de dificuldade.

Mais do que criar um simples questionário, o projeto pretende demonstrar como os conceitos de uma aplicação interativa podem ser representados através de:

- **Palco:** o diapositivo do PowerPoint;
- **Objetos:** formas, textos, imagens e botões;
- **Propriedades:** cores, tamanhos, posições, contornos e efeitos;
- **Eventos:** cliques realizados pelo utilizador;
- **Ações:** hiperligações, sons, animações e transições.

> Este projeto foi estruturado de acordo com as orientações do Projeto 1 da disciplina de TIC.

---

## 🎮 Funcionalidades

O quiz foi planeado com uma interface moderna, inspirada em ambientes tecnológicos e futuristas.

### 🏠 Ecrã inicial

- Apresentação do nome e identidade visual do quiz;
- Botão **Começar**;
- Acesso às instruções;
- Acesso às configurações;
- Identificação da turma e do grupo.

### 🧭 Menu de níveis

O utilizador pode escolher entre três níveis de dificuldade:

| Nível | Cor temática | Objetivo |
|---|---|---|
| 🟢 Fácil | Verde | Reconhecer conceitos básicos |
| 🟡 Médio | Amarelo | Distinguir e aplicar conhecimentos |
| 🔴 Difícil | Vermelho | Analisar situações e justificar respostas |

Cada nível contém **4 perguntas**, totalizando **12 perguntas**.

### 📝 Ecrã de perguntas

Cada pergunta pode incluir:

- Quatro opções de resposta;
- Imagens relacionadas com o conteúdo;
- Indicador de progresso;
- Identificação do nível atual;
- Botões de navegação;
- Som e elementos visuais interativos.

### ✅ Feedback de resposta correta

Quando o utilizador seleciona a opção correta, é apresentado:

- Uma mensagem de parabéns;
- Uma indicação visual em verde;
- Uma explicação da resposta;
- Um som curto de acerto;
- Um botão para avançar para a próxima pergunta.

### ❌ Feedback de resposta incorreta

Quando o utilizador seleciona uma opção incorreta, é apresentado:

- Uma mensagem de erro;
- Uma indicação visual em vermelho;
- A identificação da resposta correta;
- Uma explicação do conteúdo;
- Um som curto de erro;
- Uma opção para tentar novamente ou regressar à pergunta.

### 🏆 Ecrã final

No final do percurso, o utilizador poderá:

- Visualizar a conclusão do quiz;
- Consultar a pontuação, caso a atividade extra com VBA seja implementada;
- Recomeçar o quiz;
- Voltar ao menu principal;
- Consultar uma mensagem final de agradecimento.

---

## 🎨 Identidade visual

A identidade visual utiliza uma combinação de cores escuras e luminosas, com inspiração em tecnologia, informática e interfaces digitais.

### Paleta principal

- **Azul escuro:** fundo e ambiente geral;
- **Azul elétrico/ciano:** contornos, botões e elementos de destaque;
- **Verde:** respostas corretas e nível fácil;
- **Amarelo:** nível médio e elementos de atenção;
- **Vermelho:** respostas incorretas e nível difícil;
- **Branco/cinza claro:** textos e informações.

O projeto procura manter a consistência entre os diapositivos através de:

- Tipografia uniforme;
- Botões com o mesmo estilo;
- Cores consistentes;
- Ícones e elementos gráficos relacionados;
- Navegação simples e intuitiva.

---

## 🗂️ Estrutura do projeto

O projeto está organizado de acordo com a estrutura definida para o trabalho:

| Secção | Quantidade |
|---|---:|
| Capa | 1 |
| Instruções | 1 |
| Menu de níveis | 1 |
| Nível fácil | 12 |
| Nível médio | 12 |
| Nível difícil | 12 |
| Ecrã final | 1 |
| Fontes | 1 |
| **Total** | **41 diapositivos** |

Cada pergunta dos níveis de dificuldade possui:

1. Diapositivo da pergunta;
2. Diapositivo de resposta correta;
3. Diapositivo de resposta incorreta.

---

## 🔗 Navegação e interatividade

A navegação é construída através de funcionalidades do PowerPoint, como:

- Hiperligações internas;
- Ação ao clicar numa forma;
- Botões de navegação;
- Sons de acerto e erro;
- Animações e transições;
- Acionadores para revelar conteúdos.

A navegação deve ser testada no **modo de apresentação**, garantindo que:

- O clique no fundo não avança o diapositivo;
- Todas as opções possuem uma ligação funcional;
- Não existem diapositivos sem saída;
- Os botões de retorno funcionam corretamente;
- Os três níveis podem ser concluídos.

---

## 🔊 Elementos multimédia

O quiz inclui ou prevê a utilização dos seguintes elementos:

- Imagens integradas nas perguntas;
- Som de resposta correta;
- Som de resposta incorreta;
- Animações com função específica;
- Transições discretas;
- Ícones e elementos gráficos.

A utilização de efeitos deve ser controlada para manter uma experiência clara e agradável. O projeto segue a orientação de utilizar, no máximo, dois sons diferentes e uma animação por diapositivo.

---

## 🧮 Atividade extra: pontuação com VBA

Como funcionalidade opcional, o projeto pode incluir **VBA (Visual Basic for Applications)** para contabilizar a pontuação do utilizador.

Esta funcionalidade poderá permitir:

- Registar respostas corretas;
- Registar respostas incorretas;
- Contabilizar o número de perguntas respondidas;
- Apresentar a pontuação final;
- Mostrar uma mensagem de desempenho.

Quando o VBA for utilizado, o ficheiro deverá ser guardado no formato:

```text
.pptm
```

> A versão base do quiz pode funcionar com hiperligações, sem utilizar código VBA.

---

## 🛠️ Tecnologias e ferramentas

- **Microsoft PowerPoint** — criação dos diapositivos e da interação;
- **Hiperligações internas** — navegação entre diapositivos;
- **Animações e transições** — feedback e apresentação visual;
- **Áudio e imagens** — componentes multimédia;
- **VBA (opcional)** — controlo da pontuação.

---

## 👥 Organização do trabalho

O trabalho está dividido em quatro responsabilidades:

| Elemento | Responsabilidade |
|---|---|
| Elemento A | Desenvolvimento do nível fácil |
| Elemento B | Desenvolvimento do nível médio |
| Elemento C | Desenvolvimento do nível difícil |
| Elemento D | Identidade visual, capa, instruções, menu, ecrã final, fontes e integração |

A integração final deve preservar a formatação original dos blocos e garantir que todas as ligações são revistas depois da junção dos ficheiros.

---

## 📚 Conteúdos abordados

As perguntas do quiz devem basear-se nos conteúdos dos:

- **Capítulo 1 — Introdução às TIC**
- **Capítulo 2 — Sistemas de Autor**

Cada nível deve incluir perguntas dos dois capítulos, respeitando a progressão de dificuldade:

- **Fácil:** reconhecimento de conceitos;
- **Médio:** distinção e aplicação;
- **Difícil:** análise de situações e justificação.

Todas as perguntas devem ser verificadas através de fontes credíveis.

---

## ✅ Lista de verificação

Antes da entrega, deve ser confirmado que:

- [ ] Todas as ligações funcionam;
- [ ] O clique no fundo não avança os diapositivos;
- [ ] Existem quatro opções em cada pergunta;
- [ ] As opções são plausíveis;
- [ ] Existem pelo menos duas perguntas com imagens;
- [ ] Os slides de feedback apresentam explicações;
- [ ] Os sons de acerto e erro funcionam;
- [ ] Os níveis possuem cores distintas;
- [ ] O projeto apresenta uma identidade visual consistente;
- [ ] Os três níveis podem ser concluídos;
- [ ] O botão de voltar ao menu funciona;
- [ ] O slide de fontes está preenchido;
- [ ] As marcas de numeração provisórias foram removidas;
- [ ] O ficheiro final foi testado em modo de apresentação.

---

## 📁 Formato de entrega

A versão base deve ser guardada em:

```text
.pptx
```

Caso seja implementada a atividade extra com VBA, o formato será:

```text
.pptm
```

Nome sugerido do ficheiro:

```text
Quiz_Grupo0X_IG12A.pptx
```

---

## 🎓 Contexto académico

**Instituição:** Instituto Politécnico Industrial de Luanda  
**Área:** Informática  
**Curso:** Técnico de Gestão de Sistemas Informáticos  
**Classe:** 12.ª Classe  
**Turma:** IG12A  
**Disciplina:** Tecnologias de Informação e Comunicação  
**Projeto:** Projeto 1 — Quiz Interativo em PowerPoint  

---

## 👨‍💻 Equipa

| Nome | Responsabilidade |
|---|---|
| Afonso Romé | Nível fácil |
| Elieser Hernani | Nível médio |
| Alexandre André | Nível difícil |
| Dário Yopilu | Estrutura e integração |

---

## 📌 Estado do projeto

🚧 **Em desenvolvimento**

O projeto encontra-se em fase de planeamento, criação da identidade visual, construção dos ecrãs e implementação da navegação interativa.

---

## 📄 Licença

Este projeto foi desenvolvido para fins **académicos e educativos**, no âmbito da disciplina de Tecnologias de Informação e Comunicação.
