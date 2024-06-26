# omise
A point-of-sale app built using Laravel and React.

## Installation
1. Create a database
2. Navigate to ```src/api```
3. Copy the ```.env.example``` file and rename it to ```.env```
4. Edit the ```.env``` file to match your environment configuration
5. In ```src/api```, execute
```bash
composer update
npm install
npm run build
php artisan migrate:fresh --seed
php artisan key:generate
php artisan storage:link
```

## Usage
In a terminal pointed to ```src/api```, execute
```bash
php artisan serve
```
then, in another terminal pointed to ```src/app```, execute
```bash
npm start
```
then visit http://localhost:3000 (or whichever port ```npm``` serves on) on your browser.

## Contributing
Read the following files in order and see where you can help:
1. [doc/description.md](doc/description.md)
2. [doc/end-tree.md](doc/end-tree.md)
