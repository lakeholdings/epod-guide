# EPOD Merchant Getting Started Guide

Epic Print on Demand is a Print On Demand Platform to offer Epic Print products for sale.

if you are an Epic Print employee and are looking for [Catalog Administration Guide](./docs/catalog-guide.md)

## Signing up

The fist step in using EPOD is going to be signing up for a Merchant Account. Visit [internal.epicprint.dev/app/merchant](https://internal.epicprint.dev/app/merchant) and click "create an account". Or sign in if you already have a merchant account.

## Installation

After you signup for a merchant account use this link to install EPOD onto your shopify store. **You must be signed in before you can use the install link!**

[Installation Link](https://admin.shopify.com/oauth/install_custom_app?client_id=2c08e9a2b731b436f1b368ae7faf2145&signature=eyJfcmFpbHMiOnsibWVzc2FnZSI6ImV5SmxlSEJwY21WelgyRjBJam94TmprMU5EazBNemN4TENKd1pYSnRZVzVsYm5SZlpHOXRZV2x1SWpvaVpYQnBZeTF3Y21sdWRDMTNhRzlzWlhOaGJHVXViWGx6YUc5d2FXWjVMbU52YlNJc0ltTnNhV1Z1ZEY5cFpDSTZJakpqTURobE9XRXlZamN6TVdJME16Wm1NV0l6TmpoaFpUZG1ZV1l5TVRRMUlpd2ljSFZ5Y0c5elpTSTZJbU4xYzNSdmJWOWhjSEFpTENKdFpYSmphR0Z1ZEY5dmNtZGhibWw2WVhScGIyNWZhV1FpT2pFd016VTFNRFY5IiwiZXhwIjoiMjAyMy0wOS0zMFQxODozOTozMS40NDhaIiwicHVyIjpudWxsfX0%3D--9fd376502acb13905994ca80305502f0664f3e04)

This installation link expires from time to time, so if you have any issues reach out to the Devhouze team for a new link.

### Adding EPOD elements to your Shopify store

After you have successfully installed the app you will be directed to a shopify. You will need to add our App Blocks to your storefront in order to surface EPOD products and Cart to your customers.

To do so follow these steps or [watch our video](./videos/installation.mov)

1. Click customize on the online store tab.
   ![Customize your store](../images/customize.png)
2. Select your product page from the dropdown.
   ![Open Product Template](../images/select-product-template.gif)
3. Add the Product Builder App Block to your Product Page.
   ![Add Builder](../images/add-builder.gif)
4. Visit the cart page to add the Cart app block
   ![Add Cart](../images/add-cart.gif)
5. Enable the Cart Watcher App Embed so that your cart icon displays the correct number of products in the cart.
   ![Add Cart Watcher](../images/add-cart-watcher.gif)

And you are all done with the installation! Next up we will learn how to list a product.

## Adding a Product to your Merchant account

Now that you have EPOD installed on your merchant store, let's select a product form the catalog and list it on our store!

Follow along with these steps, or [watch our video](./videos/list-mug.mov)

1. Visit the [Products Page](https://internal.epicprint.dev/app/merchant/products) to select a product to add to your account. Click the Browse Catalog button and then select from the list presented. For this Demo we are going to choose "mug" from the catalog. If you need to go ahead and search for it.
   ![Add Mug](../images/add-mug.gif)
2. Click on the product you just added. Here you can manage Title, Description, Variants, and Listings. We are only interested in listing the product here so click on the + Listing button near the bottom.
   ![Add To Store](../images/add-to-store.png)
3. Now the last thing to do is to click "publish"
   ![Publish](../images/publish.png)

That's it! Now your mug product is listed in your shopify store. If you were to view that product on your storefront it should look like this!
![Mug on Store](../images/mug-on-store.png)

## Managing Scenes for Products

So far we've listed a product with the default scene that it has in the catalog. EPOD has very powerful scene editing that put you in complete control of how your customers build a customized product variant.

Scenes exist per variant, so if you would like to change a scene simply visit the product and then click on the variant you want to edit.

Follwo the steps below or [watch our video](./videos/scene-editing.mov)

1. Once on a variant page click "edit" on the scene you would like to change as shown below.
   ![Select Scene](../images/select-scene.png)
2. Now you are in the scene builder. For this example let's change the scene to be very basic. I'm going to change the scene so that it's only a blue background with a rectangular area for customers to upload images to. The steps will be to delete the scene, create a new scene with a blue background, then create a placment area as shown below.
   ![Blue Scene](../images/blue-scene-creation.gif)

Now that you've updated the scene, if you view the product on your store that vairant will display the scene you created. It will look like this
![Blue Scene Mug](../images/blue-scene-mug.png)

## Customer Orders

So far we've seen how to install EPOD, add the product builder and cart to the store, List products and modify scenes. Now we are going to go through placing an order as a customer. Everything should now work end to end. New orders will flow into Epic Prints fulfillment pipeline to be manufactured and shipped to your end customer.

Purchasing a product is as easy as uploading an image to the product and selecing add to cart. [watch our video](./videos/purchase-product.mov) or view the screenshot below.

![Add to Cart](../images/add-to-cart.gif)

![Checkout](../images/checkout.gif)

After a customer has purchased an order. Orders can be seen from the merchant dashboard or the orders page at [Orders Page](https://staging.epicprint.dev/app/merchant/orders/dashboard)
