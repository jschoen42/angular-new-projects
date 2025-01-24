# Angular create new project

```bash
npm install -g @angular/cli@6
ng new angular-v06
```

```bash
npm install -g @angular/cli@7
ng new angular-v07
```

```bash
npm install -g @angular/cli@8
ng new angular-v08
```

```bash
npm install -g @angular/cli@9
ng new angular-v09
```

```bash
npm install -g @angular/cli@10
ng new angular-v10
```

```bash
npm install -g @angular/cli@11
ng new angular-v11
```

```bash
npm install -g @angular/cli@12
ng new angular-v12
npm install => 12.2.18
web server does not start!
```

```bash
npm install -g @angular/cli@13
ng new angular-v13
npm install => 13.3.12
web server starts
```

```bash
npm install -g @angular/cli@14
ng new angular-v14
npm install => 14.3.0
web server does not start!
```

```bash
npm install -g @angular/cli@15
ng new angular-v15
npm install => 15.2.10
```

```bash
npm install -g @angular/cli@16
ng new angular-v16
npm install => 16.2.16
```

```bash
npm install -g @angular/cli@17
ng new angular-v17
nmp install => 17.3.12
```

```bash
npm install -g @angular/cli@18
ng new angular-v18
npm install => 18.2.13
```

```bash
npm install -g @angular/cli@19
ng new angular-v19
npm install => 19.1.3
```

## tsconfig.json

