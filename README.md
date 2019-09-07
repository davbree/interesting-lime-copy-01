# Stackbit Ampersand Theme

This site was generated by [www.stackbit.com](https://www.stackbit.com), v0.2.61.

Stackbit Ampersand Theme original README is located [here](./README.theme.md).

The content of this site is managed by Forestry. Visit [https://forestry.io](https://forestry.io) to manage site content.

# Running Your Site Locally

1. [Install Hugo](https://gohugo.io/getting-started/quick-start/#step-1-install-hugo)

1. get "netlify-api-key" from project menu in [Stackbit dashboard](https://app.stackbit.com/dashboard)

1. run the following command to assign this key to `STACKBIT_API_KEY` environment variable:

        export STACKBIT_API_KEY={stackbit_netlify_api_key}

1. run the following command to fetch additional site contents from Stackbit if needed:

        npx @stackbit/stackbit-pull --stackbit-pull-api-url=https://e299b818.ngrok.io/pull/5d733bfcf0d34b07c0647003

1. Build the site and start the Hugo server with drafts enabled

        hugo server -D

1. Browse to [http://localhost:1313/](http://localhost:1313/)
