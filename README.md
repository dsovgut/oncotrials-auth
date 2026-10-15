# oncotrials-auth

A static redirect page for a personal patient-facing FHIR app (SMART on FHIR standalone launch).
`callback.html` receives the one-time authorization code from the patient portal and forwards it to a
program on the user's own computer (`http://localhost:8765/callback`). No data is stored or sent anywhere else.
