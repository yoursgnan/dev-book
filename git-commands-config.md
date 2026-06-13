git config --global alias.tea status

git config --global alias.cook 'checkout -b'

git config --global alias.touch checkout

git config --global alias.sus diff

git config --global alias.shipit '!f() { git add . && git commit -m "$1" && git push; }; f'

git config --global alias.grab '!f() { git pull origin "$1"; }; f'

git config --global alias.serve '!f() { git push origin "$1"; }; f'


# usage

git tea

git cook feature/bank-reconciliation

git touch main

git sus

git shipit "Fix bank reconciliation reset issue"

git grab main

git serve main

