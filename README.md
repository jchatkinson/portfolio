When you deploy your application files, your website will be uploaded to App Engine. To deploy your app, run the following command from within the root directory of your application where the app.yaml file is located:

gcloud app deploy

Optional flags:

Include the --project flag to specify an alternate Cloud Platform Console project ID to what you initialized as the default in the gcloud tool. Example: --project [YOUR_PROJECT_ID]
Include the -v flag to specify a version ID, otherwise one is generated for you. Example: -v [YOUR_VERSION_ID]

To launch your browser and view the app at http://[YOUR_PROJECT_ID].appspot.com, run the following command:

gcloud app browse