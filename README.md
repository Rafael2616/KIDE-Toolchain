# KIDE Toolchain

Este repositório contém o conjunto de ferramentas e recursos essenciais (Toolchain) para o projeto **KIDE**. Aqui você encontrará binários, bibliotecas e imagens de sistema otimizados para o ambiente de desenvolvimento Android.

## 🚀 Estrutura do Repositório

O repositório está organizado da seguinte forma:

*   **`v1.0/`**: Contém os binários e arquivos compilados prontos para uso.
    *   `jdk-17.0.20/`: Java Development Kit v17.
    *   `jdk-21.0.12/`: Java Development Kit v21.
    *   `proot-5.1.107.92/`: Utilitário PRoot para emulação de chroot.
    *   `rootfs-ubuntu-22.04.5/`: Imagem base do Ubuntu para o ambiente KIDE.
*   **`docs/`**: Documentação detalhada sobre a origem dos recursos e como atualizá-los.

## 📖 Documentação

Para mais detalhes sobre cada componente, consulte os guias abaixo:

| Componente | Descrição                                                               | Link |
| :--- |:------------------------------------------------------------------------| :--- |
| **Java JDKs** | Download e links oficiais para JDK 17 e 21.                             | [docs/jdks.md](docs/jdks.md) |
| **PRoot & Libs** | Binários do PRoot e bibliotecas auxiliares (libtalloc, etc).            | [docs/proot.md](docs/proot.md) |
| **Ubuntu RootFS** | Informações sobre a imagem base do sistema.                             | [docs/rootfs-ubuntu.md](docs/rootfs-ubuntu.md) |
| **AAPT2 & Libs** | Binário do AAPT2 Nativo para o SDK do Android e bibliotecas auxiliares. | [docs/aapt2.md](docs/aapt2.md) |

## 🛠️ Como usar

Este toolchain foi projetado para ser integrado ao ambiente KIDE. Os binários na pasta `v1.0` são compatíveis com arquiteturas `arm64-v8a`, `armeabi-v7a` e `x86_64`.

---
*KIDE Toolchain - Desenvolvido para potencializar seu ambiente de desenvolvimento.*
