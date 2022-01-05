# Git Repository List

- node v14.18.1

- express
- react v17.0.2
- cors
- axios
- eslint-config-prettier
- express-validation
- psql

## Install psql

https://www.postgresql.org/download/

#### Get user details

```http

GET /user/api/{name}

```

| Parameter | Type | Description |

| :-------- | :------- | :------------------------------- |

| `user` | `string` | **Required**. Github user handle |

#### Get user repositories

```http

GET /user/repo/{name}

```

| Parameter | Type | Description |

| :-------- | :------- | :------------------------------------------ |

| `user` | `string` | **Required**. Github username to fetch repo |

## Run Locally

Clone the project

```bash

git clone https://github.com//github-assignment.git

```

Go to the project directory

```bash

cd github-assignment

```

Install dependencies

```bash

npm install

```

Install both client and server side dependencies with npm

```bash

npm run getpkg

```

Start the server

```bash

npm start

```

## Author

- [@pmandloi](https://www.github.com/pmandloi)
