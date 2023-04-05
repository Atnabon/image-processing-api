# Udacity Image Processing API

I have an API that can be used in two different ways. As a simple placeholder API, the first allows me to place images into my frontend with the size set via URL parameters for rapid prototyping. The second use case is as a library to serve properly scaled versions of your images to the front end to reduce page load size. Rather than needing to resize and upload multiple copies of the same image to be used throughout my site, the API you create will handle resizing and serving stored images for me.


## Requirement
Here, I will list all the dependencies used in this project and how to install them.

#### 1. TypeScript
`npm i -D typescript ts-node`

#### 2. express and type express(Typescript support for express)
```
npm i -S express
npm i -D @types/express
```

#### 3. nodemon
`npm i -D nodemon`

#### 4. rimraf
`npm install --save-dev rimraf`

#### 5. eslint
`npx eslint --init`

#### 6. prettier 
`npm install --save-dev prettier`

#### 7. set up prettier and eslint
`npm install --save-dev eslint-config-prettier eslint-plugin-prettier`

#### 8. Jest with type definition and typescript jest runner
`npm i -D jest @types/jest ts-jest`

#### 9. SuperTest with type definition
`npm i -D supertest @types/supertest`

#### 10. morgan and types
`npm i -P morgan @types/morgan`

#### 11. sharp and types
`npm i -P sharp @types/sharp`

#### 12. ejs
`npm install ejs --save`



## Resources
- [Jest doc](https://jest-bot.github.io/jest/docs/getting-started.html)
- [TypeScript doc](https://www.typescriptlang.org)
- [Resizing Images with Sharp](https://sharp.pixelplumbing.com/api-resize)
- [Fastest way to copy a file in Node.js](https://stackoverflow.com/questions/11293857/fastest-way-to-copy-a-file-in-node-js)
- [Prettire format options](https://prettier.io/docs/en/options.html)
