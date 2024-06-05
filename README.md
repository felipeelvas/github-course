Git Course

Arquivo da aula do Git Github para iniciantes

Repositório Teste para saber como o git funciona

Saiba mais em [willianjusten.com.br](http://wllianjustencom.br)

Comandos:
cd 00-Files-Elvas/

mkdir git-course

cd git-course/

git init

Repositório vazio Git inicializado em /home/elvas/00-Files-Elvas/git-course/.git/

ls -la

total 12
drwxrwxr-x  3 elvas elvas 4096 jun  5 10:52 .
drwxrwxr-x 16 elvas elvas 4096 jun  5 10:51 ..
drwxrwxr-x  7 elvas elvas 4096 jun  5 10:52 .git

elvas@elvas-b-dell:~/00-Files-Elvas/git-course$ cd .
./    ../   .git/ 

elvas@elvas-b-dell:~/00-Files-Elvas/git-course$ cd .gitelvas@elvas-b-dell:~/00-Files-Elvas/git-course/.git$ ls

branches  config  description  HEAD  hooks  info  objects  refs

elvas@elvas-b-dell:~/00-Files-Elvas/git-course/.git$ cd ..
elvas@elvas-b-dell:~/00-Files-Elvas/git-course$ vi README.md
elvas@elvas-b-dell:~/00-Files-Elvas/git-course$ ls
README.md

git status
No ramo main

No commits yet

Arquivos não monitorados:
  (utilize "git add <arquivo>..." para incluir o que será submetido)
	README.md

nada adicionado ao envio mas arquivos não registrados estão presentes (use "git add" to registrar)

git add README.md 
git status
No ramo main

No commits yet

Mudanças a serem submetidas:
  (utilize "git rm --cached <arquivo>..." para não apresentar)
	new file:   README.md


 git commit -m "add README.md"
[main (root-commit) e27e075] add README.md
 1 file changed, 4 insertions(+)
 create mode 100644 README.md

git log
commit f860712fde58e134cdbbe17ab0105b2795304e44 (HEAD -> main)
Author: Felipe Elvas Barbosa <felipeelvas+1@gmail.com>
Date:   Wed Jun 5 11:29:26 2024 -0300

    add alteração no README.md

commit e27e075bec9db35f74d17a71568492fae789ce3b
Author: Felipe Elvas Barbosa <felipeelvas+1@gmail.com>
Date:   Wed Jun 5 11:25:06 2024 -0300

    add README.md

git log --decorate
commit f860712fde58e134cdbbe17ab0105b2795304e44 (HEAD -> main)
Author: Felipe Elvas Barbosa <felipeelvas+1@gmail.com>
Date:   Wed Jun 5 11:29:26 2024 -0300

    add alteração no README.md

commit e27e075bec9db35f74d17a71568492fae789ce3b
Author: Felipe Elvas Barbosa <felipeelvas+1@gmail.com>
Date:   Wed Jun 5 11:25:06 2024 -0300

    add README.md

git log --author="Felipe"
commit f860712fde58e134cdbbe17ab0105b2795304e44 (HEAD -> main)
Author: Felipe Elvas Barbosa <felipeelvas+1@gmail.com>
Date:   Wed Jun 5 11:29:26 2024 -0300

    add alteração no README.md

commit e27e075bec9db35f74d17a71568492fae789ce3b
Author: Felipe Elvas Barbosa <felipeelvas+1@gmail.com>
Date:   Wed Jun 5 11:25:06 2024 -0300

    add README.md

 git shortlog
Felipe Elvas Barbosa (2):
      add README.md
      add alteração no README.md

Git Course

Arquivo da aula do Git Github para iniciantes

Repositório Teste para saber como o git funciona

Saiba mais em [willianjusten.com.br](http://wllianjustencom.br)

