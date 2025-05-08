# nextjs-template

## install
```bash
yarn
```

## start dev
```
yarn dev
```

## build application
```bash
yarn build
```

## rules

**!!!Do not use empty tag `<></>`, it's will panic browser translation**


### project structure

Reference to [nextjs project structure](https://nextjs.org/docs/app/getting-started/project-structure) 


### library

Use `tailwind` for styling

### configuration

Use `public/config.json` as the single source of configuration

> Note: `config.json` is just a template. The server will replace it with the actual configuration from the server side.

### package manager

Use yarn as package manager, make sure yarn.lock is working great, server side will build project via yarn.

### Code Size Guidelines  

**Components**
- Recommended: ≤200 lines  
- Hard limit: ≤300 lines  
- Exceeding: Consider splitting it into subcomponents or extracting logic into custom Hooks/Libs.

**Hooks**  
- Recommended: ≤200 lines  
- Hard limit: ≤300 lines  
- Exceeding: Modularize logic into separate methods  

**Libs**
- Recommended: ≤500 lines  
- Hard limit: ≤700 lines  
- Exceeding: Split into separate files

**Functions** 
- Maximum: 50 lines  
- Exceeding: Split into smaller functions
