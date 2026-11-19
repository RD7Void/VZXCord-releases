![VZXCord — Variante do projeto Serein, sem fins lucrativos](assets/banner.png)

# VZXCord

**Variante não oficial e sem fins lucrativos do [Serein](https://github.com/ViceVerse-cz/Serein), cliente desktop nativo para Discord em Rust.**

Este repositório é destinado à distribuição das versões do VZXCord. Não contém o código-fonte completo do aplicativo. O projeto não é afiliado, patrocinado ou endossado pelo Discord nem pelos mantenedores do Serein. Não há cobrança, monetização ou finalidade de lucro nesta distribuição.

## Downloads para Windows

Baixe os arquivos na [última release](https://github.com/RD7Void/VZXCord-releases/releases/latest):

- **Setup.exe:** instalador para Windows x64.
- **Windows-x64.zip:** pacote portátil; extraia tudo e execute `VZXCord-Portatil.cmd`.
- **VZXCord-SHA256.txt:** hashes para conferir os downloads.
- **Componentes-Licencas.zip:** avisos originais e código correspondente do componente hpke-rs modificado (MPL-2.0).

## Créditos

O **Serein** é o projeto original. Os créditos pelo desenvolvimento da base pertencem a **ViceVerse-cz e aos [contribuidores do Serein](https://github.com/ViceVerse-cz/Serein/graphs/contributors)**. Origem desta variante: commit [`054286c`](https://github.com/ViceVerse-cz/Serein/commit/054286cade72e39838c20a5236b51e4838613dc3).

A adaptação VZXCord, distribuída por **RD7Void**, inclui identidade visual própria, empacotamento para Windows e ajustes de compatibilidade de extensões e entrada de teclado. Ela não reivindica autoria sobre o trabalho original de terceiros.

Também são creditados os autores e contribuidores das bibliotecas utilizadas, incluindo **egui/eframe, wgpu, Tokio, Serde, Wry, RustCrypto, hpke-rs**, além de **Phosphor Icons, Simple Icons, Twemoji, Inter e Noto**. A relação detalhada está em [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md). Cada componente mantém sua licença e seus respectivos titulares.

## Licenças

A base Serein utiliza **MIT OR Apache-2.0**. Os avisos originais estão preservados em [licenses/Serein-LICENSE-MIT](licenses/Serein-LICENSE-MIT) e [licenses/Serein-LICENSE-APACHE](licenses/Serein-LICENSE-APACHE). As alterações do VZXCord seguem MIT OR Apache-2.0. Essas licenças não substituem as licenças das dependências.

Discord e as demais marcas mencionadas pertencem aos respectivos titulares.

## Versão atual

**0.1.0 — Windows x64.** Inclui compatibilidade com extensões WebAssembly já compiladas e correção da digitação de `?` por `Ctrl + Alt + W`. Verificações: 46 testes de extensões e 5 testes de integração/entrada aprovados. Login e conversa reais não foram testados como parte dessas verificações.
