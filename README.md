# Salezi

## Roles & Permissions 
- Super Admin :
  - Has full access to all features and functionalities.
  - Has an access to the Admin Panel.
  
- Fnac Manager : 
  - Can view and edit all data.
  - Has the authority to validate transactions initiated by sellers.
  - Has an access to the Admin Panel.

- Seller :
  - Can view and edit only their own products.
  - Can request new transactions.
  - Cannot access the Admin Panel.

## Collections
- Products : informations about books, CDs and electronics
- Users : Super Admin, Fnac Manager and Seller

## Getting started
- Clone the repository from GitHub
- Install dependencies
```sh
npm install
```
- Set up the SQLite database.
```sh
npm run setup
```
- Launch the Strapi server.
```sh
npm run develop
```
- Access the API at http://localhost:1337.
