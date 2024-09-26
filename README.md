# Plotting scripts for Bendall and Kent SWIFT paper
Repository for plotting scripts used for the Bendall &amp; Kent 2024 paper: SWIFT: A Monotonic, Flux-Form Semi-Lagrangian Tracer Transport Scheme for Flow with Large Courant Numbers

The data used for results in the paper were produced with the LFRic-Atmosphere
model, which is stored in the LFRic-Applications repository. The LFRic-Atmosphere source code and configuration files are freely available from the Met Office Science Repository Service
(https://code.metoffice.gov.uk) upon registration and completion of a software licence.

The branch and revision used to create the data in the paper is found at the path
```
fcm:lfric_apps.x-br/dev/jameskent/r3513_swift_revision@3903
```

The tests specifically used for the results in the paper can be found by running the
`transport_swift` group.

The plotting scripts held in this repository make use of the `tomplot` plotting
library, which can be accessed here: [https://github.com/tommbendall/tomplot]
