# Dicas de Debug no Playwright

No Playwright, você pode depurar seus testes de forma simples e eficiente. Este tutorial apresenta três opções para rodar um teste específico em modo debug, otimizando seu fluxo de trabalho e tornando o processo mais ágil e produtivo.

## Opção 1: Rodar um teste específico com `--debug`

Para depurar um arquivo de teste específico, utilize o comando `npx playwright test` seguido do caminho do arquivo e a flag `--debug`. Isso abrirá o inspector do Playwright e pausará a execução passo a passo, permitindo uma análise detalhada.

```bash
npx playwright test caminho/do/arquivo.spec.ts --debug
```

## Opção 2: Rodar apenas um teste pelo nome

Se você deseja depurar um teste específico com base em seu nome, pode usar a flag `-g` (grep) juntamente com o nome do teste e a flag `--debug`. Esta opção é útil quando você tem múltiplos testes em um mesmo arquivo e quer focar em um deles.

```bash
npx playwright test -g "nome do teste" --debug
```

**Exemplo:**

```bash
npx playwright test -g "deve fazer login" --debug
```

## Opção 3: Marcar apenas um teste com `.only`

Para uma depuração rápida e focada, você pode marcar um teste diretamente no código com `.only`. O Playwright executará apenas esse teste, ignorando todos os outros. Esta é uma ótima opção para isolar e depurar rapidamente um cenário específico.

**No código:**

```typescript
test.only("deve fazer login", async ({ page }) => {
  // Seu código de teste aqui
});
```

Com essas opções, você pode otimizar seu fluxo de trabalho de depuração no Playwright, tornando o processo mais ágil e produtivo.
