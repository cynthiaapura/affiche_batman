# Mise en place de bouton ouvert/fermer en HTML/CSS

[Lien vers la page](https://capura94.github.io/affiche-batman/)
>Partie HTML
```html
<details> 
    <summary> Description</summary>
        Comment un homme seul peut-il changer le monde ? Telle est la question qui hante Bruce Wayne depuis cette nuit tragique où ses parents furent abattus sous ses yeux, dans une ruelle de Gotham City. Torturé par un profond sentiment de colère et de culpabilité, le jeune héritier de cette richissime famille fuit Gotham pour un long et discret voyage à travers le monde. Le but de ses pérégrinations : sublimer sa soif de vengeance en trouvant de nouveaux moyens de lutter contre l’injustice. 
</details>
```
>Partie CSS
```css
details summary{ 
	list-style-type: none;
	cursor: pointer;
   
}
details summary::-webkit-details-marker{
	display: none;
}
details summary::before{
	display: inline-block;
	content: "+";
	color: #222;
	font-size: 3rem;
    vertical-align: -.3rem;
	font-weight: bolder;
	margin-right: .5rem;
	transform: rotate(0deg);
	transition-duration: .5s;
}
```