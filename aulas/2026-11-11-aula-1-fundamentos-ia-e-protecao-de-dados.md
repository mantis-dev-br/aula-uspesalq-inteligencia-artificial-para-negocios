# IA, LGPD e Compliance — Aula 1 (11/11/2026)

**Profa. Cristina Godoy** (FDRP/USP, CIAAM/USP, IEA/USP) · MBA USP/Esalq · Minicurso "IA, LGPD e Compliance: O Que Toda Empresa Precisa Saber"
**Tema:** Fundamentos — Inteligência Artificial e Proteção de Dados
**Live:** https://www.youtube.com/live/xoYk40pAxOk

> Anotações pessoais, resumidas a partir dos slides e da legenda automática da transmissão. Alguns trechos da legenda vieram incompletos (em especial de ~53 a ~75 min e de ~139 a ~153 min); nesses casos, entrou só o que dava para ler com segurança. Avisos da moderação não foram incluídos.

---

## Resumo pelos slides

### Parte I — Panorama da IA nas organizações

- **Adoção ≠ transformação:** a maioria relata ganho de produtividade, mas poucas empresas convertem isso em resultado financeiro (EBIT). Valor vem de redesenhar processos, não só de adotar ferramentas (McKinsey, 2026).
- **Dados de adoção (OCDE):** são fotografias de anos e países diferentes, não servem como ranking. Porte importa: médias empresas adotam bem mais que pequenas.
- **Onde a IA cria valor (WEF):** experiência do cliente, operações (menos defeitos, retrabalho e estoque), entre outros eixos. IA não é sinônimo de IA generativa.
- **Evolução:** sistemas especialistas (regras) → machine learning → LLMs → IA agêntica.
- **Solução corporativa com LLM:** exige dados, integrações e controles. Risco de "AI sprawl": ferramentas proliferam mais rápido que a governança.
- **IA agêntica:** muito interesse, retorno ainda limitado; previsões do Gartner apontam para modelos especializados e agentes.
- **Projetos bem-sucedidos:** patrocínio da liderança, dados de qualidade, governança e gestão da mudança.
- **Síntese:** a pergunta não é só "o que a IA faz", mas "sob quais condições".

### Parte II — Oportunidades, riscos e desafios éticos

- **Princípio central:** quanto mais autonomia damos à IA, maior deve ser a capacidade de avaliar, controlar e responsabilizar.
- **Nem toda IA é chatbot:** ML aprende com exemplos (ex.: risco de inadimplência); deep learning aprende representações complexas; LLM prevê sequências de tokens, então a resposta é probabilística.
- **Não confundir:** RAG (busca documentos no momento da resposta) × fine-tuning (ajusta parâmetros) × treinamento (cria o modelo).
- **Agente de IA:** objetivo → planejamento → uso de ferramentas (CRM, e-mail etc.) → execução. A diferença entre chatbot, agente e robô está no nível de autonomia e no ambiente de atuação.
- **Trabalho:** potencial técnico de automação ≠ desemprego. O trabalho é reorganizado; habilidades humanas continuam sendo demandadas (McKinsey, 2025).
- **Equilíbrio:** cada oportunidade tem um risco correspondente; evitar tratar a IA só como benefício ou só como ameaça.
- **Seis famílias de risco (OCDE):** privacidade, discriminação, transparência, autonomia, segurança e responsabilização.
- **Recrutamento com IA:** ganho de velocidade × risco à equidade. Discriminação algorítmica nasce de dados históricos com padrões injustos.
- **IA generativa:** alucinação; uma resposta convincente pode estar errada.
- **Liderança ética:** não basta publicar princípios; é preciso ter controles verificáveis.
- **Supervisão humana:** deve ser real, não decorativa, e proporcional ao impacto da decisão.
- **Caso para debate:** agente de RH corporativo, uma decisão tecnológica com impactos jurídicos e éticos.
- **Ponte para a LGPD:** cinco perguntas para qualquer projeto de IA — finalidade, dados, base legal, direitos do titular e responsabilização.

