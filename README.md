
## OpenBook  - E-Commerce Book Selling Progressive Web App


#### `How to run locally?`

```bash
1. git clone https://github.com/MasterKN48/OpenBook-E-Commerce
2. cd OpenBook-E-Commerce
3. npm i
4. cd client 
5. npm i
6. cd ..
# to run server the project must have .env file in root project directory
# see below .env file structure
7. npm run dev
# project started

```


#### `.env structure`

```bash
MONGO_URI=<MONGO_DB_SERVER>
NODE_ENV=production  # `production` or `dev`
CLIENT_URL=<REACT_APP_SERVER>
PORT=8000
BRAINTREE_ID=<BRAINTREE_SANDBOX_ID>
BRAINTREE_PRIVATE=<BRAINTREE_SANDBOX_PRIVATE_ID>
BRAINTREE_PUBLIC=<BRAINTREE_SANDBOX_PUBLIC_ID>
JWT=<JWT_SECRET>
```

#todo - payment gateway integration, bug-fix in React-UI
