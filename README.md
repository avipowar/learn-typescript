## ways to setup Typescript

# setup globally
    - tsc --init => tsconfig.json banata hai => Project settings control karta hai (TypeScript ke rules set karne wali file banana)
    - npm i -g typescript
    - tsc -v (check version)
    - touch index.ts  (create file) 
    - tsc index.ts (index.js file generate karega)
    - node index.js 

# setup locally
    - npm init -y => (create package.json file )
    - npm i -D typescript => (install in project for development)
    - npx tsc --init (create tsconfig.json file)
    - create src/index.ts file
    - npx tsc  => (compile ts => js => create js file)
    - node src/index.js (run the js file)
    - declaration: false => extra files avoid (clean project)
    - sourceMap: true => debugging easy (show ts file error not js file)

# setup using vite 
    - npm create vite@latest my-ts-app
    - npm install
    - npm run dev
    - npm run build
    - Development (npm run dev) → No JS files (fast, in-memory)
    - Production (npm run build) → JS files created (optimized)
    