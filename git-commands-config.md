git config --global alias.tea status

git config --global alias.cook 'checkout -b'

git config --global alias.touch checkout

git config --global alias.sus diff

git config --global alias.shipit '!f() { git add . && git commit -m "$1" && git push; }; f'


# usage

git tea

git cook feature/bank-reconciliation

git touch main

git sus

git shipit "Fix bank reconciliation reset issue"

