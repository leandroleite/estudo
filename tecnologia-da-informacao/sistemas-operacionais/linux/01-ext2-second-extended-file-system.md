---
titulo: EXT2 - Second Extended File System
---
- [ext2](https://pt.wikipedia.org/wiki/Ext2): O ext2 (do inglês: second extended file system, em português: segundo sistema de arquivos estendido) é um sistema de arquivos para o núcleo do Linux. Foi inicialmente desenvolvido por Rémy Card como um substituto para o extended file system (ext).

# EXT2 - Second Extended File System

É um sistema de arquivos para o núcleo do Linux. Foi inicialmente desenvolvido por Rémy Card como um substituto para o extended file system (ext). Projetado de acordo com os mesmos princípios do Berkeley Fast File System do BSD, foi o primeiro sistema de arquivos de nível comercial para Linux.

## inode ou index node

Um arquivo é descrito (a menos do seu nome e seu diretório pai) por um inode.

O inode é uma estrutura de dados com tamanho padrão de 128 bytes. O tamanho é definido na formatação. Alguns parâmetros são obrigatórios (ou essenciais), como as permissões, o tamanho do arquivo e o endereçamento dos blocos alocados. Outros, embora úteis e quase sempre definidos, são opcionais, como o UID, GID, rótulos de tempo, etc.