| Angular version (cli)              | 19.1.4         | 18.2.12        | 17.3.11        | 16.2.16        | 15.2.11        | 14.2.13        | 13.3.11        | 12.2.18        | 11.1.2         | 10.2.1         | 9.1.13         | 8.3.29              | 7.3.10              | 6.1.0               |
| ---------------------------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | ------------------- | ------------------- | ------------------- |
| Typescript version                 | 5.7.3          | 5.5.4          | 5.4.5          | 5.1.6          | 4.9.5          | 4.7.4          | 4.6.4          | 4.3.5          | 4.1.2          | 4.0.2          | 3.8.3          | 3.5.3               | 3.2.2               | 2.9.2               |
| compilerOptions                    |                |                |                |                |                |                |                |                |                |                |                |                     |                     |                     |
| baseUrl                            |                |                |                | ./             | ./             | ./             | ./             | ./             | ./             | ./             | ./             | ./                  | ./                  | ./                  |
| outDir                             | ./dist/out-tsc | ./dist/out-tsc | ./dist/out-tsc | ./dist/out-tsc | ./dist/out-tsc | ./dist/out-tsc | ./dist/out-tsc | ./dist/out-tsc | ./dist/out-tsc | ./dist/out-tsc | ./dist/out-tsc | ./dist/out-tsc      | ./dist/out-tsc      | ./dist/out-tsc      |
| forceConsistentCasingInFileNames   |                |                |                | true           | true           | true           | true           | true           | true           |                |                |                     |                     |                     |
| strict                             | true           | true           | true           | true           | true           | true           | true           | true           | true           |                |                |                     |                     |                     |
| noImplicitOverride                 | true           | true           | true           | true           | true           | true           | true           |                |                |                |                |                     |                     |                     |
| noPropertyAccessFromIndexSignature | true           | true           | true           | true           | true           | true           | true           |                |                |                |                |                     |                     |                     |
| noImplicitReturns                  | true           | true           | true           | true           | true           | true           | true           | true           | true           |                |                |                     |                     |                     |
| noFallthroughCasesInSwitch         | true           | true           | true           | true           | true           | true           | true           | true           | true           |                |                |                     |                     |                     |
| skipLibCheck                       | true           | true           | true           |                |                |                |                |                |                |                |                |                     |                     |                     |
| isolatedModules                    | true           | true           | true           |                |                |                |                |                |                |                |                |                     |                     |                     |
| esModuleInterop                    | true           | true           | true           |                |                |                |                |                |                |                |                |                     |                     |                     |
| sourceMap                          |                | true           | true           | true           | true           | true           | true           | true           | true           | true           | true           | true                | true                | true                |
| declaration                        |                | false          | false          | false          | false          | false          | false          | false          | false          | false          | false          | false               | false               | false               |
| downlevelIteration                 |                |                |                |                | true           | true           | true           | true           | true           | true           | true           | true                |                     |                     |
| experimentalDecorators             | true           |                |                | true           | true           | true           | true           | true           | true           | true           | true           | true                |                     |                     |
| module                             |                |                |                |                |                |                |                |                |                |                | esnext         | esnext              | es2015              | es2015              |
| moduleResolution                   | bundler        | bundler        | node           | node           | node           | node           | node           | node           | node           | node           | node           | node                | node                | node                |
| importHelpers                      | true           | true           | true           | true           | true           | true           | true           | true           | true           | true           | true           | true                | true                | true                |
| target                             | ES2022         | ES2022         | ES2022         | ES2022         | ES2022         | es2020         | es2017         | es2017         | es2015         | es2015         | es2015         | es2015              | es5                 | es5                 |
| module                             | ES2022         | ES2022         | ES2022         | ES2022         | ES2022         | es2020         | es2020         | es2020         | es2020         | es2020         | es2020         |                     |                     |                     |
| typeRoots                          |                |                |                |                |                |                |                |                |                |                |                | node_modules/@types | node_modules/@types | node_modules/@types |
| useDefineForClassFields            |                |                |                | false          | false          |                |                |                |                |                |                |                     |                     |                     |
| lib                                |                | [ES2022, dom]  | [ES2022, dom]  | [ES2022, dom]  | [ES2022, dom]  | [es2020, dom]  | [es2020, dom]  | [es2018, dom]  | [es2018, dom]  | [es2018, dom]  | [es2018, dom]  | [es2018, dom]       | [es2018, dom]       | [es2017, dom]       |
|                                    |                |                |                |                |                |                |                |                |                |                |                |                     |                     |                     |
| angularCompilerOptions             |                |                |                |                |                |                |                |                |                |                |                |                     |                     |                     |
| enableI18nLegacyMessageIdFormat    | false          | false          | false          | false          | false          | false          | false          | false          | false          | false          |                |                     |                     |                     |
| strictInjectionParameters          | true           | true           | true           | true           | true           | true           | true           | true           | true           | true           |                |                     |                     |                     |
| strictInputAccessModifiers         | true           | true           | true           | true           | true           | true           | true           | true           | true           | true           |                |                     |                     |                     |
| strictTemplates                    | true           | true           | true           | true           | true           | true           | true           | true           | true           | true           |                |                     |                     |                     |
| fullTemplateTypeCheck              |                |                |                |                |                |                |                |                |                |                | true           | true                |                     |                     |
| strictInjectionParameters          |                |                |                |                |                |                |                |                |                |                | true           | true                |                     |                     |

## installed packages

