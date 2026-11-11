# Kit Sobrevivência Offline — biblioteca

Pacotes de leitura offline usados pelo app [Kit Sobrevivência Offline](https://eugeniofim.github.io/kit-offline/).

Os arquivos são pacotes oficiais do [Kiwix](https://kiwix.org), cortados em partes de 40 MB só para que o app consiga baixá-los (os servidores do Kiwix não permitem download direto por uma página). Nada foi alterado: juntando as partes na ordem, o resultado tem a mesma assinatura do arquivo original.

| Pasta | Arquivo original do Kiwix | Tamanho | SHA-256 |
|---|---|---|---|
| `wikipedia-top/` | `wikipedia_pt_top_nopic_2026-10.zim` (as páginas mais lidas da Wikipédia em português, sem imagens) | 1.095.015.424 bytes | `c37790d98fe5d7689c64faedff7ab457c4d894d10c8fbe51cf897e00df992a3d` |

Para remontar: `cat wikipedia-top/parte-* > wikipedia_pt_top_nopic_2026-10.zim`

## Licença do conteúdo

O texto vem da Wikipédia em português e é distribuído sob [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.pt-br). Os autores são os colaboradores da Wikipédia; o empacotamento é do projeto Kiwix / openZIM.
