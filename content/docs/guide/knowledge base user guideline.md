---
title: KB user guideline (canceled)
weight: 2
---

## Overview

The OSC Knowledge Base Platform is a web-based application. The platform is for managing offsite construction (OSC) knowledge in the form of knowledge container. The application URI is XXX. This guideline is developed for general users who only use the service of the platform and knowledge managers who are responded to capture OSC knowledge content, construct and configure it into a knowledge unit, and upload the knowledge unit to the platform as a knowledge container.

![use_cases.png](../img/use_cases.png)

Each of these use cases are described in the following sections.

## General knowledge user’s guide

### Register

- Use “Register” button in the homepage to sign up.

![register.png](../img/register.png)

- To register you have to put in an email address, a username and a password.
The username has to be 150 characters or fewer using letters, digits and @/./+/-/_ only. The
password must have at least 8 characters and cannot be too similar to your other personal information. The password also cannot be a commonly used password or entirely numeric. Enter the same password as before, for verification.

![sign_up.png](../img/sign_up.png)

### Login

- After activating the account, you can log in using the username and password priorly chosen.
- Use “Log in” button to access the application.

![log_in.png](../img/log_in.png)

### Search knowledge

- Overview knowledge base content, e.g., case list (only knowledge manager can add, edit and delete these cases).

![case_list.png](../img/case_list.png)

- Use classification filter to clarify target OSC knowledge domains (function to be added).
- Enter queries to search and retrieve knowledge from the knowledge base.

![case_searching.png](../img/case_searching.png)

Currently, the system match target knowledge by using key words reasoning.

### Get knowledge response to use

- Check recommended knowledge in the response box.
- Select proper knowledge to use in specific project scenarios (e.g., calculate the functional design efficiency of an OSC product assembly).

![case_detials.png](../img/case_detials.png)

### Add and edit learning logs

Users can add and edit their own learning notes that can be private and public either, which means that users can choose to keep their knowledge items with themselves or open them to specific members or all users for knowledge sharing and collaboration. In addition, this may be transferred to as formal knowledge content in the knowledge base system.

- Use “Add a new entry” button to add a new learning log under specific topic.
- Use “Edit entry” button to make any change in existing learning logs.

![add_learning_log.png](../img/add_learning_log.png)

- Save changes after editing the knowledge entry.

![isave_learning_log.png](../img/save_learning_log.png)

- (Coming soon) Use “share” button to get knowledge open or collaborate with specific users.

### Logout

- Use “Logout” button to sign out.

![sign_out.png](../img/sign_out.png)

## Knowledge manager’s guide

The role of knowledge manager will be assigned by the super administrator after general registration. The knowledge managers can use all functions for general knowledge users for testing their knowledge management outcomes.

### Add document with knowledge content

Knowledge manager can add documents containing authorised knowledge contents, such as national standards, to this platform for further analysis so that these knowledge contents can be transferred or linked to usable knowledge unit.

- Upload authorised knowledge documents (e.g., standards, qualified handbook, etc.)
- Add or generate meta data to uploaded documents for knowledge matching and retrieval.

![upload_documents.png](../img/upload_documents.png)

### Parse and analyse the knowledge content

To further structuring the knowledge content into a knowledge unit, knowledge manager need to classify and re-organise knowledge content to cases for specific OSC problems.

- Add new cases

![add_cases.png](../img/add_cases.png)

- Edit existing cases

![edit_case.png](../img/edit_case.png)

- Delete existing cases

![delete_case.png](../img/delete_case.png)

### Model and configure knowledge unit (advanced usage)

This step is currently out of this platform and conducted in Protege, a free and open-source ontology development tool with various reasoning and visualising plugins.

- Refer to the guide [Ontology Development 101: A Guide to Creating Your First Ontology](https://protege.stanford.edu/publications/ontology_development/ontology101.pdf) to develop knowledge terminologies (concepts), attributes and properties.
- Develop constraint rules using [semantic web rule language (SWRL)](https://www.w3.org/submissions/SWRL/) for knowledge inference and [Shapes Constraint Language (SHACL)](https://www.w3.org/TR/shacl/) for compliance checking.

### Upload knowledge unit to the knowledge base (advanced usage)

This knowledge platform use Apache Jena Fuseki to manage RDF data and provide basic functions for adding triples and making SPARQL queries.

![rdf_database.png](../img/rdf_database.png)

![add_triples.png](../img/add_triples.png)

![rdf_query.png](../img/rdf_query.png)

![query_results.png](../img/query_results.png)

## Super Administrator’s guide

### Authentication and authorisation

SuperAdmin can set groups and users and their permissions.

![authorisation_group.png](../img/authorisation_group.png)

![authorisation_user.png](../img/authorisation_user.png)

### Application objects configuration

SuperAdmin can create and configure knowledge objects for the knowledge base.
![backend_configuration.png](../img/backend_configuration.png)