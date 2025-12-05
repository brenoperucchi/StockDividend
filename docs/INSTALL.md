# Guia de Instalacao

## Instalacao Automatica (Recomendado)

### 1. Baixar o Instalador

Baixe a versao mais recente do instalador:
- [StockInstaller.exe](https://github.com/brenoperucchi/StockDividend/releases/latest/download/StockInstaller.exe)

### 2. Executar o Instalador

1. Execute `StockInstaller.exe`
2. Clique em **"Detectar MT5"** para encontrar instalacoes do MetaTrader 5
3. Selecione as instalacoes onde deseja instalar o EA
4. Clique em **"Instalar"**

### 3. Ativar no MetaTrader 5

1. Abra o MetaTrader 5
2. No Navegador (Ctrl+N), expanda **Expert Advisors**
3. Arraste `StockDividendEA` para o grafico desejado
4. Configure os parametros e clique em OK

---

## Instalacao Manual

### 1. Baixar o EA

Baixe o arquivo compilado:
- [StockDividendEA.ex5](https://github.com/brenoperucchi/StockDividend/releases/latest/download/StockDividendEA.ex5)

### 2. Localizar a Pasta do MT5

O MetaTrader 5 geralmente esta instalado em:
- `C:\Program Files\MetaTrader 5\`
- `C:\Users\[Usuario]\AppData\Roaming\MetaQuotes\Terminal\[ID]\`

Para encontrar a pasta correta:
1. Abra o MT5
2. Menu **Arquivo** > **Abrir Pasta de Dados**
3. Navegue ate `MQL5\Experts\`

### 3. Copiar o Arquivo

Copie `StockDividendEA.ex5` para a pasta `MQL5\Experts\`

### 4. Reiniciar e Ativar

1. Reinicie o MetaTrader 5
2. O EA aparecera em **Navegador** > **Expert Advisors**
3. Arraste para o grafico e configure

---

## Atualizacoes

### Automatica (via Instalador)

O StockInstaller verifica atualizacoes automaticamente ao iniciar.
Clique em **"Atualizar"** quando uma nova versao estiver disponivel.

### Manual

1. Baixe a nova versao do [StockDividendEA.ex5](https://github.com/brenoperucchi/StockDividend/releases/latest)
2. Substitua o arquivo na pasta `MQL5\Experts\`
3. Reinicie o MT5

---

## Solucao de Problemas

### EA nao aparece no Navegador
- Verifique se o arquivo esta em `MQL5\Experts\` (nao em subpastas)
- Reinicie o MT5 completamente

### EA nao executa trades
- Verifique se o AutoTrading esta ativado (botao verde no topo)
- Verifique a licenca com o desenvolvedor

### Erro de licenca
- Contate o desenvolvedor para ativar sua conta
