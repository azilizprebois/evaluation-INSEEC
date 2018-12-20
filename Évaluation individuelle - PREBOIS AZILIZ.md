# Évaluation individuelle

## Programmation - Coaching

```
Nom : PRÉBOIS
Prénom : AZILIZ
URL de votre compte Github : https://github.com/azilizprebois
```

## Déroulé et fonctionnement. 

L'évaluation est à faire sur [Typora](https://typora.io/). Les réponses sont à écrire dans les blocks de code. 
Pour la partie Ruby, testez votre code sur [repl.it](https://repl.it/) et copiez le dans les blocks de code prévu à cet effet. 
Une fois fini, pushez votre feuille sur Github, dans un nouveau repository que vous appelerez "evaluation-inseec".
L'évaluation est individuelle et durera 1h30. Elle intègre des notions d'HTML, CSS, Ruby et computer science. 

![alt](https://media.giphy.com/media/26xBBfd0ii1khakpy/giphy.gif)

## Quelques mises en garde.

Je connais très bien ce merveilleux site qu'est Wikipédia. Je vous saurais gré de ne pas me remplir certaines questions avec les définitions de Wikipédia. Accessoirement, je sais aussi faire une recherche Google. Si j'ai un doute, je n'hésiterais pas rechercher "Qu'est-ce qu'une API" et comparer les définitions en tête de recherche avec les votre. Si je trouve une similarité trop grande et que je doute de votre bonne foi, je n'hésiterais pas à mettre 0 à la question. 
Pareil pour la copie sur les voisins. Si c'est trop gros et que j'ai un doute trop prononcé... 🔫

![alt](https://media.giphy.com/media/BtedgmzGNCiuk/giphy.gif)



------

### 1. Avec vos mots, expliquez l'interaction client-serveur

```t
Il s'agit d'un mode de communication entre plusieurs programmes coopérant ensemble : le client envoi une requête au serveur qui va lui apporter la réponse recherchée.
```



 ### 2. HTML est un langage côté... 

```
serveur.
```



### 3. Donnez-moi la structure de base d'une feuille HTML

```html
<!DOCTYPE html>
<html lang="en">
    <head>
    </head>
    <body>
```



### 4. Changez la couleur du texte "J'adore la programmation" en rose en utilisant du CSS.

```html
<div>
   <p>J'adore la programmation</p>
</div>
```

```css
/* Ecrire le code CSS sous cette ligne */
p {
    color: pink;
 
}
```



### 5. Qu'est-ce que Bootstrap ?

```
Bootstrap permet la mise en forme de page web. Il s'agit de ce que l'on appel un Framework CSS (logiciel simplifiant la conception d'un site web)
```



### 6. Reprenez votre code de la question 3 et ajoutez Bootstrap à votre feuille HTML, au bon endroit.

```html
<!DOCTYPE html>
<html lang="en">
    <head>
    
        <!-- Bootstrap CSS -->

    </head>
    <body>
```



### 7. Mettez ces trois divs sur le même plan horizontal avec trois colonnes de même taille.

```html
    
<div class="row">
                <div class="col-sm-4">
					GOOGLE
 			   </div>
                   
                <div class="col-sm-4">
                   MICROSOFT
                </div>
                
                <div class="col-sm-4">
                  APPLE
                </div>


```



### 8. Avec le même code, changez le texte par le logo de la marque en question

```html
<div class="row">
                <div class="col-sm-4">
                    https://i1.wp.com/www.grapheine.com/wp-content/uploads/2015/09/nouveau-logo-google.gif?fit=1950%2C1200&quality=90&strip=all&ssl=1
</div>

                <div class="col-sm-4">    https://wwwfr.uni.lu/var/storage/images/media/images/lcl_images/microsoft_logo/1265810-1-fre-FR/microsoft_logo.jpg
</div>

                <div class="col-sm-4">
    https://upload.wikimedia.org/wikipedia/commons/thumb/7/70/Logo_Apple.inc.gif/220px-Logo_Apple.inc.gif
</div>
```

 

### 9. Toujours sur le même bout de code, rendez les logos cliquables. Quand on clique sur le logo, on doit arriver sur le site officiel de la marque.

```html
<div>
    Google
</div>

<div>
    Microsoft
</div>

<div>
    Apple
</div>
```

![Mon gars sûr !](https://media.giphy.com/media/l0K4mbH4lKBhAPFU4/giphy.gif)

### 10. Parlons Ruby. Ruby est un langage côté...

```
client.
```



### 11. Listez-moi tous les types de données que vous connaissez.

```
String, integer, float
```



### 12. Assignez à des variables votre prénom, nom et le lien de votre compte Github puis affichez chacune des variables. En 6 lignes.

```ruby
print "What's your first name? "
first_name = Aziliz

print "What's your last name? "
last_name = Prébois

print "What's your Github link? "
link_github = https://github.com/azilizprebois 
```



### 13. Assignez 674 et 311 à des variables `a` et `b` et stockez le résultat `a` modulo `b` dans une variable `c` et affichez la. 

```ruby
> a = 674
=> 30
> b = 2
=> 20
> a = a + b
=> 52
```



### 14. Qu'est-ce qu'une gem ? 

```texte
Les gems sont liés à la plateforme RUBY. Il s'agit de codes produits par des développeurs extérieurs à RUBY, ces codes permettent d'accroître et d'améliorer les fonctionnalités de l'application.
```



### 15. Qu'est-ce qu'une API et qu'est-ce qui nous permet de nous y connecter ?

```
Une API est une interface de programmation. Nous pouvons nous y connecter grâce aux technologies du web (applications, https, interfaces, clé).
```



### 14. On va créer un script pour dire bonjour ou bonsoir, en fonction de l'heure de la journée. Votre script doit demander à l'utilisateur de rentrer son prénom. Si `hour` est inférieur à 12, lui dire `Bonjour Anthony` sinon `Bonsoir Anthony` (évidemment, le prénom doit être celui renseigné par l'utilisateur).

```Ruby
hour = 15 
prenom = gets.chomp
if hour < 12
puts "bonjour #{prenom}"
else
puts "Bonsoir #{prenom}"
end

```



### 15. Itérer sur l'array contenant des noms de twitos un peu famous et follow chacun d'eux grâce à une méthode trouvée dans la [doc de la gem twitter](https://github.com/sferik/twitter). Pas besoin de lancer le code et de faire la partie authentification. Juste le bloc d'itération suffira. 

```ruby
handles = ["@richardbranson", "@jeffweiner", "@LinkedInQueen", "@ericschmidt", "@elonmusk", "@petecashmore", "@SteveForbesCEO", "@mtbarra"]


```



### 16. Félicitations, vous êtes arrivé·e à la fin, pushez cette feuille sur votre Github dans un repo appelé `evaluation-inseec`. N'oubliez pas de remplir le premier block avec votre identité tout en haut ! 

![alt](https://media.giphy.com/media/l0MYJnJQ4EiYLxvQ4/giphy.gif)

