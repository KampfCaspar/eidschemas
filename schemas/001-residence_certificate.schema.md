| name                    | type                           | cardinality | title                                     | description                       |
|-------------------------|--------------------------------|-------------|-------------------------------------------|-----------------------------------|
| version                 | [Version](../types/Version.md) | 1           |                                           |                                   |
| creationDate            | date                           | 1           | Issuance Date                             | Date of Issuance                  |
| authority               | string                         | 1           | Issuing Authority                         | Authority issuing the certificate |
| familyName              | string                         | 1           | Surname of Subject                        |                                   |
| givenName               | string                         | n           | Given Names of Subject                    |                                   |
| birthdate               | date                           | 1           | Birthdate of Subject                      |                                   |
| placeOfOrigin           | string                         | n           | Place of Origin of Subject in Switzerland |                                   |
| nationality             | ISO3166                        | 1           | Nationality of Subject                    |                                   |
| address.streetAddress   | string                         | 1           |                                           |                                   |
| address.postalCode      | PLZ                            | 1           |                                           |                                   |
| address.addressLocality | string                         | 1           |                                           |                                   |
| residentSince           | date                           | 1           |                                           |                                   |
| arrivalFrom             | string                         | 0..1        |                                           |                                   |
| departureSince          | date                           | 0..1        |                                           |                                   |
| departureTo             | string                         | 0..1        |                                           |                                   |
| cityName                | string                         | 1           |                                           |                                   |
| cantonRegistryNumber    | int                            | 1           |                                           |                                   |
| cantonCode              | [Canton](../types/Canton.md)   | 1           |                                           |                                   |
| requestor               | string                         | 0..1        |                                           |                                   |
| purpose                 | string                         | 0..1        |                                           |                                   |
