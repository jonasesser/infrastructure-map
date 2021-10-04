https://pinetools.com/split-image
https://stackoverflow.com/questions/24098792/how-to-force-github-pages-build


// Reference: http://lea.verou.me/2011/10/easily-keep-gh-pages-in-sync-with-master/

git commit -m 'rebuild pages' --allow-empty
git push origin gh-pages

git add .
git status // to see what changes are going to be commited
git commit -m 'Some descriptive commit message'
git push origin master

git checkout gh-pages // go to the gh-pages branch
git rebase master // bring gh-pages up to date with master
git push origin gh-pages // commit the changes
git checkout master // return to the master branch


https://www.binary-kitchen.de/wiki/infra:workadventure:maps


https://play.workadventu.re/_/global/jonasesser.github.io/infrastructure-map/map.json
https://jonasesser.github.io/infrastructure-map/map.json

https://git.chaospott.de/Workadventure/workadventure.git