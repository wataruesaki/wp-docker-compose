# wp-docker-compose

Docker compose to have an adventure in WordPress.

## How to use

### 1. Create `.env`

```bash
touch .env
```

### 2. Configure `.env`

```txt
WP_PORT=WordPress port number
PHP_MY_ADMIN_PORT=phpMyAdmin port number
THEME_NAME=your theme name
```

#### Example

```txt
WP_PORT=8080
PHP_MY_ADMIN_PORT=8081
THEME_NAME=theme
```

### 3. Generate theme

```bash
bin/theme
```

### 4. Run docker compose

```bash
docker-compose up
```

### 5. Set up WordPress

#### Open `http://localhost:${WP_PORT}`

#### Install WordPress

#### Log in to WordPress

#### Activate your theme

### phpMyAdmin

You can log in to phpMyAdmin with the following information.

#### User

`root`

#### Password

`secret`

`wordpress` database is for WordPress.
