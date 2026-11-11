# 🎮 Mini Games HTML

Joguinhos feitos em HTML, CSS e JavaScript puro. Rodam direto no navegador, sem instalar nada.

🌐 **Página inicial:** https://jefersondeoliveira.github.io/mini-games-html/

## Jogos

| Jogo | Jogar | Código |
|------|-------|--------|
| 🍦 **Sorveteria Arco-Íris** | [Jogar agora](https://jefersondeoliveira.github.io/mini-games-html/sorveteria/) | [`sorveteria/`](sorveteria/) |
| 🃏 **Jogo da Memória** | [Jogar agora](https://jefersondeoliveira.github.io/mini-games-html/memoria/) | [`memoria/`](memoria/) |

### 🍦 Sorveteria Arco-Íris

Você cuida de uma sorveteria colorida e pode trocar de posto quando quiser:

- **Balcão (atendente):** lê o pedido do cliente e anota no bloquinho o recipiente, as bolas, os sabores, a cobertura e os extras.
- **Cozinha (sorveteiro):** monta o sorvete seguindo a comanda.
- O posto onde você **não** está trabalha sozinho.
- Depois de cada entrega aparece a **avaliação do cliente**, com o que acertou, o que errou e quem errou (balcão ou cozinha).
- Bata a **meta do dia** e gaste as moedas na **lojinha**: vidas, melhorias, novos sabores, caldas e extras. O progresso fica salvo no aparelho.
- Funciona no celular e pode ser **instalado** como app:
  - **Android/Chrome:** toque em "📲 Instalar".
  - **iPhone/iPad:** no Safari, toque em *Compartilhar* e depois em *Adicionar à Tela de Início*.

### 🃏 Jogo da Memória

Vire duas cartas por vez e encontre todos os pares de animais:

- **Três níveis:** Fácil (6 pares), Médio (8 pares) e Difícil (12 pares). Os animais são sorteados a cada partida.
- Conta as **jogadas** e o **tempo**, e guarda o **recorde** de cada nível no aparelho.
- Funciona no celular e no computador, com mouse, toque ou teclado (setas para andar, Enter para virar).

## Como rodar localmente

Abra o arquivo `index.html` no navegador. Para testar a instalação (PWA) é preciso um servidor local:

```bash
python3 -m http.server 8000
```

Depois acesse http://localhost:8000.

## Como adicionar um jogo novo

1. Crie uma pasta com o nome do jogo e coloque o `index.html` dele dentro.
2. Adicione um card no `index.html` da raiz e uma linha na tabela deste README.
3. Faça `git push`. O GitHub Pages publica sozinho em cerca de 1 minuto.
