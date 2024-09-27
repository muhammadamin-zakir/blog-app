# Blog Sayfası

    Basit bir şekilde blog paylaşılabilen ve kullanıcıların yorum yapabildikleri bir blog sistemi.

# Blog için kullanılan framework, kütüphaneler ve vb.

-   PHP
-   Laravel
-   Mysql
-   Docker
-   Composer
-   WSL

### Projeyi çalıştırmak için gerkenler.

-   docker desktop (https://www.docker.com/products/docker-desktop/)
-   wsl    ()
-   laravel
-   mysql

- wsl indirilmesi
  ```sh
  wsl --install
  ```

-   composer indirilmesi
    ```sh
    php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
    php -r "if (hash_file('sha384', 'composer-setup.php') === 'dac665fdc30fdd8ec78b38b9800061b4150413ff2e3b6f88543c636f7cd84f6db9189d43a81e5503cda447da73c7e5b6') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"
    php composer-setup.php
    php -r "unlink('composer-setup.php');"
    ```

### projenin indirilmesi

2. Clone the repo
    ```sh
    git clone https://github.com/muhammadamin-zakir/blog-app.git
    ```
3. Install NPM packages
    ```sh
    composer install
    ```

### wsl içinden projenin çalıştırılması

   ```sh
    ./vendor/bin/sail up -d
   ```

### localhos/blogs sayfasına gidip projeyi görebilirsiniz.
