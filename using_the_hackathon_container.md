# Using the Hackathon Container

We've created an F2 container for Hackathon participants to use for quickly deploying their apps.

[http://demo.markitqa.com/Hackathon](http://demo.markitqa.com/Hackathon)

## Registering Your Apps

To view your apps on the Hackathon container, you need to register them in the new Developer Center.

[http://developer-openf2.markitqa.com](http://developer-openf2.markitqa.com)

### Existing Accounts

If you have an existing F2 Developer Account from [developer.openf2.org](https://developer.openf2.org), you should use [Forgot Password](http://developer-openf2.markitqa.com/Account/Forgot) to get a new password for the new Developer Center. _This will not affect your production F2 Developer account._

### New Accounts

Simply follow the steps to [Sign up](http://developer-openf2.markitqa.com/Account/Create) for a new Developer Center account using your primary email address. 

### Apps

The first step in registering a new app is creating a unique AppID. This AppID will be unique to your app across the entire open financial framework ecosystem.

Go to [Manage Your Containers & Apps](http://developer-openf2.markitqa.com/Manage) to register a new app.

**Note:** Remember to provide a `ManifestURL` using the **Production field on Step 3**. Doing so will automatically link your app(s) with the [Hackathon container](http://demo.markitqa.com/Hackathon).

### Viewing Apps

**Log in** to the Hackathon container using your new Developer Center credentials.

[http://demo.markitqa.com/Hackathon/Auth](http://demo.markitqa.com/Hackathon/Auth)

The container will make a request to the F2 Registry APIs and pull in all of your apps _(as long as the `ManifestURL` is provided)_.

