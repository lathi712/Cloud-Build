Cloud Build

1. Step Deploy the sample app using
gcloud app deploy app.yaml

Create a trigger
https://console.cloud.google.com/cloud-build/triggers?_ga=2.28946108.1489868234.1599958411-449237932.1599358021&_gac=1.36375572.1599358022.EAIaIQobChMIuOT087jT6wIVYRitBh1pmAA6EAAYASAAEgLmbfD_BwE

1. In the Name field, type app-engine-test.<br/>
2. Under Event, select Push to a branch.<br/>
3. Under Source, select hello-world as your Repository and ^master$ as your Branch.<br/>
4. Under Build configuration, select Cloud Build configuration file.<br/>
5. In the Cloud Build configuration file location field, type cloudbuild.yaml after the /.<br/>
