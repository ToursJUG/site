# Site du ToursJug basé sur Hugo.

## Initialisation des sous modules git

> /!\ Ce repository utilise des sous-modules git, il est nécessaire de les initialiser.

```bash
git submodule init
git submodule update
``` 

pour lancer sans installation de hugo (nécessite docker) :

* construction préalable de l'image Hugo (inexistante sur docker hub) : 
```
git clone git@github.com:gohugoio/hugo.git
cd hugo
docker build --build-arg HUGO_BUILD_TAGS=extended --network=host -t gohugoio/hugo .
cd ..
rm -rf ./hugo
```
* dans le répertoire courant : 
```
docker run --rm --network=host -v pwd:/site gohugoio/hugo server
```


