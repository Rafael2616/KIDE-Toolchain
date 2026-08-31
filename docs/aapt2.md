# AAPT2 (Android Asset Packaging Tool 2)

O **AAPT2** (Android Asset Packaging Tool 2) é uma ferramenta essencial de compilação usada para processar, compilar e empacotar os recursos do aplicativo (como layouts XML, imagens, strings e ativos multimídia) em um formato binário otimizado para o sistema operacional Android.

O AAPT2 divide o trabalho de empacotamento em duas etapas principais:
1. **Compile**: Compila os arquivos de recursos individuais em arquivos intermediários no formato `.flat`.
2. **Link**: Mescla todos os arquivos intermediários `.flat`, resolve as referências entre os recursos e empacota o resultado final.

## 🛠️ AAPT2 Nativo

Os pacotes oficiais podem ser obtidos a partir do repositório Termux:

* **Repositório Principal:** [AAPT2](https://packages-cf.termux.dev/apt/termux-main/pool/main/a/aapt2/)

## 📚 Dependências e Bibliotecas

Para que o binário do AAPT2 funcione corretamente no ambiente de compilação, ele depende das seguintes bibliotecas:

| Biblioteca | Descrição | Link de Download |
| :--- | :--- | :--- |
| **fmt** | Biblioteca de formatação de texto em C++ de alto desempenho. | [Download](https://packages-cf.termux.dev/apt/termux-main/pool/main/f/fmt/) |
| **libc++** | Biblioteca Padrão C++ do projeto LLVM / Android NDK. | [Download](https://packages-cf.termux.dev/apt/termux-main/pool/main/libc/libc++/) |
| **libexpat** | Parser XML orientado a fluxo escrito em C. | [Download](https://packages-cf.termux.dev/apt/termux-main/pool/main/libe/libexpat/) |
| **libpng** | Biblioteca de referência para leitura e processamento de imagens PNG. | [Download](https://packages-cf.termux.dev/apt/termux-main/pool/main/libp/libpng/) |
| **libzopfli** | Algoritmo de compressão compatível com DEFLATE para otimização de recursos. | [Download](https://packages-cf.termux.dev/apt/termux-main/pool/main/libz/libzopfli/) |
| **protobuf** | Mecanismo neutro para serialização de dados estruturados. | [Download](https://packages-cf.termux.dev/apt/termux-main/pool/main/p/protobuf/) |
| **zlib** | Biblioteca padrão de compressão de dados para manipulação de pacotes e arquivos ZIP/APK. | [Download](https://packages-cf.termux.dev/apt/termux-main/pool/main/z/zlib/) |

---
> [!IMPORTANT]
> Certifique-se de baixar as bibliotecas e o binário compatíveis com a arquitetura do seu dispositivo (`aarch64`, `arm`, `x86_64`).
