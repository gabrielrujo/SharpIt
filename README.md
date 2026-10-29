# SharpIt

Uma reimplementação do Git do zero, em C#, feita para entender como o controle de versão funciona por dentro.

O SharpIt grava os repositórios no mesmo formato do Git oficial (objetos blob, tree e commit com hash SHA-1 e compressão zlib), então tudo que ele cria pode ser lido e conferido com o próprio `git`.

## Comandos planejados

- [ ] `init`
- [ ] `hash-object` / `cat-file`
- [ ] `write-tree` / `ls-tree`
- [ ] `commit`
- [ ] `log`
- [ ] `add`
- [ ] `branch` / `checkout`
- [ ] `status` / `diff`

## Estrutura

```
src/SharpIt.Core     lógica do Git (objetos, armazenamento, refs, índice)
src/SharpIt.Cli      linha de comando, um arquivo por comando
tests/SharpIt.Tests  testes automatizados
docs/                anotações sobre o formato interno do Git
```

## Regras

Este é um projeto de aprendizado: o código é escrito por nós, sem geração por IA. Veja as regras completas em [CONTRIBUTING.md](CONTRIBUTING.md).

## Tecnologias

C# · .NET
