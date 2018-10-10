Protobuf3 type declarations for the Helm API
--------------------------------------------

Packages

 - `hapi.chart` Complete serialization of Heml charts
 - `hapi.release` Information about installed charts (Releases) such as metadata about when they were installed, their status, and how they were configured.
 - `hapi.rudder` Definition for the ReleaseModuleService used by Tiller to manipulate releases on a given node
 - `hapi.tiller` Definition of the ReleaseService provoded by Tiller and used by Helm clients to manipulate releases cluster wide.
