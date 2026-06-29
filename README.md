<h1>Will Registry - Coding Exercise</h1>
<h2>Overview</h2>

Build a web application that acts as a central registry for wills.

The purpose of the registry is to allow individuals to record where their will is located so that it can be discovered when required.

The registry does not require custodians to upload copies of wills, as they already maintain these within their own systems.

# Actors
Individual

An individual can:

- Register and log in.
- Create a will registry entry.
- Choose where their will is stored.
- Either:
  - Upload their own will (PDF), or
  - Select a registered custodian that holds the original will.
View and update their own registry information.

Custodian

A registered custodian (e.g. law firm, bank or trust company) can:

- Log in.
- View all individuals who have registered that the custodian holds their will.
- Search for individuals linked to their organisation.

Custodians cannot modify an individual's registry entry.

# Public Search

Anyone can search using:

- National ID Number
- Registry Reference Number

If a record exists, display:

- Person Name
- Registry Reference
- Will Location
- Registration Date

If the will was uploaded by the individual, indicate that the will is held by the individual.

If the will is held by a custodian, display the custodian's name.

The actual will document must never be publicly accessible.

# Functional Requirements

Authentication

- Register
- Login
- Logout

Individual Dashboard

- Create registry entry
- Upload PDF (optional)
- Select custodian (optional)
- Edit registry entry
- View current registry status

Exactly one of the following must be provided:

- Uploaded will
- Registered custodian

Custodian Dashboard

- View individuals linked to the custodian
- Search by ID number
- Search by reference number

Read-only access.

# Public Lookup

Search by:

- ID Number
- Registry Reference

Display:

- Will Found / Not Found
- Location
- Custodian (if applicable)
- Registration Date

Never expose the uploaded document.

# Notes

The application should focus on:

- Good architecture
- Authentication
- Authorization
- Data modelling
- Validation
- User experience

Candidates are encouraged to use an AI coding assistant during the exercise.
