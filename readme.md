Configurasi

Tahapan

1. Buat folder NOTES-APP-BACK-END
2. npm init --y
3. npm install nodemon --save-dev
4. npm install nanoid@3.x.x
5. install esLint : npm install eslint --save-dev
   npx eslint --init
7. konfig eslint : npx eslint --init
   
How would you like to use ESLint? -> To check, find problems, and enforce code style.
What type of modules does your project use? -> CommonJS (require/exports).
Which framework did you use? -> None of these. 
Does your project use TypeScript? -> N.
Where does your code run? -> Node (pilih menggunakan tanda panah atau spasi di keyboard).
How would you like to define a style for your project? -> Use a popular style guide.
Which style guide do you want to follow? -> (Anda bebas memilih, sebagai contoh pilih AirBnB).
What format do you want your config file to be in? -> JSON.
Would you like to …… (seluruh pertanyaan selanjutnya) -> Y.

npm run lint

10. Add eslintrc.json
    "rules": {
        "no-console": "off",
    }
     
