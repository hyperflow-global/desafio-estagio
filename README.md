# Desafio de Estágio: Plataforma Inteligente de Estudos para o ENEM

## Contexto

Como nos ensina o mestre Paulo Freire em sua *Pedagogia da Autonomia*, a verdadeira educação não é apenas a transferência de conhecimento, mas a criação das possibilidades para a sua própria produção. Por isso, mais do que testar se você já sabe de cor um framework específico, o grande objetivo deste desafio é um só: **queremos ver você provar que sabe aprender a aprender**.

## 🎯 O Desafio

O Exame Nacional do Ensino Médio (ENEM) é a principal porta de entrada para o ensino superior no Brasil, e provavelmente você  fez ele. Preparar-se para ele exige organização, prática e bons materiais. Nossa missão neste desafio é avaliar como você usa a tecnologia e a sua autonomia investigativa para facilitar a vida do estudante.

Sua tarefa é desenvolver uma **aplicação web** voltada para estudantes que estão se preparando para o ENEM.

O grande diferencial deste projeto será a integração com uma **Inteligência Artificial Generativa**. Nós sugerimos o uso da IA do **Google (Gemini)**, principalmente porque ela oferece uma cota de uso gratuita para desenvolvedores, o que é perfeito para você criar e testar seu projeto sem custos. Nós não vamos te dizer *como* usar a IA: **a criatividade é sua!**

Pense em como uma IA pode realmente ajudar um estudante. Algumas ideias (você não precisa fazer essas, surpreenda-nos):

* Correção ou feedback automático de redações;

* Geração de simulados personalizados;

* Um "tutor" virtual para tirar dúvidas de matemática;

* Resumos automáticos de matérias de humanas.

## 🛠️ Stack Tecnológico

Para construirmos no mesmo ecossistema do nosso time, você deve focar nas seguintes tecnologias:

* **Backend:** Node.js (framework livre: Express, Fastify, NestJS, etc.)

* **Frontend:** React (framework livre: Vite, Next.js, Create React App, etc.)