### Parte III — Princípios da LGPD e IA

- **A IA não suspende a LGPD:** proteção de dados é direito fundamental (CF, art. 5º, LXXIX — EC 115/2022).
- **Dado pessoal:** depende da identificabilidade da pessoa; atenção a dados sensíveis e anonimização.
- **O ciclo de vida da IA também é um ciclo de dados:** coleta → curadoria → treino → uso → eliminação/auditoria.
- **Art. 6º:** os 10 princípios devem virar requisitos de sistema e controles verificáveis.
- **Necessidade:** mais dados nem sempre significam IA melhor; compare arquiteturas e minimize a exposição.
- **Bases legais (arts. 7º e 11):** consentimento não é solução universal; o enquadramento depende da finalidade e do tipo de dado.
- **Transparência em IA generativa:** ainda é um desafio empírico.
- **Art. 20:** direito à revisão de decisões tomadas unicamente por tratamento automatizado (crédito, seleção etc.). Explicabilidade ≠ abrir o código-fonte; precisa ser útil, contextual e auditável.
- **Princípio da precaução e responsabilização:** risco e incerteza exigem processos de governança.
- **ANPD:** tomada de subsídios sobre IA (124 contribuições, Nota Técnica 12/2025) e Radar Tecnológico 3 sobre IA generativa (dados de treino, transparência, direitos).
- **Governança:** definir controlador × operador; contratos sozinhos não resolvem.
- **RIPD (art. 38) e documentação:** mapa de dados, riscos e salvaguardas para demonstrar conformidade.
- **Sandbox regulatório ANPD + CIAAM/USP:** ciclos de teste em setores distintos (ex.: saúde), produzindo evidências (hipótese → protocolo → teste → aprendizado).
- **Estudo de caso:** hospital usando LLM externo como assistente.
- **Checklist antes de colocar IA em produção:** finalidade definida, dados necessários, base legal, direitos do titular, revisão humana, RIPD e segurança.

---

## Destaques da fala da professora

### Até ~51 min

- **Sandbox ANPD + CIAAM/USP:** a professora coordena o sandbox de IA e proteção de dados com a ANPD; 18 meses de trabalho, 3 empresas (mobilidade urbana, saúde e cibersegurança no setor financeiro) e 8 relatórios publicados na comemoração dos 6 anos da ANPD.
- **Mudança de perspectiva:** a IA deixou de ser só uma tecnologia e passou a ser um fenômeno econômico, social e organizacional, que muda tarefas, empresas e relações de trabalho.
- **Produtividade autorreportada ≠ ganho real:** os 80% de "ganho de produtividade" (McKinsey) são percepção dos respondentes, não medição de tempo, qualidade ou valor. Produzir mais rápido não é produzir melhor: um relatório feito em 10 min pode exigir 2 h de revisão. Tempo bruto economizado ≠ ganho líquido.
- **80% × 37% × 6% × 11%:** não são etapas de um funil, e sim indicadores com critérios diferentes. A conclusão válida é que o uso da IA está muito mais difundido do que a transformação estrutural das organizações. A IA também tem custo, e revisão e tecnologia podem neutralizar parte do ganho.
- **Tecnologia de propósito geral:** os benefícios dependem de investimentos complementares (processos, infraestrutura, qualificação, instituições). Analogia: a eletrificação só rendeu quando a produção foi reorganizada, mas isso não garante que a IA siga o mesmo caminho.
- **Automação de tarefa × transformação de processo:** ~3/4 das empresas de alta performance redesenharam workflows, contra ~1/4 das demais. Exemplo do jurídico: usar um chatbot para ler contratos é ganho individual; integrar recebimento, classificação, cláusulas sensíveis e políticas é transformação. Meça o processo inteiro (tempo total, retrabalho, erros, custo, qualidade), não os minutos poupados.
- **Dados antes da IA:** com planilhas incompletas ou dados truncados, a IA gera mais erro e retrabalho e o ROI cai. Nem todo departamento ou empresa está pronto.
- **Correlação ≠ causalidade:** empresas maduras têm ao mesmo tempo melhor governança, mais investimento e equipes qualificadas, então não dá para atribuir o resultado só ao redesenho. Leia os relatórios de forma crítica.
- **Ranking da OCDE:** Brasil 13% × EUA 6,6% não significa que o Brasil esteja à frente. Os anos (2020, 2021, 2023), as definições de IA e o porte das empresas são diferentes. Compare só indicadores compatíveis.
- **Adoção extensiva × intensiva:** ter IA ("usamos IA? sim") é diferente da profundidade de uso (quantos departamentos e processos). Um índice binário não mede transformação.
- **Porte:** no Reino Unido, 15% das pequenas e 34% das médias empresas adotam IA, diferença de 19 pontos percentuais (não 19%). Causas: custos fixos, infraestrutura e qualidade de dados. Adoção e piloto não se somam.
- **Cinco eixos de valor (WEF/Accenture):** experiência do cliente; operações e cadeia de suprimentos; P&D e inovação; planejamento estratégico e decisão; gestão de pessoas (RH é onde mais se vê adoção).
- **Tipos de sistema:** descritivo (padrões), preditivo (estima o futuro), prescritivo (recomenda ações) e generativo (cria conteúdo de forma probabilística). Avaliar risco pensando só em chatbot é inadequado.
- **Métricas de cliente:** churn e cost to serve. Dados "neutros" (consumo, pagamentos, navegação) podem permitir inferências sensíveis. Um chatbot que resolve 90% das demandas mas erra nas críticas tem KPI bom e risco jurídico alto. Escolha os KPIs com cuidado.

