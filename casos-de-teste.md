# Casos de Teste

## CT01 - Preencher e enviar formulário

**Passos:**
1. Preencher o nome com `Gabriel`.
2. Preencher a senha com `147258Gt`.
3. Preencher o e-mail com `gabriel.teste@email.com`.
4. Digitar `Teste de formulário` na mensagem.
5. Clicar em Submit.

**Esperado:** o formulário deve ser enviado.

**Resultado:** formulário enviado e mensagem de confirmação exibida.

**Status:** `PASS`

---

## CT02 - Enviar sem preencher o nome

**Passos:**
1. Deixar o campo Name vazio.
2. Preencher os outros campos.
3. Clicar em Submit.

**Esperado:** o formulário não deve ser enviado sem o nome.

**Resultado:** o campo Name foi indicado como obrigatório e o envio foi bloqueado.

**Status:** `PASS`

---

## CT03 - Marcar bebida favorita

**Passos:**
1. Marcar a opção Coffee.

**Esperado:** a opção Coffee deve ficar marcada.

**Resultado:** a opção Coffee ficou marcada.

**Status:** `PASS`

---

## CT04 - Escolher cor favorita

**Passos:**
1. Selecionar a opção Blue.

**Esperado:** a opção Blue deve ficar selecionada.

**Resultado:** a opção Blue ficou selecionada.

**Status:** `PASS`

---

## CT05 - Selecionar opção de automação

**Passos:**
1. Abrir o campo `Do you like automation?`.
2. Escolher uma opção.

**Esperado:** a opção escolhida deve aparecer selecionada.

**Resultado:** a opção escolhida ficou selecionada corretamente.

**Status:** `PASS`
