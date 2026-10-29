# Regras do projeto

O SharpIt existe para a gente **aprender** como o Git funciona por dentro. Por isso, todo código deste repositório deve ser escrito pelas próprias mãos de quem contribui.

## Uso de IA

**Não é permitido:**
- Pedir para uma IA (ChatGPT, Claude, Copilot, etc.) escrever funções, classes, comandos ou arquivos do projeto
- Usar autocompletar de IA que gere blocos inteiros de código (desativem o Copilot e similares neste repositório)
- Colar código gerado por IA e só ajustar os nomes

**É permitido, como se fosse consultar a documentação:**
- Perguntar como funciona um conceito (o que é um objeto tree, como o zlib comprime, como o SHA-1 é calculado)
- Pedir um **pequeno exemplo** de como usar uma API do .NET (`ZLibStream`, `SHA1`, `File.ReadAllBytes`...), do mesmo jeito que você copiaria um trecho da documentação da Microsoft ou do Stack Overflow
- Pedir ajuda para entender uma mensagem de erro
- Pedir revisão ou explicação de um código que **você** escreveu

**A regra prática:** se o trecho resolve um pedaço da lógica do SharpIt, você escreve. Se é só um exemplo de como usar uma ferramenta, pode consultar, desde que entenda cada linha antes de usar.

## Na dúvida

Se não souber se algo pode, pergunte para o outro antes de commitar. E se usar um exemplo consultado, deixe um comentário curto indicando a fonte.

## Fluxo de trabalho

- Nada vai direto na `main`: cada tarefa ganha uma branch e entra por pull request
- O outro integrante revisa o PR antes do merge
- Cada um deve conseguir explicar qualquer código que enviou
