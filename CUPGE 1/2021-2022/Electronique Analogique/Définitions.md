<style>

@media (prefers-color-scheme: light){
	:root	{
		--background:rgb(255, 255, 255);
        --compl:rgb(245,245,255);
		--text:#000000;
		--text-reverse:#ffffff;
		--shadow:rgba(0, 0, 0, 0.1);
	}
}

@media (prefers-color-scheme: dark){
    :root	{
        --background:rgb(25, 25, 35);
        --compl:rgb(20, 20, 30);
		--text:#ffffff;
		--text-reverse:#000000;
		--shadow:rgba(0, 0, 0, 0.3);
	}
}

</style>

# Définitions

> **Une branche** est une partie d'un circuit ou passe un courant identique

> **Un noeud** est un point de jonction de plusieurs branches

> **Une maille** est une boucle dans le circuit qui parcourt différentes branches

| Nom       | Symbole | Unité     |
| :-------- | :------ | :-------- |
| Intensité | I       | Ampère (A)|
| Potentiel | U       | Volt (V)  |
| Tension   | U       | Volt (V)  |

> on peut assimiler le courant au débit d'une rivière et la tension à la largeur d'une rivière

En parallèlle = En dérivation


# Symboles

## Générateurs :

| Nom           | Symbole     |
|:--------------|:-----------:|
| tension continue|<svg width="26" height="33" viewBox="0 0 26 33" style="stroke:var(--text)" fill="none" xmlns="http://www.w3.org/2000/svg"><line y1="12.5" x2="26" y2="12.5"/><line x1="7" y1="20.5" x2="19" y2="20.5"/><line x1="13.5" y1="21" x2="13.5" y2="33"/><line x1="13.5" x2="13.5" y2="12"/></svg> <svg width="20" height="33" viewBox="0 0 20 33" style="stroke:var(--text)"  fill="none" xmlns="http://www.w3.org/2000/svg"><line x1="10" y1="26" x2="10" y2="33"/><line x1="10" x2="10" y2="6"/><circle cx="10" cy="16" r="9.5"/><path d="M10.3536 7.64645C10.1583 7.45118 9.84171 7.45118 9.64645 7.64645L6.46447 10.8284C6.2692 11.0237 6.2692 11.3403 6.46447 11.5355C6.65973 11.7308 6.97631 11.7308 7.17157 11.5355L10 8.70711L12.8284 11.5355C13.0237 11.7308 13.3403 11.7308 13.5355 11.5355C13.7308 11.3403 13.7308 11.0237 13.5355 10.8284L10.3536 7.64645ZM10.5 24L10.5 8L9.5 8L9.5 24L10.5 24Z" fill="black"/></svg>|
|tension sinusoïdale|<svg width="21" height="33" viewBox="0 0 21 33" style="stroke:var(--text)"  fill="none" xmlns="http://www.w3.org/2000/svg"><line x1="10.5" y1="26" x2="10.5" y2="33"/><line x1="10.5" x2="10.5" y2="6"/><circle cx="10.5" cy="16" r="9.5"/><path d="M4.5 15.9997C6.88051 13.2964 10.5 15.9997 10.5 15.9997C10.5 15.9997 14.0644 18.3199 16.5 15.9997"/></svg>|
|tension carré|<svg width="21" height="33" viewBox="0 0 21 33" style="stroke:var(--text)"  fill="none" xmlns="http://www.w3.org/2000/svg"><line x1="10.5" y1="26" x2="10.5" y2="33"/><line x1="10.5" x2="10.5" y2="6"/><circle cx="10.5" cy="16" r="9.5"/><path d="M16.5 18H15.5V14H10.5V18H5.5V14H4.5"/></svg>|
|courant continu|<svg width="21" height="33" viewBox="0 0 21 33" style="stroke:var(--text)"  fill="none" xmlns="http://www.w3.org/2000/svg"><line x1="10.5" y1="26" x2="10.5" y2="33"/><line x1="10.5" x2="10.5" y2="6"/><circle cx="10.5" cy="16" r="9.5"/><path d="M20 16H1"/></svg> <svg width="20" height="33" viewBox="0 0 20 33" style="stroke:var(--text)"  fill="none" xmlns="http://www.w3.org/2000/svg"><line x1="10" y1="31" x2="10" y2="33"/><line x1="10" y1="4.53156e-10" x2="10" y2="3"/><circle cx="10" cy="12" r="9.5"/><circle cx="10" cy="21" r="9.5"/></svg>|

## Dipoles :

| Nom           | Symbole     | Unité           | Grandeur   |
|:--------------|:-----------:|:----------------|:-----------|
| résistance    | <svg width="33" height="10" viewBox="0 0 33 10" style="stroke:var(--text)"  fill="none" xmlns="http://www.w3.org/2000/svg"><line x1="4" y1="4.94446" x2="-2.18557e-08" y2="4.94446"/><line x1="33" y1="4.94446" x2="29" y2="4.94446"/><rect x="29" y="9.5" width="25" height="9" transform="rotate(-180 29 9.5)"/></svg> <svg width="33" height="12" viewBox="0 0 33 12" style="stroke:var(--text)"  fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M0 6.45455H4.86885L8.11475 1L14.0656 11L20.0164 1L25.9672 11L29.2131 5.84848H33"/></svg>| Résistance (R) | Ohm (Ω)   |
| bobine        | <svg width="33" height="12" viewBox="0 0 33 12" style="stroke:var(--text)"  fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M0 11H2.91176V4.88889C2.91176 2.74112 4.43268 1 6.30882 1C8.18497 1 9.70588 2.74112 9.70588 4.88889M9.70588 4.88889C9.70588 2.74112 11.2268 1 13.1029 1C14.9791 1 16.5 2.74112 16.5 4.88889M9.70588 4.88889V11M16.5 4.88889C16.5 2.74112 18.0209 1 19.8971 1C21.7732 1 23.2941 2.74112 23.2941 4.88889M16.5 4.88889V11M23.2941 4.88889V11M23.2941 4.88889C23.2941 2.74112 24.815 1 26.6912 1C28.5673 1 30.0882 2.74112 30.0882 4.88889V11H33"/></svg> | Inductance (L) | Henry (H) |
| condensateur  | <svg width="26" height="33" viewBox="0 0 26 33" style="stroke:var(--text)"  fill="none" xmlns="http://www.w3.org/2000/svg"><line y1="12.5" x2="26" y2="12.5"/><line y1="20.5" x2="26" y2="20.5"/><line x1="13.5" y1="21" x2="13.5" y2="33"/><line x1="13.5" x2="13.5" y2="12"/></svg> | Capacité (C)   | Farad (F) |