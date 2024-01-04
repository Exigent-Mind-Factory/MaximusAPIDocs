# Project API

>Please take note that the Project workflows are still WIP
> {style="warning"}

> User needs to be a member of an <b>Organisation</b>
> to be able to interact with Projects
> {style="note"}

### List all Projects
<api-endpoint openapi-path="../../maximus_schema_1.10.json" endpoint="/projects" method="GET"/>


### Create a Project
<api-endpoint openapi-path="../../maximus_schema_1.10.json" endpoint="/projects/" method="POST"/>


### Update a Project
>Note that Many Teams can be assigned to Many Projects
> {style="tip"}
<api-endpoint openapi-path="../../maximus_schema_1.10.json" endpoint="/projects/{id}/" method="PATCH"/>
<api-endpoint openapi-path="../../maximus_schema_1.10.json" endpoint="/projects/{id}/" method="PUT"/>


### Delete a Project

>This is not a SOFT DELETE. Deletion of a project will result in the removal of
> all documents associated with the project. 
> {style="warning"}

<api-endpoint openapi-path="../../maximus_schema_1.10.json" endpoint="/projects/{id}/" method="DELETE"/>