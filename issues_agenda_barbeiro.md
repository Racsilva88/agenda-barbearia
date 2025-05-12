# Ações corretivas e melhorias futuras

## Issue 1 – Substituir campo de horário livre por opções fixas
**Descrição:** O campo atual permite digitação livre de horários, o que pode causar conflitos. Deve-se usar uma lista de horários fixos (ex: 13h00, 14h00, 15h00) com um `<select>` para padronizar os agendamentos.  
**Tipo:** Melhoria  
**Prioridade:** Alta

## Issue 2 – Verificar horários já agendados (futuro com backend)
**Descrição:** Criar lógica que consulte o banco de dados para verificar se o horário já foi reservado antes de aceitar novo agendamento.  
**Tipo:** Melhoria futura  
**Prioridade:** Média

## Issue 3 – Mensagem para usuários sem JavaScript
**Descrição:** Adicionar um bloco `<noscript>` com uma mensagem informando que o site requer JavaScript para funcionar corretamente.  
**Tipo:** Acessibilidade  
**Prioridade:** Baixa

## Issue 4 – Acessibilidade para leitores de tela
**Descrição:** Incluir `aria-labels`, testar contraste de cores, e validar acessibilidade usando ferramentas como WAVE ou Lighthouse.  
**Tipo:** Melhoria de usabilidade  
**Prioridade:** Média