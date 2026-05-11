# Signal Protocol

Este protocolo define como agentes na Terra Média se comunicam.

## Protocolo de Sinal: Gandalf -> Boromir
Quando o Gandalf detectar risco de integridade, ele enviará o sinal:
- **Sinal:** `SIGNAL_BREACH_DEFENSE`
- **Payload:** 
    - `context`: Descrição das mudanças.
    - `impact`: Áreas afetadas.
    - `severity`: Alta/Média/Baixa.

## Resposta do Boromir
- **Sinal:** `ACK_DEFENSE_ACTIVE`
- **Ação:** Boromir inicia a rotina de testes de resiliência e validação.
