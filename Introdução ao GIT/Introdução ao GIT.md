# **Entendendo o que é o GIT**
- Criado por Linus Torvalds
- Software não é criado sozinho 

**Comandos:**
| Windows | Unix | Função |
| ------ | ------ | ----- |
| CD | CD | para ir em uma pasta |
| DIR | LS | diretório/lista de pastas |
| MKDIR | MKDIR | criar uma pasta |
| DEL/RMDIR | RM - RF | deletar pasta e repositório |

# Como o GIT funciona por baixo dos panos:
 - SHA1
 -- é um algoritmo de encriptação 
 - Objetos fundamentais
 -- BLOOBS (guarda o SHA1)
-- TREES (armazena os BLOOBS que armazena outras TREES)
-- COMMITS (armazena as TREES)
   - Os COMMITS tem: TREE, parente, autor, mensagem e timestamp
 - Sistema distribuído 
 - Segurança
 
**Chave SSH e Token**
- são chaves para manter uma conexão segura e criptografada

## Primeiros comandos do GIT
git init = inicia o repositório de uma pasta
ls -a = conteúdo oculto de uma pasta 

**login no GIT BASH**
git config --global user.email "regina.hanae@gmail.com"
git config --global user.name Reginahanae1

git add * = adicionou um arquivo que foi criado em uma determinada pasta
criou se um COMMIT e um SHA1

git init = cria uma nova pasta, um repositório 
git clone = para clonar um reositório do GIT HUB para o GITDASH

**Para resolver conflitos, resolve os problemas manualmente no GITHUB ou no GITBASH**
--- 






