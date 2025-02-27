## Material

Material is a product (final or intermediate) or an ingredient of a manufacturing process. 
Its attributes represent its current state. 
The state may be physically observed, for instance location, but also process-specific, for instance a result of quality control.

Example of a [PCB](https://en.wikipedia.org/wiki/Printed_circuit_board)
under manufacturing with the outcome of quality control 
is given below.

The concrete structure of the `status` attribute depends on 
a specific use case.  

```
{
    "id": "urn:ngsi-ld:Material:company-xyz:pcb-ncw498w",
    "type": "Material",
    "status": {
        "type": "Property",
        "value": {
            "qualityControlOutcome": "defective"
        },
        "observedAt": "2020-12-01T11:23:19Z"
    },
    "@context": [
        "https://smartdatamodels.org/context.jsonld"
    ]
}
```
