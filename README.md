
# create repo github to build gitHub pages
/<username>.github.io -> use url (https://<username>.github.io/) 
or 
/<pathname> ->  use url (https://<username>.github.io/<context name>/)


1.my repo -> setting -> pages -> chick visit -> show page readme.txt render (testing)

2.git clone to local -> coppy project / create project in the repo git -> npm run serve (testing) -> npm run build

3.edit file ignore comment #/dist and save 

4.checking branch current main  
    $ git checkout -b gh-pages -> 
    $ npm run build -> 
    $ git add dist -> 
    $ git commit -m "deploy static repo" -> 
    $ git subtree push --prefix dist origin gh-pages

5.to github my repo -> setting -> pages -> set Branch = gh-pages -> save -> waiting process 