# VersionOnePythonAPI
An API interface written for the application VersionOne

- You need an api key, stored as an environment variable. I called this variable vo_token, it is referenced in all the following scripts. You can get one by going to versionOne, than top right on the profile button and then Applications. There, create a new personal application, I have named mine curl
- You can look in [this link](https://agility.eu.airbus.corp/agility/meta.v1?xsl=api.xsl) to get all fields to all objects, necessary to create assets like stories or tests.
- [Official API docs](https://versionone.github.io/api-docs/)
- [API walkthrough](https://github.com/versionone/api-examples/blob/master/rest/apis-walkthrough.md): This is a bit more information on the docu. But it doesnt really help that much, as its only the first step.
- Tip: Give this query to chatgpt and it can help you with it (ensure that you paste NO ACTUAL DATA into your questions!! For my conversations I change airbus to company and use random data as title, team and so on)

```
You are to help me with calling an api endpoint from version one. I am creating curl commands to invoke actions on assets and more.
here are a few links, where you can read more on how the api works:
https://versionone.github.io/api-docs/#bulk-query
https://github.com/versionone/api-examples/blob/master/rest/apis-walkthrough.md

Say yes when you got this information
```

Then ask your questions or let it figure out the errors

