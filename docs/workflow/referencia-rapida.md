# 📋 Referência Rápida — Imagens, Vídeos e Clones com IA

> Compilado do Workbook + Live do Marcos Lang + Google Flow
> Atualizado em: junho/2026

---

## 🧭 Índice

- [Ferramentas Principais](#ferramentas-principais)
- [Google Flow — Passo a Passo para Vídeos](#google-flow--passo-a-passo-para-vídeos)
- [Características do Google Flow](#características-do-google-flow-ao-criar-vídeos)
- [Criação de Personagens](#criação-de-personagens)
- [Multi-Shot (Vários Takes)](#multi-shot-vários-takes)
- [Clones no Google Flow](#clones-no-google-flow)
- [HeyGen — Clones de Avatar](#heygen--clones-de-avatar)
- [Cap Cut — Pós-Produção](#cap-cut--pós-produção)
- [Comparativo de Ferramentas de Vídeo](#comparativo-de-ferramentas-de-vídeo)
- [Agregadores (Magnific, Rickfield)](#agregadores-magnific-rickfield)
- [Design System](#design-system-o-dna-da-marca)
- [Logotipos](#logotipos)
- [Rebranding](#rebranding)
- [Stories](#stories)
- [Imagem com Pessoas / Ficha de Personagem](#imagem-com-pessoas--ficha-de-consistência-do-personagem)
- [Anúncio Estático](#anúncio-estático)
- [Carrossel](#carrossel)
- [Clones (Geral)](#clones-geral)

---

## Ferramentas Principais

| Ferramenta | URL | Uso |
|---|---|---|
| **Google Flow** | https://labs.google/fx/pt/tools/flow | Imagens, vídeos, clones, ferramentas |
| **ChatGPT** | https://chatgpt.com/ | Logotipos, imagens, stories, carrosséis |
| **Gemini** | https://gemini.google.com/ | Logotipos, imagens, stories |
| **Stitch (Google)** | https://stitch.withgoogle.com/ | Design System |
| **Claude Design** | https://claude.ai/design | Design System |
| **HeyGen** | https://www.heygen.com/ | Clones de avatar (melhor p/ clientes) |
| **Kling AI** | https://klingai.com/ | Vídeos de animação (mais barato) |
| **Magnific** | https://www.magnific.com/app | Agregador de IAs (antigo Freepik) |
| **Rickfield** | https://rickfield.com/ | Agregador de IAs |
| **Cap Cut** | (app) | Edição de vídeo, remoção de marcas d'água |
| **ElevenLabs** | https://elevenlabs.io/ | Troca de voz / clone de voz |

---

## Google Flow — Passo a Passo para Vídeos

### Fluxo completo para criar um vídeo de animação com personagem

#### 1. Crie um projeto
- Clique em **Novo Projeto** e dê um nome
- Dentro do projeto, você gerencia: personagens, ingredientes, vídeos

#### 2. Crie/adicione o personagem
- Vá na aba **Personagens** (lateral)
- Arraste a **Ficha de Consistência** como ingrediente
- Adicione um prompt descrevendo o personagem
- Selecione a **Voz** do personagem (masculino = male, feminino = female)
- Personalize a voz: dê um nome, descreva como deve soar
- Salve o personagem — ele vira um ingrediente reutilizável

#### 3. Crie o vídeo — passo a passo crítico

1. **Mude para modo "Elementos"** (não "Quadros" / "Frames")  
   *Elementos permite juntar personagem + cenário + ingredientes no vídeo*

2. **Defina o formato:**
   - 16:9 = horizontal (TV, celular deitado)
   - 9:16 = vertical (Reels, TikTok, Stories)
   - 1:1 = quadrado

3. **Escolha o modelo:**
   - **Omni Flash** — melhor custo-benefício atual (2 créditos a mais que o Light)
   - Nano Banana 2 — mais rápido, qualidade similar ao Pro

4. **⚠️ ERRO CRÍTICO — MARCAR O PERSONAGEM:**
   - NÃO escreva o nome do personagem no texto
   - Use **@Personagem** (arroba + nome do personagem cadastrado)
   - Ex: "**@Leão da Copa** aparece caminhando..." em vez de "O leão aparece..."

5. **⚠️ TRADUÇÃO DO PROMPT:**
   - Escreva o prompt em português
   - Traduza para inglês (Google Tradutor ou ChatGPT)
   - **MAS mantenha o DIÁLOGO/FALA em português** entre aspas
   - Senão o personagem vai falar em inglês!

6. **Defina duração:**
   - Especifique segundos por shot: "Shot 1 deve ter 4 segundos", "Shot 2 deve ter 3 segundos"
   - Máximo aproximado: 15 segundos por clipe

7. **Resolução:**
   - Gere em **720p** (mais barato)
   - Depois faça **upscale** no Magnific, Rickfield ou Cap Cut

8. **Desative o Agente (importante!):**
   - O botão do agente no Flow causa MUITOS erros (negações por policy)
   - **Deixe desativado** para evitar falsos positivos

9. **Clique em Gerar** e aguarde (10-12 min por clipe)

### Dicas de iteração
- Se não ficou bom, clique em **"Reutilizar comando"** e gere novamente
- Considere que você pode precisar de **2x os créditos** do que planejou (erros, repetições)
- Gere 1 vídeo por vez, iterando cada um

---

## Características do Google Flow ao criar vídeos

- O Flow gera vídeo com **áudio nativo** (voz do personagem já syncada)
- Às vezes a voz muda no meio do vídeo — resolva no Cap Cut
- A consistência do personagem melhora quando você marca @Personagem
- Sem marcação, o modelo reinterpreta o visual
- **Não edite dentro do Flow** — a edição integrada não funciona bem ainda
- Baixe os clipes e edite no **Cap Cut**, **DaVinci**, **Premier** ou **Edit**

---

## Criação de Personagens

### Fluxo no Google Flow
1. Crie um projeto
2. Vá em "Personagens" (lateral)
3. Arraste a **Character Consistency Sheet** como ingrediente
4. Prompt: descreva o personagem em linguagem natural
5. Selecione **voz** (teste várias)
6. Dê um **nome ao personagem**
7. Salve — ele vira um ingrediente para usar com @

### Sobre a Character Consistency Sheet
- A ficha é fundamental para manter consistência entre gerações
- Deve conter: frontal close-up, perfis, corpo inteiro frontal/traseiro
- Use fundo cinza neutro, iluminação de estúdio, expressão neutra
- Hiper-realista, sem filtros, sem efeitos
- Anexe a ficha sempre que for gerar novos vídeos do personagem

---

## Multi-Shot (Vários Takes)

### Como fazer um vídeo com múltiplas cenas

1. Crie cada shot **separadamente** no Flow
2. Use a estrutura **"Shot 1: ... / Shot 2: ... / Shot 3: ..."** no prompt
3. Defina a **duração de cada shot** (ex: "Shot 1 deve ter 4 segundos")
4. Sempre marque **@Personagem** em cada shot

### Processo prático (exemplo do Leão da Copa):
```
Shot 1 (4s): @Leão da Copa aparece caminhando no campo com a bola
Shot 2 (3s): @Leão da Copa corre com a bola nos pés
Shot 3 (5s): @Leão da Copa no centro do campo dizendo "Viu só como sou bom?"
Shot 4 (3s): Torcida comemorando (usar imagem como referência)
```

5. Após gerar todos, baixe cada clipe em 720p
6. Leve para o **Cap Cut** e monte a sequência
7. Adicione música, transições, textos

### Estratégia de custo
- Sempre gere com margem de segurança
- Se precisa de 3 clipes, prepare créditos para 6 (erros acontecem)
- 720p primeiro → upscale depois (mais barato que gerar em Full HD)

---

## Clones no Google Flow

### Como criar seu clone (avatar pessoal)

1. Na página inicial do Flow, encontre o banner: **"Seu rosto, sua voz, sua história"**
2. Clique em **Get Started** → **Comece já**
3. Um **QR Code** aparece na tela
4. Leia com o **celular**
5. No celular:
   - Permita acesso à câmera e microfone
   - **Leia números em voz alta** (para clonar a voz)
   - **Vire a cabeça** para os lados (para escanear o rosto)
   - Siga as instruções de iluminação e enquadramento
6. Quando pronto, aparece no computador: **"Use @me no comando"**

### Como usar o clone
- Crie uma imagem com **@me** no prompt (ex: "@me sentado na frente do Macbook")
- Transforme a imagem em vídeo com um prompt de ação
- Use @me + descrição + diálogo entre aspas em português
- O clone herda sua voz escaneada

### ⚠️ CUIDADOS
- Cada pessoa gera seu PRÓPRIO QR Code — não use o de outra pessoa
- O clone é pessoal (1 clone por conta Google no Flow)
- Iluminação uniforme, fundo sem ruído, olhos/boca/nariz sempre visíveis

---

## HeyGen — Clones de Avatar

### Melhor para:
- Clonar **clientes** (múltiplos avatares)
- Vídeos mais longos
- Maior qualidade de sincronia labial

### Como criar
1. Acesse https://www.heygen.com/
2. Vá em **Avatares** → **Novo Avatar**
3. Escolha: **Clonar pessoa real** (não personagem virtual)
4. **Grave via celular** (não use webcam — qualidade ruim)
5. Leia o QR Code com o celular
6. Siga o passo a passo (similar a banco: escaneamento facial)

### Texto vs Áudio — Diferença Crucial

| Método | Vantagem | Desvantagem |
|---|---|---|
| **Áudio** (gravar) | Preserva trejeitos, sotaque, emoção, movimentos de boca naturais | Mais trabalhoso (precisa gravar) |
| **Texto** (digitar) | Muito mais rápido | Perde trejeitos, entonação soa artificial |

**Recomendação:** Sempre que possível, crie clone a partir de **áudio**.

### Dicas
- A qualidade do clone depende diretamente da **qualidade do vídeo de referência**
- Dá para clonar clientes: leve o celular até eles ou tragam ao escritório
- Dá para mudar cenário do clone (fundos)
- Dá para criar avatares virtuais (personagens) além de clones reais

---

## Cap Cut — Pós-Produção

### Principais usos após gerar no Flow

1. **Montar sequência:** arraste os clipes na ordem
2. **Ajustar áudio:**
   - Para trocar vozes inconsistentes:
     * Selecione o clipe → **Áudio separado** → **Vocais**
     * Extrai só a voz do vídeo
     * Use **Mudar voz** para selecionar um novo estilo de voz
3. **Remover marca d'água:**
   - Ferramenta **Remoção de IA**
   - Selecione com o **lápis** a área da marca
   - Clique em **Remover**
4. **Adicionar música de fundo:**
   - Aba **Áudio** → **Músicas**
   - Pesquise por estilo (ex: "futebol samba")
   - Arraste para a timeline
   - Ajuste volume (ex: -8 a -11 dB para não abafar a voz)
5. **Adicionar textos, transições, efeitos**
6. **Exportar** em resolução desejada

### Alternativas de edição
- DaVinci Resolve
- Adobe Premier
- Edit (gratuito)
- Qualquer editor de vídeo serve

---

## Comparativo de Ferramentas de Vídeo

| Ferramenta | Custo | Realismo | Diálogo | Consistência |
|---|---|---|---|---|
| **Sidence 2** (via Magnific) | Mais caro | ⭐⭐⭐⭐⭐ Melhor | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ |
| **Veo 3.1** (Google Flow) | Médio | ⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐⭐ |
| **Google Omni Flash** (Flow) | Barato (2 créditos) | ⭐⭐⭐⭐ | ⭐⭐⭐ | ⭐⭐⭐ |
| **Kling AI** | Mais barato | ⭐⭐⭐ | ⭐⭐ | ⭐⭐⭐ |
| **Veo 3.0** | Médio | ⭐⭐⭐⭐ | ⭐⭐⭐ | ⭐⭐⭐ |

**Para vídeos REALISTAS com diálogo:** Sidence 2 (via Magnific)
**Para animações / menos realistas:** Google Omni ou Kling (mais baratos)
**Melhor custo-benefício atual:** Google Omni Flash

**Sobre o Veo:** Veo 3.1 é um pouco melhor que Veo 3.0

---

## Agregadores (Magnific, Rickfield)

### O que são
Plataformas que reúnem múltiplos modelos de IA em uma única assinatura.

### Magnific (antigo Freepik)
- https://www.magnific.com/app
- Modelos: GPT Image, Imagen, Nano Banana, Grok, Flux, Recraft, SD
- Também faz vídeo: Kling 3, Sidence 2.0
- Upscale de imagens e vídeos

### Rickfield
- Similar ao Magnific
- Agrega vários modelos

### Vale a pena?
- Se produz **pouco**: agregador pode valer (1 assinatura só)
- Se produz **muito**: comprar direto de cada IA é mais barato (mas vira 3+ assinaturas)
- **Uso obrigatório** quando você precisa de Sidence 2 (só via agregadores)

---

## Design System (o DNA da marca)

**Ferramentas:** Stitch (Google) + Claude Design

**Prompt básico:**
```
Meu negócio é [DESCREVA] com a marca [NOME].

Quero criar um Design System para ela, para depois a partir desse Design System,
criar um site e materiais para divulgação nas redes sociais. Em anexo, coloquei
um exemplo de uma imagem com uma coloração que acho bacana usar.
```

> 💡 Sempre adicione uma referência visual (imagem ou URL de inspiração).

---

## Logotipos

**Ferramentas:** ChatGPT, Gemini, Google Flow

**Prompt básico:**
```
Em anexo o design system da minha marca chamada [NOME].

Gere para mim 4 versões de logos estilo [ESTILO], lembrando que meu nicho é [NICHO]
```

**Estilos para testar:** Minimalista (Apple, Nike), Vintage (Levi's), Clássico (Rolex), Divertido (Nintendo), Brutalista (CAT)

**Recomendações:**
- Gere versões: fundo escuro, fundo claro, fundo transparente
- Edite iterativamente no ChatGPT ou leve ao Canva (Camadas Mágicas)

---

## Rebranding

**Prompt completo para rebranding** — veja o workbook original para o prompt completo (4 versões: Evolução direta, Minimalista premium, Criativa/diferenciada, Comercial/versátil).

**Diretrizes:** Fundo limpo, alta definição, composição centralizada, sem mockups, sem efeitos exagerados, sem 3D desnecessário.

---

## Stories

**Ferramentas:** ChatGPT, Gemini, Google Flow

**Prompt:** Gere imagem 9:16 com design system + logo anexados, teaser com frase de expectativa.

> 💡 Anexe sempre o design system + logotipo quando necessário.

---

## Imagem com Pessoas / Ficha de Consistência do Personagem

**Ferramentas:** ChatGPT, Gemini, Google Flow

**Prompt:** Character Consistency Sheet com frontal close-up, perfis, corpo inteiro. Fundo cinza neutro, estúdio, expressão neutra, hiper-realista.

> 💡 Anexe: close frontal, vistas laterais, corpo inteiro, vista traseira.
> Use como referência permanente para todas as gerações futuras.

---

## Anúncio Estático

**Estrutura:** OBJETIVO, PRODUTO, PÚBLICO, CONCEITO, HEADLINE, SUBHEADLINE, CTA, DIREÇÃO DE ARTE, ELEMENTOS VISUAIS, COMPOSIÇÃO, IDENTIDADE VISUAL, FORMATO.

---

## Carrossel

**Ferramentas:** ChatGPT, Gemini, Google Flow

**Abordagem:** Gere slide a slide, iterando cada um. Não tente gerar tudo de uma vez.

---

## Clones (Geral)

| Ferramenta | Melhor para | Custo |
|---|---|---|
| **Google Flow** | Clone pessoal (1 por conta) | Incluso nos créditos |
| **HeyGen** | Clones de clientes, múltiplos avatares | Plano separado |
| **ElevenLabs** | Clone de voz + trocador de voz | Plano separado |

**Dicas finais:**
1. Qualidade do vídeo de referência = qualidade do clone
2. Áudio de referência > Texto (preserva trejeitos e sotaque)
3. Para cliente: HeyGen (leve o celular até eles)
4. Use @me no Flow / @ no HeyGen para chamar seu clone

---

*Documento de referência rápida para consulta e atualizações.*
*Fontes: Workbook Marcos Lang + Live Workshop (junho/2026) + Google Labs docs.*
