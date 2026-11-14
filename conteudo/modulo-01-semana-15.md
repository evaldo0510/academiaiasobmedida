# Módulo 1 — Semana 15
## Inteligência artificial e transformação digital na marcenaria

**Carga horária sugerida:** 4 horas  
**Competência:** identificar oportunidades de digitalização, utilizar IA como apoio à decisão e estruturar fluxos digitais seguros e mensuráveis em empresas de móveis sob medida.

### Objetivos de aprendizagem
- Diferenciar automação, digitalização, IA generativa e sistemas de gestão.
- Mapear processos da marcenaria e priorizar oportunidades com retorno mensurável.
- Escrever instruções eficazes para IA e validar criticamente as respostas.
- Desenhar fluxos integrados entre comercial, projeto, compras, produção e instalação.
- Proteger dados de clientes, desenhos, contratos e informações comerciais.

> A tecnologia não corrige um processo mal definido por mágica. Primeiro organizamos o trabalho; depois escolhemos onde a tecnologia pode ampliá-lo.

## Aula 1 — Fundamentos de IA e oportunidades na marcenaria

**Digitalização** é converter informações e registros para formatos digitais. **Automação** executa regras e sequências previamente definidas. **Inteligência artificial** reúne métodos computacionais que realizam tarefas associadas a percepção, previsão, classificação ou geração. **IA generativa** produz conteúdos como textos, imagens, resumos e código a partir de instruções e contexto. **Sistema de gestão** organiza cadastros, processos, permissões e registros operacionais.

Essas categorias podem trabalhar juntas, mas não são sinônimas. Uma planilha que calcula margem por fórmula é automação baseada em regra; um modelo que resume um briefing é IA generativa; um sistema que registra o histórico de pedidos é gestão de informação.

### Aplicações possíveis

| Etapa | Aplicação possível | Validação humana |
|---|---|---|
| Comercial | Organizar briefing e preparar perguntas | Confirmar contexto e não inventar requisitos |
| Projeto | Estruturar memorial e comparar versões | Projetista valida medidas, normas e solução |
| Orçamento | Classificar itens e organizar dados | Conferir quantitativos, custos, impostos e margem |
| Compras | Comparar propostas e destacar diferenças | Confirmar especificação, prazo e fornecedor |
| Produção | Gerar instruções e checklists | Encarregado valida sequência e segurança |
| Instalação | Preparar checklist e relatório de pendências | Equipe verifica condições reais e qualidade |
| Pós-venda | Classificar feedback e redigir respostas preliminares | Responsável decide solução e compromissos |

Mapeie uma tarefa repetitiva, frequente, com entradas conhecidas e resultado verificável. Estime volume, tempo gasto, erros, custo do problema e risco de uma resposta incorreta. Priorize atividades administrativas e de apoio antes de automatizar decisões técnicas ou críticas.

### Exercício 1 — Mapa de oportunidades
Escolha um processo da MadePrimer: recebimento de lead, briefing, proposta, revisão de projeto, compra, produção ou assistência. Descreva como funciona hoje, onde ocorre retrabalho, quais dados entram, qual resultado sai e como uma pessoa verifica a qualidade. Proponha uma aplicação digital ou de IA e indique os riscos.

**Critério:** a proposta precisa resolver um problema identificado, não apenas adicionar tecnologia ao processo.

