### Init
```
npm init -y
```
### Install Dependencies

```
npm install tailwindcss autoprefixer postcss-cli
```
### Init Tailwindcss
```
npx tailwindcss init
npx tailwindcss init tailwind.config.full.js --full
```
### Create configuration file postcss.config.js 
##### Documentation reference [See page](https://tailwindcss.com/docs/installation#add-tailwind-as-a-post-css-plugin)

```
touch postcss.config.js
```
### Script for compile tailwindcss
```
postcss css/tailwind.css -o public/css/styles.css
```
### Script for compile tailwindcss to develop
```
postcss css/tailwind.css -o public/css/styles.css --watch
```