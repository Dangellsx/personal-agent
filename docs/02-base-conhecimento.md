# Base de Conhecimento

## Dados Utilizados

Será utilizado o google maps para verificar possibilidades de chuva ou sol intenso e o próprio site do estabelecimento como fonte de dados para as vagas disponíveis

## Estratégia de Integração

### Como os dados são carregados?

Dante irá verificar o local onde o estabelecimento se encontra e verificar a previsão do clima do dia saber o melhor horário para ir até lá, de acordo com a agenda e quadro de horário do estabelecimento

### Como os dados são usados no prompt?

---

Serão acessados online no momento da solicitação do cliente

> Mostre um exemplo de como será uma execução do agente.

```
Cliente: Olá. Gostaria de saber qual o melhor horário disponível pra hoje na barbearia 2 irmãos.

Dante: E aí! Beleza? Vou verificar isso agora para você. Só um momento.
Dante: Para hoje (18/04/2026) a agenda está bem preenchida, mas ainda temos os seguintes horários disponíveis:
Dante:---- Horários disponíveis Barbearia 2 Irmãos ----
           11:00 - 15:45 - 17:00
Dante: Segundo o google Clima, terá chance de chuva as durante toda a manhã e continuará nublado durante a tarde.
Dante: Deseja que eu reserve qual horário ?
...
```