### Referências da Aula 1
1. NIST. [AI Risk Management Framework (AI RMF)](https://www.nist.gov/itl/ai-risk-management-framework).
2. OECD. [OECD AI Principles](https://oecd.ai/en/ai-principles).
3. ISO/IEC. [ISO/IEC 22989 — conceitos e terminologia de IA](https://www.iso.org/standard/81230.html).

## Aula 2 — Engenharia de prompts, dados e validação

Um prompt útil informa: **papel** esperado; **objetivo**; **contexto**; **dados disponíveis**; **restrições**; **formato de saída**; e **critérios de verificação**. Não peça apenas “faça um orçamento”. Informe quais dados existem, quais estão ausentes, o que não deve ser presumido e quais cálculos precisam ser realizados por planilha ou sistema validado.

### Modelo de prompt — organizar briefing
> Atue como assistente de organização comercial de uma empresa de móveis sob medida. Organize as informações em: ambientes; necessidades; medidas informadas; materiais; ferragens; restrições; dúvidas; decisões pendentes; próximos passos. Não invente medidas, preços, normas ou especificações. Marque como “não informado” o que estiver ausente. Separe fatos de hipóteses. Ao final, gere perguntas objetivas para a próxima conversa. Dados: [inserir somente informações autorizadas e necessárias].

Modelos generativos podem produzir conteúdo plausível, porém incorreto. Podem inventar referências, misturar versões, interpretar uma medida de forma errada ou ignorar uma restrição. Não trate fluência como evidência. Confira números, unidades, fórmulas, fontes, compatibilidade e atualidade.

Em cálculos de preço, dimensionamento, carga, fixação, elétrica, segurança de máquinas ou especificação técnica, utilize métodos, documentos e profissionais competentes. A IA pode ajudar a organizar perguntas e revisar documentos, mas não substitui cálculo validado, manual do fabricante, norma aplicável ou responsabilidade profissional.

### Teste antes de incorporar ao processo
1. Crie casos reais anonimizados ou sintéticos.
2. Defina resposta correta e erros inaceitáveis.
3. Teste casos comuns, incompletos e excepcionais.
4. Compare o resultado com referência revisada por especialista.
5. Registre falhas, ajustes e versão do prompt ou ferramenta.
6. Libere o uso gradualmente e monitore a qualidade.

### Dados, privacidade e propriedade intelectual
Não insira em ferramentas públicas dados pessoais, endereços, plantas identificáveis, contratos, preços estratégicos ou informações de clientes sem autorização, base legal, avaliação de segurança e regras internas adequadas. Use minimização, anonimização ou dados fictícios quando possível. Verifique políticas de retenção, treinamento, acesso e compartilhamento do fornecedor da ferramenta. Imagens de ambientes podem revelar rotinas, patrimônio e localização. Respeite direitos autorais, licenças e termos de uso.

### Exercício 2 — Laboratório de prompts
Escreva dois prompts para o mesmo briefing: um vago e outro estruturado. Compare fatos corretos, itens inventados, omissões, clareza, utilidade e necessidade de revisão. Reescreva o prompt para reduzir o principal erro identificado.

**Critério:** demonstrar melhoria verificável e declarar o que ainda exige conferência humana.

### Referências da Aula 2
1. NIST. [AI RMF — Govern, Map, Measure, Manage](https://www.nist.gov/itl/ai-risk-management-framework).
2. UNESCO. [Recommendation on the Ethics of Artificial Intelligence](https://www.unesco.org/en/artificial-intelligence/recommendation-ethics).
3. ANPD. [Materiais orientativos sobre LGPD](https://www.gov.br/anpd/pt-br).
4. OpenAI. [Prompt engineering — documentação técnica](https://platform.openai.com/docs/guides/prompt-engineering).

## Aula 3 — Fluxos digitais, integração e indicadores

Um fluxo confiável conecta a informação criada no primeiro contato às decisões posteriores. Exemplo: lead identificado → briefing estruturado → visita e medidas validadas → proposta versionada → aprovação formal → projeto liberado → compras → produção → inspeção → instalação → entrega → pós-venda. Cada transição deve ter responsável, condição de entrada, saída e registro.

Evite redigitar a mesma informação em várias ferramentas. Quando possível, mantenha um cadastro de referência e identifique qual sistema é a fonte oficial de cada dado. Integrações precisam de permissões, logs, tratamento de erros e possibilidade de correção manual.

### Arquitetura mínima de um fluxo
1. **Entrada:** formulário, mensagem, arquivo ou registro autorizado.
2. **Validação:** campos obrigatórios, unidade, formato, versão e consistência.
3. **Processamento:** regra automatizada ou assistência de IA.
4. **Revisão:** pessoa responsável confirma exceções e resultados.
5. **Saída:** documento, tarefa, alerta ou atualização no sistema oficial.
6. **Auditoria:** data, autor, versão, decisão e histórico de alteração.

### Indicadores de transformação digital
- **Tempo de ciclo:** tempo entre início e conclusão da tarefa.
- **Retrabalho:** correções ou repetições por processo/projeto.
- **Completude:** percentual de registros com campos essenciais preenchidos.
- **Adoção:** uso efetivo do fluxo pela equipe, não apenas contas criadas.
- **Qualidade:** erros detectados antes e depois da implantação.
- **Resultado econômico:** horas poupadas, custo evitado e impacto na margem, com método de cálculo explícito.

Estabeleça uma linha de base antes da mudança. Compare períodos equivalentes e considere sazonalidade, volume e complexidade. Tempo poupado não é automaticamente lucro: é preciso verificar como a capacidade liberada foi utilizada.

### Plano de implantação
1. Selecionar processo pequeno, frequente e de baixo risco.
2. Documentar o fluxo atual e medir a linha de base.
3. Desenhar a versão futura com responsável e controles.
4. Testar com poucos usuários e dados não sensíveis.
5. Revisar erros, segurança, custo e experiência da equipe.
6. Treinar, documentar e ampliar apenas após validação.
7. Reavaliar periodicamente desempenho e dependência do fornecedor.

### Exercício 3 — Projeto-piloto digital
Escolha um processo da MadePrimer e elabore um piloto de 30 dias. Registre problema, objetivo, processo atual, ferramenta candidata, dados utilizados, riscos, responsáveis, custo estimado, linha de base e três indicadores. Defina critérios de sucesso e condições para interromper o piloto.

**Critério:** o projeto deve ser pequeno o bastante para testar, útil o bastante para medir e seguro o bastante para controlar.

### Referências da Aula 3
1. NIST. [AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework).
2. OECD. [OECD AI Principles](https://oecd.ai/en/ai-principles).
3. ISO. [ISO/IEC 22989 — conceitos e terminologia de IA](https://www.iso.org/standard/81230.html).
4. SEBRAE. [Conteúdos de gestão, inovação e transformação digital para pequenos negócios](https://sebrae.com.br/).

## Aplicação prática na MadePrimer
1. Mapear o caminho de um pedido desde o lead até o pós-venda.
2. Identificar três tarefas repetitivas e medir tempo, volume e falhas.
3. Escolher um processo administrativo de baixo risco para o primeiro piloto.
4. Criar padrão de briefing com campos obrigatórios e itens não informados.
5. Testar IA para resumir briefings e preparar perguntas, sempre com revisão humana.
6. Definir a versão oficial de propostas, desenhos e aprovações.
7. Registrar mudanças e decisões em um local de referência.
8. Treinar a equipe sobre dados que não podem ser compartilhados com ferramentas externas.
9. Medir tempo de ciclo, retrabalho, completude e qualidade.
10. Decidir com base em evidências se o piloto deve ser ajustado, ampliado ou encerrado.

## Modelo de ficha de oportunidade digital
- Processo e responsável:
- Problema observado e frequência:
- Tempo/custo atual e linha de base:
- Dados de entrada e fonte oficial:
- Ferramenta ou automação candidata:
- Etapas com revisão humana:
- Riscos de erro, privacidade e segurança:
- Indicadores e critérios de sucesso:
- Prazo, custo e decisão de continuidade:

## Checklist de uso responsável de IA
1. O problema e o objetivo estão definidos?
2. A tarefa é apropriada para IA ou automação?
3. Os dados podem ser usados nessa ferramenta e finalidade?
4. Informações pessoais e estratégicas foram minimizadas?
5. As fontes, números e especificações serão conferidos?
6. Há responsável humano pela aprovação?
7. Existe registro de versão, decisão e correção?
8. O fluxo prevê exceções e falhas da ferramenta?
9. O resultado será medido contra uma linha de base?
10. A equipe sabe quando não confiar ou interromper o uso?

## Entrega avaliativa da semana
- Mapa de oportunidades de digitalização.
- Dois prompts testados e comparados.
- Fluxo digital futuro com entradas, controles e responsáveis.
- Ficha de oportunidade digital preenchida.
- Piloto de 30 dias com linha de base, indicadores e critérios de interrupção.

**Rubrica sugerida:** diagnóstico do problema; qualidade do desenho do fluxo; validação e supervisão humana; proteção de dados; mensuração do resultado. Cada critério vale 0–2 pontos. Total: 10 pontos. Recomenda-se nota mínima de 7.

## Glossário
- **IA generativa:** sistemas que geram conteúdo a partir de instruções e contexto.
- **Prompt:** instrução fornecida a um modelo de IA.
- **Alucinação:** resposta gerada que apresenta informação falsa ou não sustentada como se fosse verdadeira.
- **Automação:** execução de tarefas por regras e sequências predefinidas.
- **Digitalização:** conversão e organização de informações em formato digital.
- **Integração:** troca controlada de dados entre sistemas.
- **Fonte oficial:** local definido como referência válida para determinado dado ou documento.
- **Linha de base:** medida inicial usada para comparar o efeito de uma mudança.
- **Supervisão humana:** revisão e decisão por pessoa responsável.
- **Governança de IA:** regras, papéis e controles para uso responsável de sistemas de IA.

## Referências gerais da semana
1. NIST. [AI Risk Management Framework (AI RMF)](https://www.nist.gov/itl/ai-risk-management-framework).
2. OECD. [OECD AI Principles](https://oecd.ai/en/ai-principles).
3. UNESCO. [Recommendation on the Ethics of Artificial Intelligence](https://www.unesco.org/en/artificial-intelligence/recommendation-ethics).
4. ISO/IEC. [ISO/IEC 22989 — concepts and terminology](https://www.iso.org/standard/81230.html).
5. ANPD. [Guias orientativos sobre LGPD](https://www.gov.br/anpd/pt-br).
6. OpenAI. [Documentação técnica de engenharia de prompts](https://platform.openai.com/docs/guides/prompt-engineering).

> **Nota de rigor:** IA generativa pode produzir erros, omissões e conteúdo desatualizado. Não use suas respostas como validação independente de medidas, cargas, dimensionamento, segurança, normas, preços ou obrigações legais. Decisões técnicas devem ser verificadas por profissionais competentes e documentação aplicável. A referência a frameworks e normas não implica certificação da empresa nem garante conformidade. O uso de dados pessoais deve observar a LGPD, contratos e políticas da ferramenta escolhida.
