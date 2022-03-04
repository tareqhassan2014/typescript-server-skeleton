### 1) Initialize a git repository

```ch
git init
```

### 2) Initialize node

```ch
npm init -y
```

### 3) initialize typescript

```ch
npx tsc --init
```

### 4) Make directories

```ch
mkdir src src/library src/middleware src/resources src/resources/auth src/resources/product src/utility
```

### 5) Make files

```ch
touch .gitignore types.d.ts .env .env.example src/app.ts src/service.ts src/library/jwt.ts src/middleware/error.ts src/resources/ src/resources/auth/auth.model.ts src/resources/auth/auth.controller.ts src/resources/auth/auth.service.ts src/resources/product/product.model.ts src/resources/product/product.controller.ts src/resources/product/product.service.ts src/utility/responseGenerator.ts
```

### 6) Add dependance

```ch
yarn add express dotenv mongoose helmet morgan cors compression  jsonwebtoken bcrypt
```

### 7) Add dev dependence

```ch
yarn add -D typescript nodemon ts-node @types/express @types/node @types/dotenv @types/compression @types/cors @types/morgan @types/helmet @types/jsonwebtoken @types/bcrypt
```

### 8) Alternate all in all command

```ch
git init
npm init -y
mkdir src src/library src/middleware src/resources src/resources/auth src/resources/product src/utility
npx tsc --init
touch .gitignore types.d.ts .env .env.example src/app.ts src/service.ts src/library/jwt.ts src/middleware/error.ts src/resources/ src/resources/auth/auth.model.ts src/resources/auth/auth.controller.ts src/resources/auth/auth.service.ts src/resources/product/product.model.ts src/resources/product/product.controller.ts src/resources/product/product.service.ts src/utility/responseGenerator.ts
yarn add express dotenv mongoose helmet morgan cors compression  jsonwebtoken bcrypt
yarn add -D typescript nodemon ts-node @types/express @types/node @types/dotenv @types/compression @types/cors @types/morgan @types/helmet @types/jsonwebtoken @types/bcrypt
git init
```
# typescript-server-skeleton
