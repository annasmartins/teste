# Casos de Teste - Urban Routes

## CT-01 - Inserção de endereço de origem e destino
**Objetivo:** Validar o preenchimento dos campos de origem e destino.  
**Pré-condição:** Aplicação aberta no navegador.  
**Passos:**
1. Inserir um endereço válido no campo "De"
2. Inserir um endereço válido no campo "Para"
3. Enviar as informações

**Resultado esperado:** O sistema deve receber os pontos A e B e apresentar as opções de rota disponíveis.

---

## CT-02 - Exibição dos tipos de transporte
**Objetivo:** Validar a exibição dos tipos de transporte disponíveis.  
**Pré-condição:** Origem e destino preenchidos corretamente.  
**Passos:**
1. Informar origem e destino
2. Observar os ícones de transporte disponíveis

**Resultado esperado:** O sistema deve exibir corretamente as opções de transporte disponíveis, como caminhada, táxi, bicicleta, scooter e carro.

---

## CT-03 - Cálculo de tempo e custo da viagem
**Objetivo:** Validar se o sistema calcula tempo e custo da rota.  
**Pré-condição:** Origem e destino válidos informados.  
**Passos:**
1. Inserir os endereços
2. Selecionar um tipo de transporte
3. Verificar as informações apresentadas

**Resultado esperado:** O sistema deve exibir o tempo estimado e o custo da viagem conforme o tipo de transporte selecionado.

---

## CT-04 - Alteração do tipo de transporte
**Objetivo:** Validar atualização das informações ao trocar o tipo de transporte.  
**Pré-condição:** Origem e destino já preenchidos.  
**Passos:**
1. Selecionar um tipo de transporte
2. Anotar tempo e custo exibidos
3. Trocar para outro tipo de transporte

**Resultado esperado:** O sistema deve atualizar corretamente o tempo e o custo conforme o novo transporte selecionado.

---

## CT-05 - Validação geral da interface
**Objetivo:** Verificar se os elementos da interface são exibidos corretamente.  
**Pré-condição:** Aplicação carregada.  
**Passos:**
1. Abrir a aplicação
2. Verificar campos, botões, modos e ícones

**Resultado esperado:** Todos os elementos da interface devem estar visíveis, legíveis e funcionando corretamente.
