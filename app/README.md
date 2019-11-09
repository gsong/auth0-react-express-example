# React Client

Follow along step-by-step at <https://auth0.com/docs/quickstart/spa/react>.

## Where do I find the values for `auth_config.json`?

Log into your Auth0 account.

### `domain` and `clientId`

1. Click on "Applications."
1. Click on the application that you created in the tutorial.
1. Copy and paste from "Domain" and "Client ID":
   ![Screenshot showing application detail](../docs/auth_config_01.png)

### `audience`

1. Click on "APIs."
1. Copy "API Audience" from the API that you created:
   ![Screenshot showing application detail](../docs/auth_config_02.png)

References:

- `react-auth0-spa.js` uses React context, see
  <https://reactjs.org/docs/context.html> for more info.
