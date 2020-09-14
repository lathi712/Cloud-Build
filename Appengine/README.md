Cloud Build

1. Step Deploy the sample app using
gcloud app deploy app.yaml

Create a trigger
https://console.cloud.google.com/cloud-build/triggers?_ga=2.28946108.1489868234.1599958411-449237932.1599358021&_gac=1.36375572.1599358022.EAIaIQobChMIuOT087jT6wIVYRitBh1pmAA6EAAYASAAEgLmbfD_BwE

In the Name field, type app-engine-test.
Under Event, select Push to a branch.
Under Source, select hello-world as your Repository and ^master$ as your Branch.
Under Build configuration, select Cloud Build configuration file.
In the Cloud Build configuration file location field, type cloudbuild.yaml after the /.