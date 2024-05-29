<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="450" alt="Laravel Logo"></a></p>

<p align="center">With</p>

<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/4/4e/Docker_%28container_engine%29_logo.svg" width="300" alt="Laravel Logo"></a></p>

## Starting project

Mettre à jour le fichier .env :

```bash
cp .env.example .env
```

Installer les dépendances avec Composer :

```bash
composer install
```

Générer la clé de l'application :

```bash
php artisan key:generate
```

### Configurer Docker :

Assure-toi que les fichiers de configuration Docker (comme docker-compose.yml) sont présents et correctement configurés.

```bash
docker-compose build
```

```bash
docker-compose up
```
### Faire la migration avec :
```bash
sail artisan migrate
```

### Accèder à l'application à l'adresse :

**app Laravel** => http://localhost:8383

**phpMyAdmin** => http://localhost:8181


### Helper Alias **Sail**
#### ajouter l'alias
pour bash
```bash
echo "alias sail='[ -f sail ] && bash sail || bash vendor/bin/sail'" >> ~/.bashrc
```
ou pour zsh
```bash
echo "alias sail='[ -f sail ] && bash sail || bash vendor/bin/sail'" >> ~/.zshrc
```



## About This e-commerce project

This is a Boiler plate for an e-commerce with Laravel and Docker

-   Laravel Sail
-   MySQL
-   PhpMyAdmin
-   Docker
-   Docker Compose

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Start with a virgin git repo - BoilerPlate

Supprimer le lien github actuel:

```bash
git remote remove origin
```

Ajouter un nouveau dépôt GitHub en utilisant l'URL du nouveau dépôt:

```bash
git remote add origin https://github.com/ton-utilisateur/mon-nouveaur-repo.git
```

Vérifier les nouveaux remotes :

```bash
git remote -v
```

Pousser ton code vers le nouveau dépôt :

```bash
git push -u origin master
```

## Laravel Sponsors

We would like to extend our thanks to the following sponsors for funding Laravel development. If you are interested in becoming a sponsor, please visit the [Laravel Partners program](https://partners.laravel.com).

### Premium Partners

-   **[Vehikl](https://vehikl.com/)**
-   **[Tighten Co.](https://tighten.co)**
-   **[WebReinvent](https://webreinvent.com/)**
-   **[Kirschbaum Development Group](https://kirschbaumdevelopment.com)**
-   **[64 Robots](https://64robots.com)**
-   **[Curotec](https://www.curotec.com/services/technologies/laravel/)**
-   **[Cyber-Duck](https://cyber-duck.co.uk)**
-   **[DevSquad](https://devsquad.com/hire-laravel-developers)**
-   **[Jump24](https://jump24.co.uk)**
-   **[Redberry](https://redberry.international/laravel/)**
-   **[Active Logic](https://activelogic.com)**
-   **[byte5](https://byte5.de)**
-   **[OP.GG](https://op.gg)**

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

# ecom-anais

# boilerEcomLaravelDocker

# boilerEcomLaravelDocker

# boilerEcomLaravelDocker

# boilerEcomLaravelDocker

# boilerEcomLaravelDocker
