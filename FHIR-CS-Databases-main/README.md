# FHIR-CS-Databases Info

This is an example C# WebApi project used to explore modeling choices when storing FHIR data.

# Documentation
# FHIR and Databases - Web API

This repository contains the source code for a FHIR Server implementation using .NET 6. It is being built as part of a tutorial series focusing on server-side FHIR development and database modeling decisions.

## Project Status
Currently, this project implements the basic Web API skeleton for a FHIR server, including:

* **Framework:** .NET 6 Web API
* **SDK:** `Hl7.Fhir.Net` (Firely SDK)
* **Endpoints:** Basic routing setup for standard FHIR interactions:
    * `Instance Read` (GET)
    * `Instance Update/Create` (PUT)
    * `Instance Delete` (DELETE)
    * `Type Search` (GET/POST)
    * `Capability Statement` (metadata)

## Getting Started
1.  Clone the repository.
2.  Run `dotnet restore` to install the `Hl7.Fhir.Net` NuGet package.
3.  Run `dotnet run` to launch the API.
4.  Navigate to the root URL to view the Swagger/OpenAPI documentation.

## Context
Based on the "FHIR and Databases" video series by Gino Canessa.

## More Information


FHIR&reg; is the registered trademark of HL7 and is used with the permission of HL7. 