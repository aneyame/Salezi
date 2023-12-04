# Salezi

## Description

Salezi is an API developped by Cloudy which offers an interface to manage the stocks and sales of products for each of our partner sellers.

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
npm run strapi develop
```
- Access the API at http://localhost:1337
- Use these logins :

email : `candice.caussade@epitech.digital`

password : `Jesaispas123`

## Endpoints
[Here](http://localhost:1337/documentation/v1.0.0#/) you can access the endpoints of the API 
Or directly from the Strapi admin dashboard : Plugins -> Documentation


## Roles & Permissions 
- Super Admin :
  - Has full access to all features and functionalities.
  - Has an access to the Admin Panel.

- Fnac Manager : 
  - Can view and edit all data.
  - Has the authority to validate transactions initiated by sellers.
  - Has an access to the Admin Panel.
    
- Seller :
  - Can view all products but only edit their own products.
  - Can request new transactions.
  - Cannot access the Admin Panel.


# Grafana Dashboard - [Salezi | Fnac dashboard]

## Overview

This repository contains the JSON configuration for a Grafana dashboard aimed at the Fnac Manager. 
It provides information about the stocks of products per category, listed in the API.

## Prerequisites

- [Grafana](https://grafana.com/) installed and running.

## Installation

1. Clone this repository:

    ```bash
    git clone https://github.com/aneyame/Salezi.git
    cd salezi
    ```

2. Import the Grafana dashboard JSON file:
   - Open your Grafana instance in a web browser.
   - Navigate to the "+" menu on the left sidebar.
   - Select "Import."
   - Upload the `Salezi _ Fnac-dashboard.json` file from this repository.

3. Configure the data source:
   - In Grafana, navigate to the gear icon (⚙️) > "Data Sources".
   - Add or select the data source used by your dashboard (e.g., Prometheus).
   - Configure the necessary settings, such as URL and access.
  
