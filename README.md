<h1 align = "center">Persona 5 Database</h1>

<p align = "center"><b>Overview</b>: A Companion Database to search though the Persona 5 main characters, their main personas, and the persona's main strengths and weaknesses. </p>

  <img align = "center" src="/readme-images/pg-Admin-ex-persona-table.JPG" alt="pgAdmin Persona Table view">

------------

## Installation

To run this via the repo:

Prerequisties: A local .env file with the following criteria:

```bash
PORT = "yourlocalportno"
DB_CONNECTION_STRING = "EnterYourDBConnectionStringHere"
```

Then inside your VScode terminal, enter the following:

```bash
    npm i
    npm run dev
```

## The Brief

At School of Code, our team was challenged to implement, and deploy an API using a managed PostgreSQL database hosted with a third-party provider. We had to provide that functional MVP within 2 days.

<i>Note: We utilised Render with it's free trial, which expired on 10/02/25.</i>

<h2>Documentation</h2>

<h3><u>MVP</u></h3>

- Seed the two Tables: Main characters and Personas
- TABLE 1: Character Name, Pseudoname, Main Persona
- TABLE 2: Personas, Strengths (array), Weaknesses (array)
- Get the CR from CRUD functionality inc Error handling

  <img align = "center" src="/readme-images/API_FETCH_Table.JPG" alt="P5 API Fetch Table">

- Ensure there is a Primary Key and a Foreign Key relationship between the two tables:

  <img align = "center" src="/readme-images/Showing_primary_key_and_foreign_key_in_constraints.JPG" alt="PK & FK">


## Future Milestones

<h3><u>MS2</u></h3>

- Add an Images Column
- More Persona focused data columns, ie Arcanas and Move Sets
- Split Tables into more suitably distributed data (ie split Strengths into Resist/Block/Absorb/Reflect)

## Authors

Created by Team: 4Real 
<i>aka Hannalysis and Menice4</i>
