# 🎮 Mini Games HTML

Joguinhos feitos em HTML, CSS e JavaScript puro. Rodam direto no navegador, sem instalar nada.

🌐 **Página inicial:** https://jefersondeoliveira.github.io/mini-games-html/

## Jogos

| Jogo | Jogar | Código |
|------|-------|--------|
| 🍦 **Sorveteria Arco-Íris** | [Jogar agora](https://jefersondeoliveira.github.io/mini-games-html/sorveteria/) | [`sorveteria/`](sorveteria/) |
| 🃏 **Jogo da Memória** | [Jogar agora](https://jefersondeoliveira.github.io/mini-games-html/memoria/) | [`memoria/`](memoria/) |
| 🧪 **LabRemember** | [Jogar agora](https://jefersondeoliveira.github.io/mini-games-html/labremember/) | [`labremember/`](labremember/) |
| 👁️ **Treino de Lash** | [Jogar agora](https://jefersondeoliveira.github.io/mini-games-html/lash/) | [`lash/`](lash/) |
| 💖 **Lash Studio** | [Jogar agora](https://jefersondeoliveira.github.io/mini-games-html/lash-studio/) | [`lash-studio/`](lash-studio/) |

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

### 🧪 LabRemember

Um jogo para decorar as regras de cada laboratório. Você mesmo cadastra as regras e treina com elas:

- **Cadastro:** crie os laboratórios e, em cada um, os itens com **mínimo**, **máximo**, **margem** e unidade. Exemplo: Lab 1, Crioscopia, máximo 500 com margem 2 (até 502 ainda é OK).
- **Rodadas de 10 perguntas**, de todos os laboratórios ou de um só, misturando dois tipos:
  - **Julgar:** aparece um valor perto do limite e você responde OK ou Erro.
  - **Limite:** qual é o mínimo ou o máximo daquele item, entre 4 alternativas.
- As regras que você mais erra aparecem mais vezes.
- Tudo fica salvo **só no navegador** do aparelho. Use **Exportar backup** e **Importar backup** para guardar uma cópia ou levar as regras para outro aparelho.

### 👁️ Treino de Lash

Um quiz para treinar as decisões do atendimento de extensão de cílios:

- **Atender ou não?** A cliente conta uma situação (conjuntivite, alergia à cola, lentes de contato, gestação e outras) e você decide se atende, atende com um cuidado extra ou não atende hoje.
- **Produto certo:** qual produto usar em cada momento do procedimento.
- **Ordem certa:** monte a sequência dos passos.
- São **15 perguntas sorteadas** por rodada. O jogo só mostra o que está certo ou errado **no fim**, com a explicação de cada resposta.
- Feito para o **celular deitado**. As perguntas ficam nos blocos `CASOS`, `PRODUTOS` e `ORDENS`, no topo do código.

### 💖 Lash Studio

Um simulador do atendimento de extensão de cílios, sem roteiro:

- A cada cliente o olho chega de um jeito, sorteado: **limpo**, **com maquiagem**, **com extensões antigas para tirar**, **para manutenção** ou **irritado** (caso em que o certo é remarcar).
- O olho ocupa a **tela inteira** e o botão **Ferramentas** abre a bancada, com 18 itens, inclusive os que não devem ser usados. Você pega a ferramenta e usa no olho: demaquilar, lavar, secar, remover, isolar com pad e fita e passar primer.
- Para colar, toque no fio natural para isolar (a tela aproxima), segure na **pedra de jade** para molhar a extensão e toque na marca verde do fio.
- Ao **entregar o espelho**, a cliente avalia de 1 a 5 estrelas: paga o valor cheio com gorjeta se ficou perfeito, paga menos ou reclama dizendo o que deu errado.
- O **caixa do dia** soma os atendimentos e o recorde fica salvo no aparelho.
- Feito para o **celular deitado**, com botão de tela cheia. Os mapas de cada efeito e os preços ficam nos blocos `ESTILOS` e `PRECO`, no topo do código.

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
