# AURORA Calculadora Farmacêutica — Repositório oficial Android

Repositório atual: https://github.com/fabriciomatosqa/AURORA-CALCULADORAFARMACEUTICA-ANDROID

Backup do projeto original: https://github.com/fabriciomatosqa/Aurora-calculadorafarmaceutica

Versão inicial do projeto migrado: 0.0.1+1.

O código Flutter, módulos de prescrições, calculadoras, testes, scripts, GitHub Actions e documentação foram transferidos. Os links do atualizador foram direcionados ao novo repositório.

Para habilitar as atualizações no celular, é obrigatório configurar neste novo repositório os quatro Secrets de assinatura Android: AURORA_KEYSTORE_BASE64, AURORA_KEYSTORE_PASSWORD, AURORA_KEY_ALIAS e AURORA_KEY_PASSWORD. O workflow não publica APK Release sem eles.

Use uma chave compatível com a assinatura do aplicativo já instalado. Uma chave nova pode exigir migração/reinstalação inicial, com backup prévio dos dados. Nunca publique a chave privada no repositório.

## Primeiro APK independente

A versão 0.0.1 é um novo aplicativo Android com identificador `br.com.aurora.calculadorafarmaceutica`. Ela poderá ser instalada ao lado da versão de testes antiga, sem apagá-la. Os dados locais do aplicativo antigo não são importados automaticamente; conserve-o como backup. Depois de instalar o primeiro APK Release assinado, as versões seguintes usam o mesmo identificador e a mesma chave para atualizar diretamente no app.