### De ~52 a ~75 min

- **Avaliar além de velocidade e economia:** incluir precisão, segurança, satisfação do usuário, taxa de erro (matriz de confusão), necessidade de intervenção humana e risco no tratamento de dados.
- **Não somar percentuais de relatórios:** 25% de retenção + 8% de receita não dão um ganho agregado. São métricas com unidades e contextos diferentes, não uma promessa universal de retorno.
- **Operações:** é onde a IA mostra vantagem mais clara, porque já existem indicadores técnicos (defeitos, prazos). Manutenção preditiva lê sinais dos equipamentos antes da falha, em vez de agir só depois (manutenção corretiva).
- **Correlação ≠ causalidade (de novo):** o modelo encontra padrões, não causas. Exemplo de gestão de estoque: equilibrar excesso e falta de produtos.
- **Governança de dados e drift:** um modelo pode ir bem com o ambiente estável e piorar quando ele muda (data/concept drift, ex.: mudança no padrão de consumo). Implantar não basta: é preciso monitorar continuamente.
- **Risco depende da finalidade:** agendar consultas não é o mesmo que influenciar uma decisão clínica. Apoiar a decisão humana é diferente de produzir a própria decisão.
- **Automation bias:** manter formalmente um humano no processo não garante supervisão real. A pessoa tende a confiar na resposta da máquina.
- **Famílias tecnológicas:** sistemas especialistas (regras definidas por especialistas, comuns em compliance); ML supervisionado (exemplos rotulados), não supervisionado (agrupamentos) e por reforço (recompensas); deep learning (muitas camadas, de difícil interpretação humana); IA generativa e LLMs (preveem tokens).
- **LLM não "compreende":** aprende relações estatísticas. Há debate sobre raciocínio e generalização, mas isso não equivale à compreensão nem à intencionalidade humanas.
- **Agentes:** LLM + planejamento + acesso a ferramentas. Um sistema que responde perguntas não é equivalente a um que executa ações. A sequência do slide é didática, não uma progressão obrigatória.
- **Arquitetura corporativa:** entre a aplicação e o modelo ficam autenticação, controle de acesso, segregação de informações (vários clientes no mesmo modelo) e logs — quais dados entraram, quais informações foram acessadas e qual ferramenta foi acionada. Isso é base de responsabilização.
- **RAG × fine-tuning × treinamento:** RAG busca documentos da empresa na hora da resposta, sem retreinar. Fine-tuning altera parâmetros. Treinamento cria o modelo. Se o fornecedor usar prompts e dados enviados para treinar, há tratamento de dados sob a LGPD.

