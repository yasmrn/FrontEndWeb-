# ![RealWorld Example App](logo.png)

> ### [Svelte](https://github.com/sveltejs/svelte) codebase containing real world examples (CRUD, auth, advanced patterns, etc) that adheres to the [RealWorld](https://github.com/gothinkster/realworld) spec and API.

### [Demo](https://realworld.svelte.dev)&nbsp;&nbsp;&nbsp;&nbsp;[RealWorld](https://github.com/gothinkster/realworld)


J'ai utilisé votre Backend dans lequel j'ai ajouté un fichier .env et le fichier JSON qui comporte tous les lieux de tournages à Paris. "npm start" pour lancer le backend. 
Quant au front-end j'ai utilisé le même (presque) que le vôtre. J'ai réussi à faire une page d'accueil, de login, de register, de locations et détails qui affiche les informations des lieux de tournage.
```bash
npm install
npm run dev
```
pour lancer le Frontend. 

Si un utilisateur random s'inscrit, cela le redirige directement vers la page login avec laquelle il doit s'identifier pour accéder aux fonctionnalités du site telle que les lieux de tournage (page "locations")
Ainsi, si l'utilisateur n'est pas inscrit, il ne peut pas y accéder. L'utilisateur est alors redirigé vers la page login, lui indiquant d'abord de s'identifier. L'utilisateur inscrit peut voir les lieux et peut cliquer sur le bouton "Détails" à côté du lieu correspondant pour ouvrir une modale contenant des détails, afin que le site soit utile.
J'ai donc terminé les 3 premières User Stories.