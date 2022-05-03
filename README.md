# Gravitate Health Focusing interfaces

In [Gravitate Health Focusing](gravitate-health-focusing-interface-oapi.yml) you can find the current interface to be used in order to implement the focusing in the Medication Information model.

It contains a single POST method, which will be invoked by the G-Lens service and will send a Bundle consisting of two items:
- An optional IPS 
- A Medication Information object ([FHIR compliant](https://www.hl7.org/fhir/medication.html))

The response of the call must contain the same Bundle and the focused Bundle.
