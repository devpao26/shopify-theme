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


![Screenshot 2025-01-30 at 11 42 01 AM](https://github.com/user-attachments/assets/b6d04928-8d29-4ea0-a6cd-5dea7f0bffa6)
![Screenshot 2025-01-30 at 5 30 13 PM](https://github.com/user-attachments/assets/7eb2d341-4819-42d0-87bb-91173c2bd071)
![Screenshot 2025-01-30 at 5 30 47 PM](https://github.com/user-attachments/assets/10aa7c62-4f88-447e-b534-03eb322413e9)
![Screenshot 2025-01-30 at 5 31 34 PM](https://github.com/user-attachments/assets/d36dda3e-a9c7-4bf3-8879-eb2396f002e8)
![Screenshot 2025-01-30 at 5 31 46 PM](https://github.com/user-attachments/assets/ca262626-0cb6-499d-94a7-7eb82bfa017d)









