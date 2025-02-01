## Demo

![Image](https://github.com/user-attachments/assets/b633dbba-47c7-4760-8d1a-b0922ca80f7e)

## Installation

1. Create the database (ex: `example-app`)

2. Terminal (Powershell, etc)

    ```shell
    git clone https://github.com/raflizocky/laravel11-sbadmin2.git
    ```

    ```shell
    code laravel11-sbadmin2
    ```

3. `.env`

    - Terminal:
        ```shell
        cp .env.example .env
        ```
    - Adjust `.env`:
        ```shell
        DB_CONNECTION=mysql
        DB_HOST=127.0.0.1
        DB_PORT=3306
        DB_DATABASE=example-app
        DB_USERNAME=root
        DB_PASSWORD=
        ```

4. Terminal (Powershell, etc)
    - 1
      ```shell
      composer i ; php artisan key:generate ; php artisan mi
      ```
    - 2
      ```shell
      php artisan serve
      ```

## Contributing

If you encounter any issues or would like to contribute to the project, feel free to:

-   Report any [issues](https://github.com/raflizocky/laravel-sbadmin2/issues)
-   Submit a [pull request](https://github.com/raflizocky/laravel-sbadmin2/pulls)
-   Participate in [discussions](https://github.com/raflizocky/laravel-sbadmin2/discussions) for any questions, feedback, or suggestions

## License

Code released under the [MIT License](https://github.com/raflizocky/laravel-sbadmin2/blob/main/LICENSE).