* **Inteligência Artificial:** Sugerimos a [Google Gemini API](https://aistudio.google.com/) por possuir uma tier gratuita. Você pode gerar sua API Key no Google AI Studio. (Se preferir e tiver créditos, pode usar OpenAI, Claude, etc).

* **Controle de Versão:** Git e GitHub.

💡 **Dica de Ouro:** Recomendamos o uso da IDE [antigravidade](https://antigravity.google/) do Google. Pelo mesmo motivo da IA do Google, ela tem uma ótima cota gratuita de uso para codar. Mas você é totalmente livre: pode usar o **Cursor**, fazer tudo "na mão" com o bom e velho **VS Code**, ou utilizar qualquer outra IDE da sua preferência!

## ✅ Requisitos Funcionais

1. **Autenticação e Sessão:** Eu, como usuário, preciso conseguir criar uma conta, fazer login e deslogar da plataforma. Ao logar novamente, meus dados e histórico devem estar salvos.

2. **Área do Estudante (Dashboard):** Uma interface central (dashboard) onde o usuário logado possa ter uma visão geral e interagir com a plataforma de estudos.

3. **Simulados e Resultados:** O usuário deve conseguir realizar simulados dentro da plataforma. Além disso, preciso conseguir ver os resultados e o histórico de desempenho dos simulados que já realizei.

4. **A Feature de IA:** Onde a mágica acontece. A aplicação deve consumir a API de IA escolhida de maneira aberta e criativa, desde que seja útil para o contexto de estudos do ENEM.

**Dica sobre Banco de Dados:** Para salvar os dados dos usuários e dos simulados, recomendamos fortemente o uso do **MongoDB** (possui cota gratuita via Atlas e é um dos principais bancos que utilizamos hoje) ou **PostgreSQL** (que você pode utilizar de forma gratuita e fácil com o **Supabase**, e também utilizamos muito no nosso dia a dia).

## 💻 Requisitos Não-Funcionais e Entregáveis

* **Deploy (Obrigatório):** A sua aplicação precisa estar acessível online.

  💡 **Sugestões de Deploy Gratuito:**

  * **Para o Frontend (React):**

    * [Vercel](https://vercel.com/) (Excelente integração com GitHub, muito rápido para React/Next.js)

    * [Netlify](https://www.netlify.com/) (Muito popular e fácil de configurar)

    * [Firebase Hosting](https://firebase.google.com/docs/hosting)

    * [Cloudflare Pages](https://pages.cloudflare.com/)

  * **Para o Backend (Node.js):**

    * [Render](https://render.com/) (Ótimo plano gratuito para web services)

    * [Railway](https://railway.app/) (Fácil de usar e configurar via GitHub)

    * [Koyeb](https://www.koyeb.com/) (Alternativa interessante com tier gratuita)

    * [Fly.io](https://fly.io/) (Exige um pouco mais de configuração, mas é muito poderoso)

* **O Repositório:** Seu código deve estar em um repositório **público** no GitHub. O nome do repositório deve seguir o padrão: `seu-nome-enem-ai-challenge`.

* **Documentação (O seu README):** O README é a vitrine do seu código! É aqui que você vai "vender" o seu projeto para o nosso time. O seu repositório deve conter um `README.md` caprichado explicando:

  *  **Link do Deploy:** Coloque o link da sua aplicação rodando logo no topo do README.

  * Qual foi a sua ideia para o uso da IA no projeto.

  * Como rodar o seu projeto localmente (passo a passo para o avaliador).

  * **Prints ou GIFs** da aplicação funcionando (mostre a tela de login, o dashboard, a IA respondendo, etc).

  * *Atenção:* **NÃO** suba a sua API Key no GitHub! Use variáveis de ambiente (`.env`) 

  * 💡 *Inspiração:* Quer ver exemplos de repositórios open-source com READMEs muito bem feitos para se inspirar? Dê uma olhada no [Supabase](https://github.com/supabase/supabase), no [React](https://github.com/facebook/react) ou explore a lista [Awesome README](https://github.com/matiassingers/awesome-readme).

* **Boas Práticas:** Código limpo, legível e organizado.

* **Commits:** Faça commits semânticos e pequenos. Queremos ver a evolução do seu pensamento durante o desenvolvimento.

## 🌟 Diferenciais (Bônus)

*Não é obrigatório, mas vai destacar muito o seu perfil:*

* **UI/UX:** Uma interface bonita, amigável e responsiva (sinta-se livre para usar Tailwind, Material UI, Chakra UI, etc).

* **Testes:** Testes unitários básicos no frontend ou backend.

* **TypeScript:** Utilização de TS no lugar de JS puro.

## ⚖️ Critérios de Avaliação

O que nosso time de engenharia vai olhar no seu projeto:

1. **Autonomia e Capacidade de Aprender:** Como você lidou com o que não sabia (ex: ler a documentação da API do Gemini e implementá-la com sucesso, fazer o deploy da aplicação).

2. **Criatividade e Foco no Usuário:** A ideia da IA faz sentido? Resolve uma dor real de quem estuda?

3. **Qualidade e Arquitetura do Código:** Como você organizou as pastas, separou as responsabilidades (Frontend vs Backend) e nomeou variáveis/funções.

4. **Uso do Git:** Como você documenta o desenvolvimento através dos commits.

## 📦 Como Entregar

1. Crie o seu repositório seguindo as regras acima.

2. Desenvolva e faça o deploy da solução.

3. Envie o link do seu repositório público (que já deve conter o link do deploy no README) para o mesmo email que você recebeu o desafio com o assunto "Desafio Estágio - Seu Nome" até 8 dias após o recebimento do email do desafio técnico.

🫂 **Não conseguiu terminar tudo? Envie mesmo assim!**
Sabemos que a vida é corrida e imprevistos acontecem. Se por algum motivo você não conseguir finalizar 100% dos requisitos até o prazo, não desista! **Entregue o que você conseguiu fazer até a data máxima**. Nosso time vai avaliar o seu código, a sua lógica e o seu esforço com muito carinho e atenção. O mais importante é mostrar a sua evolução.

🆘 **Dúvidas?**
Caso você tenha alguma dúvida durante o desenvolvimento e nem o Google, nem alguma IA consigam te ajudar, não hesite em entrar em contato com o nosso time através do e-mail: `kelwin.ferreira@hyperflow.global`.

Estamos ansiosos para ver o que você vai construir. Boa sorte e divirta-se codando! 🚀


## 🌱 Para a vida

Sabemos que a vida de estudante (e de dev!) é cheia de desafios. Por isso, queremos te deixar duas dicas que vão te ajudar muito, não só neste processo seletivo, mas em toda a sua jornada acadêmica e profissional:

*   **[GitHub Student Developer Pack](https://education.github.com/pack):** O GitHub oferece um pacote incrível e totalmente gratuito para estudantes verificados. O pacote inclui dezenas de benefícios como licenças grátis de ferramentas profissionais, hospedagem em nuvem, domínios gratuitos e até acesso ao GitHub Copilot! Basta se cadastrar com o seu e-mail da faculdade.
*   **[Gemini para Estudantes](https://gemini.google/students/):** O Google também conta com um plano focado em universitários (geralmente garantindo recursos avançados da IA sem custo por um longo período). É a ferramenta perfeita para te ajudar a criar cronogramas, resumir PDFs imensos da faculdade e aprender novos conceitos de programação mais rápido. Vale muito a pena resgatar!

