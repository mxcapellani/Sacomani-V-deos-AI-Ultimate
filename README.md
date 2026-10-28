# Sacomani — Vídeos AI Ultimate

Uma Agent Skill especializada em direção criativa e produção profissional de vídeos com inteligência artificial.

**Versão:** 1.0.0  
**Idioma:** Português brasileiro  
**Licença:** MIT  
**Padrão:** Agent Skills

## Visão geral

Sacomani — Vídeos AI Ultimate transforma conceitos em planos audiovisuais estruturados, desde a definição da ideia até o roteiro, storyboard, prompts generativos, animação, áudio, edição e capa.

É uma Skill baseada em instruções e conhecimento especializado. Não depende de API proprietária para executar seu núcleo.

A geração efetiva de mídia depende das ferramentas disponíveis no ambiente hospedeiro.

## Funcionalidades

### Planejamento
- Briefing criativo.
- Definição de público e plataforma.
- Estilo audiovisual.
- Pesquisa de tendências, quando disponível.
- Criação de ganchos.

### Pré-produção
- Design de personagens.
- Bíblia de continuidade.
- Prompts de imagem.
- Direção de arte.
- Roteiros e variações.

### Produção
- Storyboard.
- Prompts de animação.
- Linguagem cinematográfica.
- Planejamento de movimentos.
- Direção de voz e música.

### Pós-produção
- Plano de montagem.
- Legendas.
- Tratamento de áudio.
- Capas e thumbnails.
- Checklist de exportação.

### Avaliação
- Auditoria de prompts.
- Comparação de soluções.
- Identificação de erros.
- Revisão de continuidade.
- Adaptação entre plataformas.

## Funcionalidades preservadas

A reconstrução mantém as funções documentadas do agente audiovisual de referência:
- Experiência adaptada ao usuário.
- Planejamento guiado.
- Briefing por etapas.
- Pesquisa de referências.
- Criação de personagens.
- Desenvolvimento narrativo.
- Storyboard técnico.
- Animação e áudio.
- Pós-produção.
- Prompts especializados por modelo.

Não se afirma equivalência total sem validação comparativa.

## Melhorias Ultimate

- Modo Direto para pedidos pontuais.
- Produção Completa com premissas explícitas.
- Modo Auditoria.
- Modo Adaptação.
- Modo Laboratório.
- Modo Resgate de cenas problemáticas.
- Bíblia de continuidade.
- Controle de compatibilidade por versão.
- Revisão sistemática.
- Matriz de testes.
- Declaração de dependências.

## Estrutura

```text
.agents/skills/sacomani-videos-ai-ultimate/
    SKILL.md
    references/
        technical-guide.md
        functional-audit.md
    examples/
        complete-project.md

tests/
    acceptance.md

README.md
LICENSE
CHANGELOG.md
.gitignore
```

## Instalação

### Instalação em um projeto

Clone o repositório na raiz do projeto:

```bash
git clone https://github.com/SEU-USUARIO/sacomani-videos-ai-ultimate.git
```

Copie a pasta da Skill para o projeto desejado:

```bash
mkdir -p .agents/skills

cp -R \
  sacomani-videos-ai-ultimate/.agents/skills/sacomani-videos-ai-ultimate \
  .agents/skills/
```

Em Windows, realize a cópia equivalente pelo gerenciador de arquivos ou PowerShell.

### Instalação manual

Copie:

```text
.agents/skills/sacomani-videos-ai-ultimate/
```

para um diretório de descoberta de Skills suportado pelo seu agente.

O mecanismo de ativação depende do hospedeiro. Alguns agentes exigem selecionar ou mencionar explicitamente a Skill.

## Utilização

Exemplo de solicitação:

"Use a Skill Sacomani para criar um vídeo cinematográfico de 30 segundos sobre um astronauta perdido, para TikTok, com imagens no Midjourney e animação no Kling."

### Modo Estúdio

"Quero começar um projeto guiado do zero."

### Modo Direto

"Crie um prompt para animar esta cena no Runway."

### Modo Auditoria

"Analise este roteiro e identifique falhas de retenção."

### Modo Adaptação

"Converta este roteiro horizontal para Reels."

### Modo Produção Completa

"Crie autonomamente o pacote completo de produção de um vídeo de 45 segundos."

## Dependências e permissões

### Núcleo obrigatório

- Agente de IA com suporte ao carregamento de Agent Skills.
- Capacidade de interpretar Markdown e seguir instruções.

### Capacidades opcionais

- Acesso à web para pesquisa.
- Leitura multimodal para referências.
- Ferramentas de geração de imagem.
- Ferramentas de geração de vídeo.
- Ferramentas de áudio.
- Manipulação de arquivos.
- Execução de scripts.

Nenhuma credencial deve ser armazenada no repositório.

## Como testar

Abra `tests/acceptance.md`.

Execute os mesmos prompts no agente de referência e no agente com esta Skill.

Avalie:
- Cobertura.
- Precisão.
- Qualidade.
- Consistência.
- Formato.
- Especialidade.
- Autonomia.
- Referências.
- Utilidade.
- Recursos avançados.

Registre resultados independentemente.

### Validação estrutural

Quando a ferramenta de referência Agent Skills estiver instalada:

```bash
skills-ref validate \
  .agents/skills/sacomani-videos-ai-ultimate
```

Consulte a documentação oficial caso o comando ou a forma de instalação tenham sido atualizados.

## Limitações

- Não gera vídeo automaticamente sem integração externa.
- Não substitui uma suíte de edição.
- Não garante resultados idênticos em modelos diferentes.
- Não garante desempenho de audiência.
- Não possui acesso automático às contas do usuário.
- Não garante persistência entre conversas.
- Requer atualização periódica de compatibilidade das IAs.
- A equivalência com o agente de referência ainda depende dos testes documentados.

## Atualização

1. Verifique mudanças nas ferramentas generativas.
2. Atualize `technical-guide.md`.
3. Atualize regras relevantes de `SKILL.md`.
4. Execute os testes de regressão.
5. Atualize `CHANGELOG.md`.
6. Incremente a versão.
7. Crie uma release no GitHub.

Use versionamento semântico:
- MAJOR: mudanças incompatíveis.
- MINOR: novas funcionalidades compatíveis.
- PATCH: correções.

## Publicação

Consulte as instruções de GitHub fornecidas na documentação de entrega.

O repositório não deve incluir imagens privadas, arquivos sem licença, tokens ou chaves de API.

## Referências

- https://agentskills.io/specification
- https://github.com/agentskills/agentskills
- https://docs.midjourney.com/

## Licença

MIT. Consulte LICENSE.

Não implica afiliação oficial com provedores de modelos de IA.
