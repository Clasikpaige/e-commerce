[![open source project](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fvercel%2Fcommerce&project-name=commerce&repo-name=commerce&demo-title=Next.js%20Commerce&demo-description=An%20all-in-one%20starter%20kit%20for%20high-performance%20e-commerce%20sites.&demo-url=https%3A%2F%2Fdemo.vercel.store&demo-image=https%3A%2F%2Fbigcommerce-demo-asset-ksvtgfvnd.vercel.app%2Fbigcommerce.png&integration-ids=oac_MuWZiE4jtmQ2ejZQaQ7ncuDT,oac_9HSKtXld74NG0srzdxSiBGty&skippable-integrations=1&root-directory=site&build-command=cd%20..%20%26%26%20yarn%20build)

# 24luxuri Commerce

Building high-performance e-commerce sites. With a few clicks.













- cart
- search
- wishlist
- customerAuth
- customCheckout

#### How to turn Features on and off

> NOTE: The selected provider should support the feature that you are toggling. (This means that you can't turn wishlist on if the provider doesn't support this functionality out the box)

- Open `site/commerce.config.json`
- You'll see a config file like this:
  ```json
  {
    "features": {
      "wishlist": false,
      "customCheckout": true
    }
  }
  ```
- Turn `wishlist` on by setting `wishlist` to `true`.
- Run the app and the wishlist functionality should be back on.

### How to create a new provider

Follow our docs for [Adding a new Commerce Provider](packages/commerce/new-provider.md).

If you succeeded building a provider, submit a PR with a valid demo and we'll review it asap.

## Contribute


## Work in progress


People actively working on this project: @clasikpaige

