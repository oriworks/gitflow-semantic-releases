- Feature branch deve estar sempre atualizada com develop.
- Develop branch deve estar sempre atualizada com master.
```shell
git checkout develop
git pull
git merge --no-ff master -m "chore(merge): merge 'master' into 'develop'"
git push
```