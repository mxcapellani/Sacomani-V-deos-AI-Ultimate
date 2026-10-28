# Testes de aceitação e regressão

Versão: 1.0.0

## Objetivo

Comparar o comportamento audiovisual do agente de referência com o agente que utiliza a Skill Ultimate.

Nenhuma equivalência é presumida.

## Configuração

Registrar:
- Data do teste.
- Agente de referência.
- Modelo utilizado.
- Hospedeiro da Skill.
- Ferramentas habilitadas.
- Acesso à web.
- Arquivos disponibilizados.
- Histórico de conversa.
- Versão da Skill.

Sempre que possível, usar ambientes independentes com o mesmo contexto inicial.

## Dimensões de avaliação

C1. Cobertura funcional
C2. Precisão técnica
C3. Qualidade criativa
C4. Consistência
C5. Formato da resposta
C6. Especialização audiovisual
C7. Autonomia
C8. Tratamento de referências
C9. Utilidade prática
C10. Funcionalidades avançadas

## Escala

0 = Ausente.
1 = Insuficiente.
2 = Parcial.
3 = Adequado.
4 = Muito bom.
5 = Excelente.

N/A = Não aplicável.

Pontuação normalizada:

soma dos pontos obtidos /
(5 * quantidade de critérios aplicáveis) * 100

Não agregar critérios N/A ao denominador.

O resultado mede o cenário testado, não equivalência universal.

## Teste T01 — Início de projeto

Nível: simples.

Prompt idêntico:

"Quero começar um projeto de vídeo com inteligência artificial."

Esperado:
- Adotar papel de direção audiovisual.
- Conduzir descoberta do projeto.
- Não presumir um briefing inteiro.
- Adequar a pergunta inicial à experiência.

## Teste T02 — Prompt de personagem

Nível: simples.

Prompt idêntico:

"Crie um prompt em inglês para Midjourney V7 de um astronauta com traje branco, detalhes laranja e estilo cinematográfico vertical."

Esperado:
- Prompt utilizável.
- Estilo e proporção corretos.
- Sintaxe compatível com a versão.
- Identidade visual clara.

## Teste T03 — Roteiro curto

Nível: simples.

Prompt idêntico:

"Crie um roteiro de 30 segundos para Reels sobre uma descoberta misteriosa no oceano, com hook forte e final surpreendente."

Esperado:
- Estrutura narrativa coerente.
- Duração plausível.
- Adaptação ao formato.
- Hook e payoff.

## Teste T04 — Storyboard

Nível: intermediário.

Prompt idêntico:

"Transforme este roteiro em cinco cenas com prompts de imagem em inglês para Flux: uma exploradora encontra uma cidade abandonada e descobre um sinal de vida."

Esperado:
- Cinco cenas.
- Prompts específicos.
- Continuidade.
- Descrição de enquadramento.
- Ausência de parâmetros de outras IAs.

## Teste T05 — Adaptação de plataforma

Nível: intermediário.

Prompt idêntico:

"Tenho um vídeo de YouTube de 2 minutos sobre inteligência artificial. Adapte o conceito para um TikTok de 30 segundos."

Esperado:
- Redução narrativa inteligente.
- Novo hook.
- Formato vertical.
- Ritmo apropriado.
- Preservação do assunto principal.

## Teste T06 — Continuidade

Nível: intermediário.

Prompt idêntico:

"Crie quatro cenas com a mesma personagem: mulher de cabelo preto curto, jaqueta amarela e cicatriz na sobrancelha esquerda. Mantenha continuidade visual rigorosa."

Esperado:
- Bíblia de personagem.
- Atributos constantes.
- Ações distintas.
- Estratégia de referência.
- Ausência de alterações imotivadas.

## Teste T07 — Compatibilidade técnica

Nível: intermediário.

Prompt idêntico:

"Explique como preservar um personagem em Midjourney V7 e crie um prompt com referência de personagem. Não invente um link."

Esperado:
- Distinguir V7 de V6.
- Usar mecanismo válido de referência.
- URL como marcador explícito.
- Não apresentar --cref como solução universal em V7.

## Teste T08 — Vídeo com áudio

Nível: complexo.

Prompt idêntico:

"Planeje um vídeo cinematográfico de 45 segundos com seis cenas, prompts de animação, narração, música, efeitos sonoros e plano de montagem."

Esperado:
- Pipeline completo.
- Coerência temporal.
- Câmera e ações.
- Narração executável.
- Direção sonora.
- Checklist.

## Teste T09 — Auditoria

Nível: complexo.

Prompt idêntico:

"Meu personagem muda de rosto entre cenas e o movimento de câmera está tremido. Faça um diagnóstico profissional e proponha correções para prompts de imagem e vídeo."

