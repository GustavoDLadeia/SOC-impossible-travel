# Login suspeito (impossible travel)

Cenário de possível login suspeito identificado por padrão de impossible travel, com acessos consecutivos do mesmo usuário em países distintos em curto intervalo de tempo. A discrepância geográfica sem uso de VPN autorizada indica forte indício de comprometimento de credenciais.

## Resumo

Foram identificados logins consecutivos do mesmo usuário a partir de localizações  
geográficas distintas em curto intervalo de tempo, indicando possível comprometimento  
de conta.

## Evidências

- Usuário: `ana.ferreira`
- Login 1: Brasil — `10:15 AM`
- Login 2: Alemanha — `10:22 AM`
- Intervalo entre logins: 7 minutos
- Ausência de VPN autorizada

## Análise

O curto intervalo entre logins em localidades geograficamente distantes caracteriza um  
padrão típico de "impossible travel", incompatível com deslocamento físico.

A ausência de registro de VPN autorizada reduz a probabilidade de atividade legítima.  
No entanto, não se pode descartar completamente o uso de VPN não autorizada ou proxy.

Esse tipo de comportamento é frequentemente associado ao uso indevido de credenciais  
comprometidas por terceiros.

Não há evidência, no contexto analisado, que justifique atividade legítima para esse  
padrão de acesso.

- Severidade: Alta
- Confiança: Alta

## Conclusão

Atividade altamente suspeita compatível com comprometimento de conta.

## Ação

- Forçar redefinição de senha do usuário
- Revogar sessões ativas
- Validar com o usuário se houve acesso legítimo
- Verificar origem dos IPs envolvidos
- Monitorar novos logins suspeitos
- Escalar para N2 caso comportamento persista
