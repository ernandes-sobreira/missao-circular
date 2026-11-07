# ♻️ Missão Circular

**Suas decisões transformam a cidade.** Um jogo educativo de escolhas sobre consumo consciente, redução de resíduos e economia circular.

[**🎮 Jogar Missão Circular**](https://ernandes-sobreira.github.io/missao-circular/) · [Código-fonte](https://github.com/ernandes-sobreira/missao-circular)

## Como jogar

1. Selecione **Básico**, **Intermediário**, **Difícil** ou **Carbonauta**.
2. Leia o cenário apresentado e escolha uma das três decisões.
3. Observe as consequências: **boas escolhas melhoram o índice ambiental**, escolhas intermediárias o mantêm e escolhas inadequadas o reduzem.
4. Acompanhe a cidade animada: árvores, cores e atmosfera respondem ao estado do ecossistema.
5. Ao terminar, confira sua pontuação e, se desejar, salve o resultado no ranking.

A cidade começa com **50 pontos**. O valor é um **indicador didático**, não um índice ambiental real medido em campo. As decisões têm pesos por nível; a pontuação final vai de 0 a 100. Em caso de empate no ranking, o menor tempo decide.

## Experiência

- Ilustrações vetoriais diferentes para cada uma das 42 situações nos quatro níveis, representando mercados, reparo, coleta seletiva, recursos naturais, indicadores e fluxos de materiais.
- A ilustração acompanha o assunto da pergunta, enquanto o índice ambiental acompanha o resultado acumulado das decisões. Não há casas representadas em APP nem paisagem urbana de grandes prédios.
- Feedback educacional imediato e mensagens que traduzem consequências das decisões.
- Quatro dificuldades com situações diferentes.
- Cronômetro, progresso, indicador de saúde do ecossistema e contagem de escolhas.
- Ranking online com Firebase Cloud Firestore, separado por dificuldade.
- Layout responsivo para computador e celular.
- Respeito à configuração de redução de movimento do navegador.

## Uso educacional

Adequado para aulas de Ciências, Biologia, Geografia, Ecologia, educação ambiental e sustentabilidade. O jogo pode abrir discussões sobre prevenção de resíduos, reparabilidade, consumo responsável, logística reversa e justiça socioambiental. As alternativas são simplificações didáticas e podem ser exploradas criticamente em sala.

## Executar e publicar

O jogo utiliza um único arquivo **`index.html`** com HTML, CSS e JavaScript. O quiz funciona localmente, mas o ranking requer acesso à internet e regras adequadas do projeto Firebase. O fluxo em `.github/workflows/pages.yml` publica a branch `main` pelo GitHub Pages; nas configurações do repositório, escolha **Settings → Pages → Source: GitHub Actions**, se necessário.

## Idealização

**ERNANDES SOBREIRA**

## Licenciamento

O repositório ainda não contém uma licença de código aberta específica. Solicite autorização do autor para reutilização do código fora dos usos explicitamente permitidos pela plataforma.

---

*Jogar é explorar escolhas. Aprender é entender suas consequências.*
