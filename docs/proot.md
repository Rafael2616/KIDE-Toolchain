# PRoot & Bibliotecas Auxiliares

O PRoot é uma implementação de `chroot`, `mount --bind` e `binfmt_misc` que funciona sem privilégios de root. No KIDE, ele é essencial para isolar o ambiente de execução.

## 🛠️ PRoot

Os pacotes oficiais podem ser baixados do repositório Termux:

*   **Repositório Principal:** [Termux PRoot](https://packages-cf.termux.dev/apt/termux-main/pool/main/p/proot/)

## 📚 Dependências e Bibliotecas

Para que o PRoot funcione corretamente no Android, as seguintes bibliotecas são necessárias:

| Biblioteca | Finalidade | Link de Download |
| :--- | :--- | :--- |
| **libtalloc** | Alocador de memória hierárquico usado pelo PRoot. | [Download](https://packages-cf.termux.dev/apt/termux-main/pool/main/libt/libtalloc/) |
| **libandroid-shmem** | Fornece suporte a memória compartilhada (System V SHM) no Android. | [Download](https://packages-cf.termux.dev/apt/termux-main/pool/main/liba/libandroid-shmem) |

---
> [!IMPORTANT]
> Certifique-se de baixar a versão compatível com a arquitetura do seu dispositivo (`aarch64`, `arm`, `x86_64`).
