![Image of Yaktocat](https://res.cloudinary.com/hy4kyit2a/f_auto,fl_lossy,q_70/learn/modules/git-and-git-hub-basics/work-with-the-git-hub-workflow/images/17cdcf6d5135213b505e04eb6c7be614_4-collaborate.png)

# Git-GitHub do Zero


## 00 - Instalando o Git na sua máquina.

Usuários dos Sistemas Operacionais(OS) **MAC** e **Linux** não precise instalar pois o Git já vem de fábrica.

Para instalar o git na sua máquina (caso ainda não o tenha) no caso usuários **Windows** irão ter de baixá-lo. 

não precisa se precupar, pois a instalaçao é bem fácil de fazer [instalar](https://git-scm.com/).

 
### Por quê ?

Imagine contribuir com um projeto grande, com colaboradores de todas as partes do mundo fazendo alterações (às vezes ao mesmo tempo) em um mesmo arquivo ? Se você já conhece git sabe que isso causará provavelmente muitos conflitos que podem soar desesperadores e por vezes complicados de resolver.

  1 - Controle de Versão</br>
  2 - Armazenamento em nuvem</br>
  3 - Melhorar seu código</br>
  5 - Reconhecimento</br>

### O que é Git ?

  Um sistema de controle de versão, moderno e mais usado no mundo. O Git é um projeto de código aberto, com manutenção ativa desenvolvido em 2005 por Linus Torvalds,  mesmo criado do kernel Linux.</br>
  Muitos projetos de software depende do Git para controle de versão, projetos código-fonte aberto e incluindo projetos comerciais.</br>
  Os desenvolvedores que trabalharam com o Git estão bem representados no pool de talentos de desenvolvimento de software disponíveis e funcionam bem em uma ampla variedade de sistemas operacionais e IDEs (Ambientes de Desenvolvimento Integrado).</br>
  Sendo um exemplo de DVCS (Sistema de Controle de Versão Distribuído). o Git se diferencia porque a cópia de trabalho de todo desenvolvedor do código também é um repositório que pode conter o histórico completo de todas as alterações.
  Além de ser distribuído, o Git foi projetado com desempenho, segurança e flexibilidade em mente.</br>

 
### Navegação CLI

Comandos basicos para um bom desempenho no terminal
Diferença entre os sistemas operacionais
#### Comandos windows
  cd, dir, mkdir,del/rmdir

#### Comandos Unix
  cd, ls, mkdir, rm / -rf
  
### Fundamentos Git

- SHA1
Secure hash Algorithm (Algoritmo de Hash Seguro), é um conjunto de funções hash criptograficas projedadas pela NSA (Agência de Segurança nacional dos EUA).
A encriptação gera conjunto de characteres identificador de 40 dígitos.

echo "ola mundo" | openssl sha1
> (stdin)= f9fc856e559b950175f2b7cddad61facbe58e7b

- Objetos internos do Git

 - blobs
   - echo 'conteudo' | git hash-object --stdin
   > fc31e91b26cf85a55e072476de7f263c89260eb1
   
   -SHA1 sa4d8s... 
   -Blob ---- Tamanho 42
   -\0
   -ola Mundo
   
 - Trees
  Armazenam Blobs
   - Tree <tamanho>
   -\0
   -blob sa4d8s texto.txt
   -blob
 
 - Commits
   - tree s4a5sq
   - parente a98acq1
   - autor perkles
   - mensagem "inici..."
   - timestamp

- Sistemas Distribuidos
 - Definir
 - Segurança 
 - Definir
 
- Primeiros Commandos com Git
   - Iniciando o Git
   git init
   git add * ou arquivo
   git commit - m "msg"
   
  - criando um commit
 
 Ciclo de vida dos arquivos Git
  - Passo a passo
 
Conclusão