| Angular main version              | 19     | 18      | 17      | 16      | 15      | 14      | 13       | 12       |
| --------------------------------- | ------ | ------- | ------- | ------- | ------- | ------- | -------- | -------- |
| @angular-devkit/build-angular     | 19.1.4 | 18.2.12 | 17.3.11 | 16.2.16 | 15.2.11 | 14.2.13 | 13.3.11  | 12.2.18  |
| @angular/animations               | 19.1.3 | 18.2.13 | 17.3.12 | 16.2.12 | 15.2.10 | 14.3.0  | 13.3.12  | 12.2.17  |
| @angular/cli                      | 19.1.4 | 18.2.12 | 17.3.11 | 16.2.16 | 15.2.11 | 14.2.13 | 13.3.11  | 12.2.18  |
| @angular/common                   | 19.1.3 | 18.2.13 | 17.3.12 | 16.2.12 | 15.2.10 | 14.3.0  | 13.3.12  | 12.2.17  |
| @angular/compiler-cli             | 19.1.3 | 18.2.13 | 17.3.12 | 16.2.12 | 15.2.10 | 14.3.0  | 13.3.12  | 12.2.17  |
| @angular/compiler                 | 19.1.3 | 18.2.13 | 17.3.12 | 16.2.12 | 15.2.10 | 14.3.0  | 13.3.12  | 12.2.17  |
| @angular/core                     | 19.1.3 | 18.2.13 | 17.3.12 | 16.2.12 | 15.2.10 | 14.3.0  | 13.3.12  | 12.2.17  |
| @angular/forms                    | 19.1.3 | 18.2.13 | 17.3.12 | 16.2.12 | 15.2.10 | 14.3.0  | 13.3.12  | 12.2.17  |
| @angular/platform-browser-dynamic | 19.1.3 | 18.2.13 | 17.3.12 | 16.2.12 | 15.2.10 | 14.3.0  | 13.3.12  | 12.2.17  |
| @angular/platform-browser         | 19.1.3 | 18.2.13 | 17.3.12 | 16.2.12 | 15.2.10 | 14.3.0  | 13.3.12  | 12.2.17  |
| @angular/router                   | 19.1.3 | 18.2.13 | 17.3.12 | 16.2.12 | 15.2.10 | 14.3.0  | 13.3.12  | 12.2.17  |
|                                   |        |         |         |         |         |         |          |          |
| @types/jasmine                    | 5.1.5  | 5.1.5   | 5.1.5   | 4.3.6   | 4.3.6   | 4.0.3   | 3.10.18  | 3.8.2    |
| jasmine-core                      | 5.5.0  | 5.2.0   | 5.1.2   | 4.6.1   | 4.5.0   | 4.3.0   | 4.0.1    | 3.8.0    |
|                                   |        |         |         |         |         |         |          |          |
| karma-chrome-launcher             | 3.2.0  | 3.2.0   | 3.2.0   | 3.2.0   | 3.1.1   | 3.1.1   | 3.1.1    | 3.1.1    |
| karma-coverage                    | 2.2.1  | 2.2.1   | 2.2.1   | 2.2.1   | 2.2.1   | 2.2.1   | 2.2.1    | 2.0.3    |
| karma-jasmine-html-reporter       | 2.1.0  | 2.1.0   | 2.1.0   | 2.1.0   | 2.0.0   | 2.0.0   | 1.7.0    | 1.7.0    |
| karma-jasmine                     | 5.1.0  | 5.1.0   | 5.1.0   | 5.1.0   | 5.1.0   | 5.1.0   | 4.0.2    | 4.0.2    |
| karma                             | 6.4.4  | 6.4.4   | 6.4.4   | 6.4.4   | 6.4.4   | 6.4.4   | 6.3.20   | 6.3.20   |
|                                   |        |         |         |         |         |         |          |          |
| rxjs                              | 7.8.1  | 7.8.1   | 7.8.1   | 7.8.1   | 7.8.1   | 7.5.7   | 7.5.7    | 6.6.7    |
|                                   |        |         |         |         |         |         |          |          |
| tslib                             | 2.8.1  | 2.8.1   | 2.8.1   | 2.7.0   | 2.8.1   | 2.8.1   | 2.8.1    | 2.8.1    |
| typescript                        | 5.7.3  | 5.5.4   | 5.4.5   | 5.1.6   | 4.9.5   | 4.7.4   | 4.6.4    | 4.3.5    |
|                                   |        |         |         |         |         |         |          |          |
| zone.js                           | 0.15.0 | 0.14.10 | 0.14.10 | 0.13.3  | 0.12.0  | 0.11.8  | 0.11.8   | 0.11.8   |
|                                   |        |         |         |         |         |         |          |          |
| @types/node                       |        |         |         |         |         |         | 12.20.55 | 12.20.55 |
