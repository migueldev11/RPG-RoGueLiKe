# RPGLiKe — Rogue-style ASCII

![RPGLiKe Screenshot](https://i.imgur.com/your-image-url-here.png)


Um jogo simples de exploração de masmorras estilo *rogue-like*, desenvolvido em JavaScript puro. Explore andares gerados proceduralmente, lute contra monstros, colete ouro e aprimore seu personagem.

## Funcionalidades

- **Mundo em ASCII**: Um mapa simples e nostálgico, construído com caracteres de texto como `+`, `-`, `|`, `#`, e `.`.
- **Geração Procedural**: Cada andar da masmorra é único, com salas e corredores gerados aleatoriamente.
- **Cidade Inicial**: Comece sua aventura em uma cidade segura, onde você pode comprar itens e se preparar antes de entrar na masmorra.
- **Progressão do Personagem**: Encontre ouro para comprar melhorias de dano e poções de vida na loja.
- **Inimigos e Chefe**: Enfrente inimigos de diferentes tipos e prepare-se para o grande chefe no último andar.
- **Persistência de Dados**: Seu progresso é salvo automaticamente no navegador (usando `localStorage`), permitindo que você continue a partir de onde parou.
- **Controles Simples**: Use as teclas de seta ou os botões na tela para se mover e lutar.

## Como Jogar

O objetivo é descer o máximo de andares possível, derrotar o chefe no **Andar 5** e, em seguida, voltar para a cidade pela escada de saída (`>`).

### Controles
- **Teclas de Seta (↑ ↓ ← →)**: Mover o personagem `@`. Se você se mover em direção a um inimigo, atacará automaticamente.
- **`Espaço`** ou **Botão ⚔**: Ataca o inimigo adjacente.
- **`S`**: Interage com a loja (`T`) se você estiver em cima dela.
- **`<`**: Desce para o próximo andar.
- **`>`**: Sobe para o andar anterior. Na masmorra, leva de volta à cidade.

### Símbolos no Mapa
- `@`: Seu personagem.
- `+ - | #`: Paredes e bordas das salas.
- `.`: Chão/caminho.
- `<`: Escada para o próximo andar.
- `>`: Escada para subir (leva de volta à cidade após derrotar o chefe).
- `T`: Loja.
- `Z`, `S`: Inimigos.
- `B`: O Grande Chefe.
- `P`: Poção de cura.
- `A`: Flechas (dá ouro).
- `W`: Arma (aumenta seu dano).

## Instalação e Execução

Basta clonar este repositório e abrir o arquivo `index.html` em qualquer navegador moderno.

```bash
git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)
cd seu-repositorio
