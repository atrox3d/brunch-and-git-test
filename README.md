# brunch-test

### ISTRUZIONI INIZIALI github

We recommend every repository include a README, LICENSE, and .gitignore.


```
echo # brunch-test >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/IngloriousCoderz/brunch-test.git
git push -u origin master
```

OR
```
git remote add origin https://github.com/IngloriousCoderz/brunch-test.git
git push -u origin master
```

#IN LOCALE
```
cd <path>
git clone https://github.com/IngloriousCoderz/brunch-test.git
```

#primi comandi tutorial
https://github.com/brunch/brunch-guide/blob/master/content/en/chapter04-starting-from-scratch.md

```
npm install -g brunch	// globale
```

dalla cartella brunch-test :

```
npm install --save-dev brunch	// locale (raccomandato)
npm install --save-dev coffee-script-brunch
npm install --save-dev stylus-brunch
```

ed infine, sempre come da tutorial, il build:

```
brunch build
```