### De ~75 min ao intervalo (~93 min)

- **RAG e fine-tuning se combinam:** primeiro tente RAG; se não resolver, faça fine-tuning com treinamento adicional. São abordagens para momentos diferentes do projeto.
- **AI sprawl na prática:** ela já foi chamada por multinacionais em que cada funcionário usava uma ferramenta própria, fora da governança, enviando contratos e dados de clientes, com risco até para o segredo empresarial. Segundo a OutSystems (2026), só ~12% das empresas tinham tomado medidas concretas contra isso.
- **Consequências do sprawl:** dados dispersos, governança interna enfraquecida, recomendações diferentes para situações iguais e ferramentas usadas sem aprovação. Remédio: políticas de uso, inventário de ferramentas e rastreabilidade das decisões.
- **IA agêntica e ROI:** interesse tecnológico não significa lucro. Medir o ROI considerando licenças, integração e custos recorrentes contra os benefícios. Quanto mais o agente pode alterar registros ou executar transações, maior o risco.
- **Previsões do Gartner:** são projeções baseadas em hipóteses, não resultados observados. Tendência: combinar modelos especializados com orquestração (o sistema escolhe o modelo conforme a tarefa e o custo computacional) e usar modelos locais, no próprio servidor, para não enviar dados a terceiros.
- **Projetos bem-sucedidos (estudo com 11 organizações):** liderança, governança de dados (dados incompletos derrubam o projeto), integração com sistemas legados, segurança, privacidade e supervisão, que é diferente de revisão. Cuidado com a validade externa: o que deu certo numa empresa não se repete automaticamente em outra.
- **Conclusão do bloco:** há ganhos de produtividade individual, mas desempenho tecnológico (o que o modelo faz) não é resultado organizacional. Ex.: uma ferramenta de recrutamento eficiente ainda precisa provar confiabilidade e justiça.
- **Política no papel não basta:** é preciso produzir evidências (documentação, testes), como foi feito no sandbox da ANPD. Gancho para o próximo bloco: instrumentos jurídicos.

### Após o intervalo

_Recaptura linha a linha da legenda. Entre ~139 e ~153 min a legenda veio com falhas; ali entrou só o que deu para ler com segurança._

#### Perguntas da turma (~117–125 min)

- **Maior gargalo da LGPD hoje:** não é falta de norma nem de fiscalização. A ANPD virou agência, tem cerca de 400 servidores, já aplica multas e autua empresas, e por decreto passou a coordenar o SIA (sistema nacional de governança de IA, previsto no PL 2338, aprovado no Senado e hoje na Câmara). O gargalo é cultural: proteção de dados e segurança da informação ainda não foram incorporadas pelas pessoas. Há política de privacidade no papel, mas alguém cola CPFs no ChatGPT "porque ninguém vai perceber". A adesão ainda é movida pelo medo da multa, não pela importância de proteger os dados.
- **Usar ChatGPT, Gemini ou nuvem é transferência internacional?** Sim: esses modelos rodam em outros países (ex.: EUA), então valem as regras da LGPD para transferência internacional, que muitas empresas não seguem. Esse foi um ponto do sandbox. Mesmo com IA local (modelo baixado e rodando no próprio servidor), pergunte onde fica o backup: backup fora do país também é transferência. Com dados pessoais ou sensíveis sem essas cautelas, há violação da LGPD.
- **IA aumenta o risco de vazamento?** O risco existe com ou sem IA (às vezes é o próprio funcionário que leva os dados); por isso controle de acesso e gestão de dados. Vazamento "não é se, mas quando". A IA pode facilitar, sobretudo com agentes. Caso de 2026: uma empresa americana de agentes de IA para saúde, contratada por um hospital de Nova York, errou a configuração do Elasticsearch e expôs dados de mais de 400 mil pacientes, gerando uma class action. A IA também serve para defesa: contra ataques automatizados em larga escala, o time de cibersegurança precisa de IA de apoio.

