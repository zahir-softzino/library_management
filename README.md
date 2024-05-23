# To Run Library Management Project Follow

## Clone the repository

```
git clone https://github.com/zahir-softzino/library_management.git

```

## Go to the folder

```
cd your-repo folder
```

## Install composer dependancies
```
composer install
```
## Install npm dependancies 
```
npm install
```
## Create and configure the environment file
```
cp .env.example .env

```

## Generate application key
```
php artisan key:generate
```
## Run database migration 
```
php artisan migrate
```
## Start the development server
```
php artisan serve
```
## Compile the frontend assets
```
npm run dev
```
