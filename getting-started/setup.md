# 🚀 Setup

You only need 2 things to get started with Typus. You need a plain, simple HTML form and a Typus account, which takes less then 5 seconds to setup. 

For this example, we'll use a very simple contact form as an example, with a `name` field and `message` textarea. 

```markup
<form>
        <label for="name">Name</label>
        <input type="text" id="name" name="name" />
        
        <label for="message">Message</label>
        <textarea type="text" id="message" name="message" />
        
        <button type="submit">Submit</button>
</form>
```

For the form to work, we need to point the `action` attribute to Typus. Let's do that!

First, create a form on Typus, and go to the **Setup** tab. 

![The setup tab is between the Submissions and Validation tabs.](../.gitbook/assets/image%20%285%29.png)

Then, copy the URL it gives you. It should look something like `https://api.typus.io/XXXX`. Put the link into the `action` attribute on your form, and set the `method` attribute to `POST`. Your form should look something like this:

```markup
<form method="POST" action="https://api.typus.io/XXXX">
        <label for="name">Name</label>
        <input type="text" id="name" name="name" />
        
        <label for="message">Message</label>
        <textarea type="text" id="message" name="message" />
        
        <button type="submit">Submit</button>
</form>
```

And that's it! You can start accepting submissions immediately. We will never delete or limit your submissions, unlike other form services. Keep reading to learn about our other powerful features, such as validation, confirmations, notifications, file uploads, and much more!

