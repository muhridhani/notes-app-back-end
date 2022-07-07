1. install nodemon
    -npm install nodemon --save-dev
2. install eslint
    -npm install eslint --save-dev
    -npx eslint --init
    -How would you like to use ESLint? -> To check, find problems, and enforce code style.
    -What type of modules does your project use? -> CommonJS (require/exports).
    -Which framework did you use? -> None of these. 
    -Does your project use TypeScript? -> N.
    -Where does your code run? -> Node (pilih menggunakan spasi).
    -How would you like to define a style for your project? -> Use a popular style guide.
    -Which style guide do you want to follow? -> (Anda bebas memilih, sebagai contoh pilih AirBnB).
    -What format do you want your config file to be in? -> JSON.
    -Would you like to …… (seluruh pertanyaan selanjutnya) -> Y.
    - "lint": "eslint ./" (Pada package.json)