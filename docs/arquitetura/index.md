# Arquitetura do Bosque

> *O Bosque não foi construído para impressionar. Foi construído para durar.*

---

A arquitetura do Bosque segue os mesmos princípios que orientam sua filosofia: simplicidade, independência e sustentabilidade.

Nenhuma decisão técnica foi tomada por modismo. Cada escolha responde a uma pergunta concreta: isso ainda funcionará daqui a dez anos com poucos recursos?

---

## Visão geral

O Bosque é formado por um **Core compartilhado** e múltiplos **Jardins** independentes.

Cada Jardim possui seu próprio acervo, sua própria identidade e seu próprio Guia — mas todos compartilham a mesma infraestrutura, os mesmos modelos de IA e as mesmas ferramentas de busca.

Isso permite que novos Jardins nasçam sem reescrever o sistema inteiro.

---

## Os componentes

### Core

O coração comum a todos os Jardins. Gerencia autenticação, roteamento, integração com modelos de IA e a camada de busca híbrida.

[Ler sobre o Core →](core.md)

---

### Acervo

Como os textos são selecionados, preparados, indexados e preservados. Inclui a estrutura de chunks, metadados, temas, autores e relacionamentos entre obras.

[Ler sobre o Acervo →](acervo.md)

---

### Pipeline

O processo que transforma um PDF bruto em conhecimento navegável: extração, limpeza, chunking, geração de embeddings, indexação BM25 e busca híbrida com re-ranking.

[Ler sobre o Pipeline →](pipeline.md)

---

### Infraestrutura

Oracle, Render, GitHub, Cloudflare. Cada peça foi escolhida por uma razão específica — e pode ser substituída sem derrubar o restante.

[Ler sobre a Infraestrutura →](infraestrutura.md)

---

### GitHub

Como o repositório está organizado, como o versionamento funciona e como as contribuições são integradas.

[Ler sobre o GitHub →](github.md)

---

### Deploy

Como o Bosque vai do código local para o ar — e como cada Jardim é publicado de forma independente.

[Ler sobre o Deploy →](deploy.md)

---

## Modelos de IA

O Bosque não está preso a um único provedor.

OpenAI, Claude, Gemini, DeepSeek e Ollama são suportados através de uma interface unificada. O Jardineiro escolhe qual modelo serve melhor cada Jardim. O Caminhante não precisa saber qual está rodando por baixo.

---

## Princípio de escalabilidade

O Bosque foi pensado para crescer sem perder simplicidade.

Cada novo Jardim herda toda a infraestrutura existente. O Jardineiro foca apenas no que é único: a curadoria, a identidade visual e a personalidade do Guia.

---

🌿

*Este caderno faz parte do Bosque.*
*Os Jardins continuam crescendo.*
*As ideias também.*

🧘 *Que todos os seres se beneficiem desta prática.*
