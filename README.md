# Portfólio de projetos

João Pedro dos Anjos · Analista de Dados na Softplan

Projetos autorais que exploram problemas concretos em dados, automação e desenvolvimento de software. Os projetos abaixo são apresentados como estudos de caso; **os repositórios de código-fonte são privados**. Apenas os serviços identificados como demonstrações têm acesso público.

## Dados e produtos

### ExtratoFácil
Converte extratos bancários em PDF ou foto para Excel, CSV e OFX.

- **Problema:** transformar extratos de formatos variados em lançamentos utilizáveis, sem perder a conferência dos valores.
- **Abordagem:** tenta primeiro extrair o texto do PDF; recorre à IA quando a extração não é suficiente ou quando o documento é uma imagem. Valida os lançamentos pela equação de saldo: saldo anterior + entradas − saídas = saldo final.
- **Demonstração:** [extratofacil.duckdns.org](https://extratofacil.duckdns.org)

### Radar Imobiliário de Blumenau
Reúne anúncios de apartamentos à venda e para aluguel no entorno do Hospital Santa Isabel.

- **Problema:** comparar anúncios dispersos e encontrar opções relevantes pela localização e características.
- **Abordagem:** coleta anúncios, valida a localização, consolida duplicidades e organiza os resultados em painel com mapa e filtros.
- **Demonstração:** [imoveiscapivari.duckdns.org](https://imoveiscapivari.duckdns.org)

### Capi Finanças
Sistema privado para registrar e consultar despesas domésticas.

- **Problema:** reduzir o trabalho de transcrever gastos e faturas para uma planilha.
- **Abordagem:** reúne mensagens coladas do WhatsApp, lançamentos rápidos e importação de faturas PDF, CSV e OFX em uma fila de revisão. Categorias e formas de pagamento podem ser corrigidas antes da sincronização com o Google Sheets; consultas resumem os gastos por mês, categoria e meio de pagamento.
- **Acesso:** sem demonstração pública; a aplicação contém dados financeiros privados.

### Radar Freela
Automação para encontrar oportunidades freelance de Dados e BI.

- **Problema:** acompanhar oportunidades em plataformas diferentes e priorizar quais merecem atenção.
- **Abordagem:** busca projetos, usa IA para avaliá-los e organizá-los por prioridade, apoia o envio de propostas e envia notificações pelo Telegram.

## Software, integração e automação

### NanoKVM
Cliente para acessar um dispositivo NanoKVM a partir de um PC Windows ou celular Android.

- **Problema:** simplificar a descoberta do dispositivo na rede e o acesso local ou remoto.
- **Abordagem:** o launcher localiza o NanoKVM e abre sua interface em uma janela dedicada; no Android, o app oferece uma experiência em tela cheia. O acesso remoto pode usar Tailscale quando configurado.
- **Código-fonte:** privado.

### Tibiatimer
Bot do Discord com avisos de voz para mecânicas de chefes de Tibia, acionados por teclas de atalho no PC.

- **Problema:** coordenar contagens e avisos durante uma chamada de voz sem depender de acionamentos manuais no Discord.
- **Abordagem:** combina contagens regressivas e ciclos repetidos de avisos; os cronômetros podem rodar juntos, com prioridade para a contagem curta.
- **Código-fonte:** privado.

### Civ5 Crash Guard
Ferramenta de estabilidade e manutenção para uma instalação de Civilization V com muitos mods.

- **Problema:** investigar falhas e manter correções aplicadas entre atualizações do jogo e dos mods.
- **Abordagem:** monitora o jogo, lê logs e dumps, gera informações de diagnóstico e reaplica correções verificadas. O projeto também reúne mods próprios e ferramentas de apoio para esse ambiente.
- **Código-fonte e arquivos:** privados; não é uma distribuição de mods ou arquivos de terceiros.

## Contato

[LinkedIn](https://www.linkedin.com/in/joaopedrodosanjos/)