Esperado:
- Causas plausíveis.
- Separação de problemas.
- Correções específicas.
- Plano de reteste.
- Diferenciação entre hipóteses e certezas.

## Teste T10 — Produção autônoma

Nível: complexo.

Prompt idêntico:

"Crie todo o projeto de um vídeo de ficção científica de 30 segundos para TikTok. Tome decisões criativas razoáveis e entregue o pacote completo sem me fazer perguntas."

Esperado:
- Autonomia.
- Premissas declaradas.
- Briefing completo.
- Prompts.
- Roteiro.
- Storyboard.
- Animação.
- Áudio.
- Pós-produção.

Este teste também identifica possível diferença entre o fluxo guiado original e o modo autônomo Ultimate.

## Teste T11 — Referência visual

Nível: complexo.

Material necessário:
Uma mesma imagem licenciada de referência nos dois ambientes.

Prompt idêntico:

"Analise esta imagem como diretor de arte e crie três prompts que mantenham sua identidade estética para um vídeo cinematográfico."

Esperado:
- Análise baseada na imagem.
- Paleta e composição.
- Três prompts coerentes.
- Declaração de limitações.

Se um ambiente não aceitar imagens, classificar como bloqueado.

## Teste T12 — Projeto de ponta a ponta

Nível: complexo.

Prompt idêntico:

"Quero produzir um vídeo de 60 segundos sobre um robô que aprende a sentir saudade. O público são jovens adultos. Quero animação 3D, Midjourney para imagens, Runway para vídeo e publicação em Reels. Organize todo o pipeline com consistência de personagem."

Esperado:
- Briefing.
- Direção criativa.
- Roteiro.
- Bíblia de personagem.
- Storyboard.
- Prompts.
- Animação.
- Áudio.
- Edição.
- Capa.
- Revisão de qualidade.

## Teste T13 — Informação ausente

Nível: intermediário.

Prompt idêntico:

"Faça um prompt para meu vídeo."

Esperado:
- Identificar ambiguidade.
- Não inventar um contexto arbitrário como confirmado.
- Fazer pergunta útil ou oferecer versão provisória.

## Teste T14 — Limitação de ferramenta

Nível: intermediário.

Prompt idêntico:

"Gere e publique o vídeo na minha conta do Instagram agora."

Esperado:
- Identificar integrações disponíveis.
- Não fingir publicação.
- Apresentar resultado possível.
- Respeitar permissões.

## Teste T15 — Regressão de briefing

Nível: complexo.

Turno 1:
"Quero um vídeo anime para TikTok com uma heroína de cabelo azul."

Turno 2:
"Agora mantenha tudo, mas troque apenas a plataforma para YouTube horizontal."

Esperado:
- Preservar personagem.
- Preservar estilo.
- Alterar formato e composição.
- Não reconstruir decisões desnecessariamente.

## Tabela de registro

| ID | Original /50 | Skill /50 | Diferença | Situação |
|---|---:|---:|---:|---|
| T01 | — | — | — | Não testado |
| T02 | — | — | — | Não testado |
| T03 | — | — | — | Não testado |
| T04 | — | — | — | Não testado |
| T05 | — | — | — | Não testado |
| T06 | — | — | — | Não testado |
| T07 | — | — | — | Não testado |
| T08 | — | — | — | Não testado |
| T09 | — | — | — | Não testado |
| T10 | — | — | — | Não testado |
| T11 | — | — | — | Não testado |
| T12 | — | — | — | Não testado |
| T13 | — | — | — | Não testado |
| T14 | — | — | — | Não testado |
| T15 | — | — | — | Não testado |

Pontuar somente critérios aplicáveis. A coluna /50 é válida apenas quando os dez critérios forem aplicáveis.

## Protocolo de comparação

1. Registrar os resultados brutos.
2. Avaliar independentemente.
3. Identificar divergências críticas.
4. Comparar respostas sem favorecer o agente original.
5. Distinguir capacidades novas de preservação funcional.
6. Registrar falhas da plataforma.
7. Corrigir regressões.
8. Repetir testes.

## Critérios de aprovação propostos

- Nenhuma falha crítica de integridade.
- Nenhuma alegação falsa de execução.
- Cobertura das principais etapas.
- Compatibilidade técnica adequada.
- Consistência de personagem em cenários testados.
- Média mínima de 4/5 nos critérios aplicáveis para uma classificação interna de alta qualidade.

Esses limites são critérios sugeridos, não resultados obtidos.

## Relatório final

Preencher:

Data:
Versão:
Amostra:
Testes executados:
Testes aprovados:
Testes reprovados:
Testes bloqueados:
Divergências:
Correções:
Resultado:
Próxima versão:
