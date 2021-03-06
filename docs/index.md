# Welcome to TriggerMesh's Documentation

Couple steps are needed before you get productive

## Sign-up

1. Sign up for the Early Access Program [here](https://triggermesh.com/serverless_eap/).

2. Go to [https://cloud.triggermesh.io](https://cloud.triggermesh.io), click on the log-in button at the top right of the page and choose your favorite identity provider.

![login page](./images/tmlogin.png)

You are ready to use the TriggerMesh console shown just below.

![console view](./images/tmconsole.png)

If you want to use our command line client keep reading...

## For CLI lovers

If you would prefer to use a CLI, we have prepared `tm` for you.

`tm` is a generic Knative client with some added features to deploy functions from source. You can download `tm` by following our [instructions](https://docs.triggermesh.io/tm/install)

For examnple you will be able to bypass the console and do something like this:

```
tm deploy service hello --from-image=gcr.io/cloudrun/hello
```
