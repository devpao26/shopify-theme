# shopify-theme

# USING CLI: 
# Install Shopify CLI:

First, install the Shopify CLI to manage your store and themes locally.

- Using sh Run `npm install -g @shopify/cli`

Check if installed correctly, 

- Run `shopify version`

# Authenticate and Log In

Run `shopify login --store ipz00m-f4.myshopify.com` or your store name.

Once autheticated and logged in, it will be displayed in the browser.

# Clone the Shopify Theme

Run `git clone https://github.com/devpao26/shopify-theme.git` 

Or alternatively download an existing theme from shopify store: 

Run `shopify theme pull --store ipz00m-f4.myshopify.com`

# Start the local development server

- Run `shopify theme dev`


If want changes on section

- Navigate to the theme's code directory:

Run `cd shopify-theme`

- Add the featured-collection.liquid file to the /sections/ folder.

- Push Changes Back to Shopify
* If you made local changes and want to upload them:

Run `shopify theme push` - this will sync local theme with shopify.

- Pull Changes back to Local Editor
* If you want to sync changes from latest and prevent conflict. 

Run `shopify theme pull` - this will ensure your local is up-to-date with the store.

#  Verify in the Shopify Admin Panel
- Go to Online Store > Themes > Customize.
- Add the Featured Collection section.
- Customize and save.

Here is the working screenshots for referrence: 

Screenshot 2025-01-30 at 5.31.46 PM.png
Screenshot 2025-01-30 at 5.31.34 PM.png
Screenshot 2025-01-30 at 5.30.47 PM.png
Screenshot 2025-01-30 at 5.30.13 PM.png
Screenshot 2025-01-30 at 11.42.01 AM.png









