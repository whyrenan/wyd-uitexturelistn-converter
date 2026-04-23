# WYD UITextureListN Converter

Ferramenta standalone em HTML para visualizar, ler, exportar e reconstruir arquivos `UITextureListN.bin`, com compatibilidade para layouts de `264` e `528` bytes por registro.

## Recursos

- Conversao de `UITextureListN.bin` para `.txt`
- Conversao de `.txt` para `UITextureListN.bin`
- Compatibilidade com os layouts `264` e `528`
- Deteccao automatica de layout
- Suporte a `BIN de referencia` para reconstruir no formato correto
- Visualizador integrado com listagem dos registros do BIN
- Busca por indice, caminho e tipo
- Exportacao da listagem atual para `.txt`
- Execucao local no navegador, sem instalacao

## Como usar

1. Abra o arquivo `WYD UITextureListN Converter.html` no navegador.
2. Em `BIN PARA TXT`, selecione um arquivo `.bin` para detectar o layout e exportar o `.txt`.
3. Em `TXT PARA BIN`, selecione um arquivo `.txt` e, se necessario, informe um `BIN de referencia`.
4. Use o visualizador para conferir os registros atuais do BIN carregado.

## BIN de referencia

O `BIN de referencia` e opcional. Ele serve para orientar a reconstrucao do arquivo no layout correto quando houver mais de uma variacao de estrutura entre clientes diferentes.

## Compatibilidade

Layouts suportados:

- `264` bytes por registro
- `528` bytes por registro

## Arquivo principal

- `WYD UITextureListN Converter.html`

## Observacoes

- O processamento acontece localmente no navegador.
- Nenhum arquivo e enviado para servidor.
- O seletor de arquivos pode variar conforme o suporte do navegador as APIs modernas de abertura local.

- <img width="1070" height="559" alt="image" src="https://github.com/user-attachments/assets/23f2ad3f-af94-47fa-9282-ecb82cda3a38" />

