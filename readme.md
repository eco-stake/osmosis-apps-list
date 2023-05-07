# Osmosis Apps List

## Adding Your Application
To add your application to the list, simply create a pull request to this repository that includes your application object added to the end of the applications array in the applications.json file. Your application object should include values for all the required properties. Once your pull request is merged, your application will be added to the list!

## Application Properties
Here are the properties that can be included in your application object:

 - title (required): The title of your application.
 - subtitle (required): A brief description or tagline for your application.
 - external_URL (required): The URL to the external site of your application.
 - image_URL (required): The URL of an image to display for your application.
 - hero_image_URL (required): The URL of a larger hero image to display for your application.
 - twitter_URL (optional): The URL of your application's Twitter account.
 - medium_URL (optional): The URL of your application's Medium account.
 - github_URL (optional): The URL of your application's GitHub repository.
 - featured (optional): A boolean value indicating whether your application should be featured.

## Example Application Object
Here's an example of what your application object should look like:
```
{
  "title": "My Awesome App",
  "subtitle": "A brief description of my app",
  "external_URL": "https://my-awesome-app.com",
  "image_URL": "https://my-awesome-app.com/image.jpg",
  "hero_image_URL": "https://my-awesome-app.com/hero-image.jpg",
  "twitter_URL": "https://twitter.com/my-awesome-app",
  "medium_URL": "https://medium.com/my-awesome-app",
  "github_URL": "https://github.com/my-awesome-app/my-awesome-app",
  "featured": false
}
```