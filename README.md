# JosesBeerRandomizer
A short hands-on introduction to Azure Functions. Forget the "Hello World!". Let's write something useful and **critical** instead!

## Blog post

You can find the blog post at
[Build Your First Azure Function in Visual Studio Code](https://developer.okta.com/blog/2019/02/07/build-your-first-azure-function-visual-studio-code)

## Before running this

You **must** get an API Key for BreweryDB.

1. Go to [BreweryDB](https://www.brewerydb.com/).
2. Create account
3. Choose **Developers** and **My API Keys** from the main menu. 
4. Copy the **Sandbox Key** as you’ll be using the sandbox (meaning free) tier. 

The original blog post has more details on this if needed.

## Running locally

**Get your API key for BreweryDB first**

1. Clone repo
2. Open in Visual Studio Code
3. Find and replace the code in the `local.settings.json` for `"BREWERY_DB_API_KEY": "YOUR_BREWERY_DB_API_KEY_GOES_HERE"` with your API key.
4. Press `F5`
5. Ctrl + click on url in console
6. What beer did you get? :)

## Next step - deploy to Azure! 

Follow the blog post and deploy it to Azure. 

Why should such an useful assistant should remain in your local machine? Share it with the world.
