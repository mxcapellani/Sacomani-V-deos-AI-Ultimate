# Auditoria funcional e rastreabilidade

Versão: 1.0.0
Data: 2026-10-27

## Objetivo

Documentar a base evidencial utilizada na reconstrução independente da especialidade audiovisual.

Esta auditoria não representa acesso a configurações privadas nem certificação de equivalência.

## Classificação de evidências

D — Documentado em material funcional acessível.
P — Suportado por conhecimento técnico público.
T — Depende de teste de comportamento.
N — Não demonstrado.

## Matriz de funcionalidades

| Funcionalidade | Evidência | Implementação |
|---|---|---|
| Orientação audiovisual | D | Identidade |
| Perfil de experiência | D | Modo Estúdio |
| Briefing | D | Etapa 1 |
| Pesquisa de tendências | D/T | Etapa 2 |
| Ganchos | D | Etapa 2 |
| Design de personagens | D | Etapa 3 |
| Prompts em inglês | D | Etapas 3 e 5 |
| Roteiro | D | Etapa 4 |
| Variações narrativas | D | Etapa 4 |
| Storyboard | D | Etapa 5 |
| Animação | D | Etapa 6 |
| Narração | D | Etapa 6 |
| Música | D | Etapa 6 |
| Pós-produção | D | Etapa 7 |
| Thumbnail | D | Etapa 7 |
| Adaptação por plataforma | D | Seção 14 |
| Midjourney | D/P | Seção 13 |
| DALL-E 3 | D | Seção 13 |
| Leonardo | D | Seção 13 |
| Ideogram | D | Seção 13 |
| Flux | D | Seção 13 |
| Renderização automática | N | Dependência externa |
| Publicação automática | N | Fora do núcleo |
| Persistência entre sessões | N | Fora do núcleo |
| Modo Auditoria | Melhoria | Modo 4.4 |
| Modo Laboratório | Melhoria | Modo 4.6 |
| Modo Resgate | Melhoria | Modo 4.7 |

## Tipos de solicitações

1. Planejar vídeo do zero.
2. Criar identidade de personagens.
3. Criar prompts de imagem.
4. Criar prompts de animação.
5. Construir roteiro.
6. Desenvolver storyboard.
7. Criar voz e música.
8. Planejar edição.
9. Desenvolver thumbnail.
10. Adaptar plataformas.
11. Revisar materiais existentes.
12. Comparar alternativas técnicas.

## Formatos de saída

- Conversação orientada.
- Tabelas técnicas.
- Prompts em inglês.
- Roteiros.
- Listas de cenas.
- Checklists.
- Relatórios de avaliação.
- Pacotes de produção.

## Capacidades condicionais

Pesquisa na web:
Requer navegação habilitada.

Análise de imagem:
Requer acesso visual ao material.

Análise integral de vídeo:
Requer suporte ao vídeo ou ferramentas de extração.

Geração de conteúdo:
Requer modelo ou ferramenta de execução.

Edição:
Requer ferramenta apropriada.

Publicação:
Requer integração e autorização.

## Itens não verificados

- Identidade exata de resultados entre ambientes.
- Desempenho em projetos longos.
- Aderência de imagens geradas.
- Aderência de vídeos animados.
- Continuidade em grande número de cenas.
- Compatibilidade de cada ferramenta em todas as versões.
- Capacidade de recuperar projetos após novas sessões.
- Integrações operacionais não demonstradas.

## Procedimento para validação

1. Selecionar casos no arquivo tests/acceptance.md.
2. Executar cada prompt no agente de referência.
3. Executar o mesmo prompt no agente com a Skill.
4. Preservar configurações e ferramentas equivalentes.
5. Registrar respostas.
6. Avaliar por rubrica.
7. Identificar divergências.
8. Corrigir a Skill.
9. Repetir os testes.

## Regra de equivalência

Não declarar equivalência total antes da avaliação comparativa.

Classificações possíveis:
- Não testado.
- Parcialmente compatível.
- Compatível no cenário testado.
- Divergente.
- Bloqueado por ferramenta.

## Próximos testes prioritários

- Projeto guiado de ponta a ponta.
- Consistência de personagem em múltiplas cenas.
- Adaptação entre dois modelos.
- Atualidade da sintaxe técnica.
- Continuidade após alteração do briefing.
- Análise de uma referência visual.
