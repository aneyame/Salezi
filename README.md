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

Fnac manager token :
8bc88d34c856152bb8faad9ac13c3b9e37fe30f90b0bd0acdae093a8f34435ae9f821ff3edf1cc499c351aeb6b50f93c8e8fbb60ce804faf7afd208868a5f588bc02c648516a349897214d4ec3b2f69e9f01acf0e434dd0af252d4df9f6d2659a0a150be68f51094cf6dc17686f12bbc827d49598d4a7bb1a45b1e1b8e79fdbf

Super Admin token :
34c7257e93f02be8ae13b1095041214286b043cec411d29ff9ddfdbd662cf6e5c6dff9f06d600915694f83a76314884a3a8ab0cb0a51b73a85535d2faf548c2ec8fc3323eaad603389a3cd56d1a8db881841f6a63c4810ff33021f40e028aa17d981514e5e1382b978673ef46c131069cd338dd6613b4e0b16db9d2e8bcf9487

Seller token :
dd06ac0e6586dd372a6b708b75335b988ef1089b528c540bfe63ff2583479aebf505f1f5f6b1c87d9d987c5cdef792dd4e48e9cd6f47c72b995015e2420177c981200bba4ba27ab99edef8075ceb1587e8f13e585b6a586ab89435ee48cc1a7f3490d4d203a04c400f9b4cff169a68a98d23847cf27f82431787113249416fc6
