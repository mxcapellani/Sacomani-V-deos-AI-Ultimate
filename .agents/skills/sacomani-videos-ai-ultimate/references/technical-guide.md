# Guia técnico audiovisual

Versão: 1.0.0

Este guia complementa o SKILL.md. Não substitui documentação oficial dos fornecedores.

## 1. Construção de prompts de imagem

Modelo conceitual:

SUBJECT + IDENTITY + ACTION + ENVIRONMENT + COMPOSITION + CAMERA + LIGHTING + STYLE + CONSTRAINTS

Exemplo:

"A courageous young astronaut with short black hair and a scratched white spacesuit, standing on a deserted red planet, wide cinematic shot, dramatic backlighting, windblown dust, realistic science fiction cinematography, strong foreground-background separation."

## 2. Construção de prompts de vídeo

Modelo:

STARTING FRAME + SUBJECT ACTION + SECONDARY MOTION + CAMERA MOVEMENT + ENVIRONMENT + CONTINUITY + END STATE

Exemplo:

"Starting from the reference image, the astronaut slowly turns toward a distant glowing structure. Fine dust moves across the foreground. The camera performs a gentle push-in. Preserve the character's face, spacesuit, helmet design and lighting direction. End with the astronaut staring at the structure."

Evite movimentos contraditórios.

Um prompt de vídeo não deve depender de acontecimentos invisíveis ao modelo.

## 3. Consistência visual

### Bíblia de personagens

Registre:

| Atributo | Exemplo |
|---|---|
| ID | ASTRONAUT_01 |
| Cabelo | Short black hair |
| Rosto | Oval face |
| Roupa | Weathered white spacesuit |
| Acessório | Orange shoulder patch |
| Identidade | Constant across all scenes |
| Estilo | Realistic cinematic science fiction |

### Regras

- Mantenha os atributos permanentes.
- Reutilize referências aprovadas.
- Separe identidade de pose.
- Separe identidade de ambiente.
- Não transforme a roupa sem motivação.
- Não altere aparência entre cenas sem decisão narrativa.

## 4. Continuidade espacial

Registre:
- Direção do olhar.
- Posicionamento de objetos.
- Direção da luz.
- Eixo de ação.
- Horário.
- Clima.
- Estado do figurino.
- Resultado da cena anterior.

Verifique cenas adjacentes antes de renderizar.

## 5. Modelos de imagem

### Midjourney

Prompts combinam descrição natural e parâmetros suportados.

Exemplo V7:

"Lonely astronaut walking across red dunes, atmospheric cinematic lighting, wide shot --ar 16:9 --v 7"

Para V7, --oref aceita referência válida em URL.

Para V6/6.1, --cref é uma possibilidade de referência de personagem.

Não trate --cref como equivalente universal a --oref.

Em V8.x, verificar Edit Model e suporte atual de referências.

Não presumir recursos de uma versão em outra.

### DALL-E 3

Exemplo:

"Create a cinematic vertical composition showing a lonely astronaut crossing a red desert at sunset. Use dramatic natural lighting, detailed atmospheric depth and realistic cinematic science fiction art direction. The frame should be suitable for a 9:16 mobile video."

Não anexar --ar.

### Leonardo

Priorizar:
- Sujeito.
- Textura.
- Direção artística.
- Composição.
- Configuração opcional de recursos na interface.

### Ideogram

Priorizar:
- Hierarquia visual.
- Legibilidade.
- Texto curto.
- Composição tipográfica.

### Flux

Priorizar descrição explícita e semanticamente ordenada.

Versões e implementações podem ter capacidades diferentes.

## 6. Modelos de vídeo

As orientações seguintes descrevem estratégias de prompting, não garantias de recursos nativos.

### Veo

Descrever:
- Cena.
- Ação.
- Cinematografia.
- Ambiente.
- Áudio, quando suportado.
- Continuidade.

Verificar versão e funções ativas.

### Runway

Dar atenção a:
- Estado inicial.
- Movimento principal.
- Direção de câmera.
- Identidade da referência.
- Complexidade temporal.

### Kling

Definir:
- Sujeito.
- Movimento.
- Interação.
- Câmera.
- Continuidade.
- Estado final.

### Pika

Priorizar:
- Ação delimitada.
- Efeito pretendido.
- Movimento legível.
- Composição estável.

### Nano Banana

Tratar como tecnologia de imagem ou edição quando aplicável à versão utilizada.

Não presumir que qualquer implementação chamada Nano Banana seja um gerador de vídeo independente.

Confirmar ferramenta efetiva antes de planejar a animação.

## 7. Voz e música

Ferramentas exemplificativas:
- ElevenLabs.
- Play.ht.
- Suno.
- Udio.

Verifique capacidade, disponibilidade, planos e termos atuais.

### Prompt de voz

"Warm Brazilian Portuguese narration, intimate documentary delivery, moderate pace, restrained excitement, clear articulation, natural pauses."

### Prompt de música

"Original cinematic ambient score, slow evolving synthesizer pads, subtle low percussion, emotional sense of wonder, instrumental, no vocals, gradual rise toward the ending."

## 8. Linguagem de câmera

- Wide shot: plano aberto.
- Medium shot: plano médio.
- Close-up: plano fechado.
- Extreme close-up: detalhe.
- Dolly-in: aproximação física.
- Push-in: aproximação progressiva.
- Pan: rotação horizontal.
- Tilt: rotação vertical.
- Tracking: acompanhamento.
- Orbit: trajetória orbital.
- Static: câmera fixa.

Não confundir movimento da câmera com movimento do personagem.

## 9. Plataformas

### YouTube horizontal
Proporção de partida: 16:9.

### TikTok
Proporção de partida: 9:16.

### Instagram Reels
Proporção de partida: 9:16.

### YouTube Shorts
Proporção de partida: 9:16.

A duração e os requisitos técnicos mudam. Verificar documentação atual quando necessário.

Não posicionar textos importantes em regiões cobertas pela interface.

## 10. Estimativa temporal

Para narração:

Duração aproximada em segundos =
(número de palavras / palavras por minuto) * 60.

Exemplo:
75 palavras / 150 palavras por minuto = 30 segundos.

Essa estimativa não inclui necessariamente pausas, respiração ou efeitos.

Para o storyboard:

Soma das durações planejadas das cenas =
duração estimada do vídeo.

Em caso de diferença, redistribuir cenas antes de produzir.

## 11. Checklist de um prompt profissional

- Sujeito explícito.
- Identidade consistente.
- Ação principal clara.
- Ambiente definido.
- Enquadramento.
- Luz.
- Estilo.
- Proporção.
- Ferramenta compatível.
- Ausência de contradições.
- Ausência de parâmetros inventados.

## 12. Prompt negativo

Use negative prompt separado somente quando a interface suportar esse recurso.

Não assuma sintaxe universal.

Exemplo conceitual:
"unwanted extra limbs, identity drift, costume changes, distorted hands, flickering textures"

Não apresente o exemplo como garantia de correção.

## 13. Avaliação de qualidade

Critérios de 0 a 5:
- Clareza.
- Fidelidade ao objetivo.
- Continuidade.
- Compatibilidade.
- Qualidade cinematográfica.
- Viabilidade.
- Adequação à plataforma.

Recomende revisão quando qualquer critério crítico estiver abaixo de 3.

## 14. Referências oficiais

- https://agentskills.io/specification
- https://docs.midjourney.com/
- https://help.runwayml.com/
- https://deepmind.google/models/veo/

Consultar documentação dos demais fornecedores quando houver necessidade de verificação específica.

Última revisão documental inicial: 2026-10-27.