#### Parte II — Oportunidades, riscos e desafios éticos

- **Abertura do bloco (slide 21):** eficiência não significa uso adequado, seguro ou legítimo. Mesmo com ROI positivo, há uma segunda camada de análise: legitimidade e segurança. Dois erros comuns: tratar tecnologias diferentes como iguais (classificar imagem médica ≠ LLM) e generalizar o risco (um resumo de texto ou o Grammarly ≠ um agente que movimenta dinheiro ou rejeita candidatos). Três conceitos: capacidade (o que o sistema faz), autonomia (quanto age sozinho; ex.: níveis de autonomia dos carros) e impacto (efeito sobre pessoas e organizações). Eles não andam juntos: alta capacidade pode ter baixa autonomia, e um sistema simples pode ter muito poder. Regra de governança: quanto maior o impacto e a autonomia, maior a exigência de avaliação, controle, supervisão e responsabilização (proporcionalidade, não fórmula matemática). Risco ≠ erro técnico: um sistema que funciona como projetado ainda pode ser injusto ou ilegal.
- **Mapa das tecnologias (slide 22):** IA é um campo amplo (classificar, prever, reconhecer padrões, planejar, gerar conteúdo, apoiar decisão); IA, ML, redes neurais, LLM e chatbot não são sinônimos. ML ajusta modelos a partir de dados (exige muito volume). Deep learning é uma família de ML baseada em redes neurais com camadas ocultas (daí a pirâmide invertida). IA generativa cria conteúdo novo (imagem, voz, texto são aplicações distintas). Nem toda IA é ML: há a tradição simbólica (regras explícitas, inferência lógica, sistemas especialistas, IA de videogame) e a conexionista (redes neurais); sistemas híbridos combinam as duas. Isso pesa na explicabilidade: em regras dá para apontar a condição que gerou a resposta; em redes neurais pode ser impossível dizer como a IA decidiu. A arquitetura limita a transparência.
- **Machine learning: risco de inadimplência (slide 23):** um banco treina um modelo supervisionado com o histórico de crédito. Features (variáveis de entrada: renda declarada, histórico de pagamento, comprometimento financeiro) e target (variável-alvo: inadimplir em certo período). O treino minimiza a loss function (diferença entre o previsto e o real). Treinar ≠ generalizar: no overfitting o modelo "decora" e falha em casos novos; por isso se separam dados de treino, validação e teste, e a matriz de confusão ajuda a detectar (ela está lidando com overfitting num projeto agora). Data leakage: usar informação que não existiria no momento da previsão. E aprendizado estatístico não garante justiça: se o histórico de crédito carrega desigualdade, o modelo reproduz, mesmo sem usar variável protegida, por correlação com outras variáveis (proxies).
- **Deep learning e explicabilidade (slide 24):** rede neural = pesos ajustados no treino, em várias camadas; nas profundas, as relações ficam distribuídas, o que dificulta explicar. Daí a XAI (Explainable AI): técnicas para tornar o comportamento compreensível a desenvolvedores, auditores, gestores e afetados, em geral com aproximações locais. Ressalva: distinguir explicação fiel ao modelo de explicação apenas plausível, o que é relevante para direitos individuais.
- **LLM e como ele responde (slides 25–26):** modelos treinados para processar e gerar linguagem, aprendendo regularidades dos dados; geram o próximo token a partir do texto anterior, sem consultar frases prontas. Gerar a resposta é a inferência, guiada pelo contexto do prompt. Não confundir janela de contexto com memória persistente, nem parâmetros com dados de treino. Riscos: geração não fundamentada e erro factual ("alucinação"); resumir também exige escolhas (o que entra e o que sai). Chatbots existiam antes dos LLMs. O que vai ao fornecedor depende da arquitetura usada.
- **Treinamento × fine-tuning × RAG (slide 27):** treinamento ajusta os parâmetros por otimização (é onde ocorre o aprendizado estatístico). Fine-tuning é treino adicional para adaptar o modelo a tarefas, estilos e domínios; funciona bem para taxonomias (ex.: taxonomia de fraude, junto com ontologia), mas não para documentos que mudam o tempo todo. RAG recupera documentos relevantes (ex.: base de pareceres de um escritório) e os coloca no contexto da resposta, em geral por busca semântica, embeddings/base vetorial e ranqueamento, mas pode usar busca tradicional ou híbrida. RAG não garante verdade: pode recuperar o documento errado, omitir ou interpretar mal. E não elimina o risco de dados: a recuperação precisa respeitar permissões, finalidade e segregação, ou vaza documento confidencial para quem não deveria ver, mesmo sem treino com ele. Três perguntas ao contratar IA: (1) quais dados ajustam os parâmetros? (2) quais dados são recuperados no uso? (3) quais dados vão ao fornecedor na inferência? Cada uma exige análise jurídica e de segurança. Resumo: treino altera parâmetros (aprender capacidades); fine-tuning altera parâmetros (adaptar); RAG não altera (traz informação na hora da resposta). A escolha é também de governança, não só de engenharia.
- **O que é um agente de IA (slide 28):** sistema que recebe objetivos, percebe o ambiente, escolhe procedimentos e executa ações conforme capacidades e autorizações. O conceito é anterior aos LLMs; hoje designa LLMs conectados a ferramentas. Exemplo: para organizar propostas comerciais, o chatbot explica como fazer; o agente consulta o CRM, classifica e encaminha. Etapas: objetivo → planejamento → acesso a ferramentas (APIs, bancos, sistemas, busca) → execução → avaliação e controle. Não atribuir autonomia ilimitada: as ações dependem de permissões e limites (um agente que só consulta não altera registros). Recomendação dela: o agente recomenda e um humano aprova antes de executar. Human in the loop (humano dentro do processo decisório), on the loop (supervisiona e pode intervir) e out of the loop (sem intervenção). Esses arranjos não são, sozinhos, garantia de segurança nem categoria jurídica. Quanto mais ações externas, mais importam limites de autorização, rastreabilidade e botão de parada, sobretudo com dados pessoais.
- **Chatbot × agente × robô (slide 29):** chatbot com LLM interage pela linguagem; agente organiza operações, usa ferramentas e age; robô atua no mundo físico (sensores e atuadores). Nem todo robô usa ML, nem todo agente tem corpo, e as fronteiras se misturam (agentes podem comandar equipamentos). A McKinsey (fim de 2025) associa agentes a tarefas não físicas e robôs a físicas: útil para economia, não é definição universal. Consequências: chatbot que erra uma resposta < agente que altera cadastro ou autoriza procedimento < robô que pode ferir pessoas. Juridicamente, evitar antropomorfizar: o sistema não tem personalidade nem vontade jurídica; alguém é sempre responsável, e é quem a documentação de governança aponta como responsável por aquela decisão.
- **Trabalho humano + agentes + robôs (slide 30):** McKinsey: 57% das horas de trabalho atuais nos EUA têm potencial técnico de automação (44 p.p. por agentes digitais, 13 p.p. por robôs). É potencial teórico, não previsão de desemprego; a unidade são horas de atividade, não empregos nem ocupações. Uma ocupação é um conjunto de tarefas (no jurídico: pesquisa, triagem e minutas são automatizáveis; negociação, interpretação, estratégia e responsabilidade profissional não). E não se deve depender 100% da IA: médicos precisam continuar sabendo operar, e se o sistema cair, as pessoas precisam saber fazer. Quatro viabilidades: técnica, econômica (às vezes o humano sai mais barato), organizacional (infraestrutura, dados, competências) e jurídica/social. Debate econômico: efeito substituição (desemprego) × efeito produtividade (mais demanda, novas tarefas). Nada é automático: depende de instituições, qualificação e organização do trabalho, e quem perde a vaga nem sempre migra para as novas funções. No Brasil, há locais sem infraestrutura nem para processar dados. Objetivo dela no curso: rejeitar conclusões simplistas (nem desemprego proporcional ao potencial, nem ganho automático para todos). Tema bom para TCC.
- **Habilidades humanas (slide 31):** mais de 70% das competências pedidas pelos empregadores são usadas tanto em atividades automatizáveis quanto nas não automatizáveis (McKinsey). Tarefa é a atividade concreta (fazer um relatório, revisar planilha, classificar documento); competência é o conhecimento e a habilidade mobilizados em várias tarefas. Interpretar informação, formular boas perguntas, avaliar evidências, achar inconsistências e assumir responsabilidade ficam mais importantes. Mas nem todas as competências se valorizam igual: umas sobem, outras caem. Destaque para a AI fluency, que não é só escrever prompts: é entender capacidades e limites, escolher boas aplicações, interpretar resultados e saber quando o humano precisa intervir. Mudança tecnológica enviesada por competências: diferente da Revolução Industrial, a IA atinge também quem tem ensino superior e pós, e mostra que tarefas cognitivas complexas podem ser parcialmente automatizadas. A lição que ela pediu para fixar: isso não elimina a diferença entre executar, julgar, responder e compreender; o desafio das empresas é redesenhar funções e qualificação. Há ainda uma dimensão distributiva (quem terá acesso, como não ampliar desigualdades), por isso avaliar IA não se resume a produtividade. Ressalva: o "crescimento de 7x" na procura por certa competência é variação relativa nos anúncios, não 7x mais contratados.
- **Três oportunidades, três riscos (slide 32):** o risco nasce do mesmo mecanismo que gera o benefício. (1) Personalização: adaptar serviços e recomendações, mas permite perfilização excessiva, inferências indevidas e discriminação. (2) Automação: acelera e barateia, mas um erro humano afeta uma decisão, e um erro embutido no sistema pode afetar milhões antes de ser percebido. (3) Eficiência baseada em dados: integrar mais informação revela padrões, mas amplia monitoramento, vigilância, perda de autonomia e exposição.
- **Risk assessment × impact assessment:** avaliação de risco identifica eventos adversos, consequências e fatores, para depois vir o plano de mitigação (está nos relatórios do sandbox). Avaliação de impacto examina de forma estruturada os efeitos sobre pessoas, grupos e direitos; é a exigida no PL 2338 para sistemas de alto risco. Os conceitos se sobrepõem, mas uma análise só de probabilidade de perda financeira deixa de captar danos à dignidade, discriminação e restrição de autonomia.
- **Fechamento:** governança responsável precisa combinar várias dimensões de análise para maximizar oportunidades e reduzir ao máximo o risco, para que a IA seja uma ferramenta de uso responsável.

---

## Referências citadas em aula

- McKinsey Quarterly (out. 2026). *AI is changing work. Now it has to change the organization.*
- OECD/BCG/INSEAD (2025). *The Adoption of Artificial Intelligence in Firms.*
- World Economic Forum / Accenture (mar. 2026) — eixos de transformação organizacional por IA.
- Gartner (ago. 2026). *Emerging Tech Impact Radar: Generative AI.*
- OutSystems (2026). *Introduction to Agentic Systems Engineering.*
- McKinsey Global Institute (nov. 2025). *Agents, robots, and us.*
- OECD (2022). *Using AI in the workplace: What are the main ethical risks?*
- ANPD — Radar Tecnológico nº 3 (IA Generativa, 2024); Nota Técnica nº 12/2025; relatórios do Sandbox de IA (nov. 2026).
- Lei nº 13.709/2018 (LGPD); CF/1988, art. 5º, LXXIX.
