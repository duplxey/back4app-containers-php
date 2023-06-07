# back4app-containers-php

This repository demonstrates how to dockerize and deploy a [Laravel](https://laravel.com/) application to [Back4app Containers](https://www.back4app.com/container-as-a-service-caas).

To learn more check out the [article](x).

## Deploy (Docker)

1. Install Docker (if you don't have it yet).

2. Build and tag the image:
    ```sh
    $ docker build -t laravel-sample:1.0 .
    ```

3. Start a new container:
   ```sh
    $ docker run -p 80:80 laravel-sample:1.0
    ```

4. Navigate to [http://localhost/](http://localhost/) in your favorite web browser.
