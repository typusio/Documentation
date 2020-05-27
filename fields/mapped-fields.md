# 🗺️ Mapped fields

Mapped fields are found under the General section of the Settings tab. They allow you to map the names of the fields specified in the `name` attributes on your form to the names of the fields displayed on Typus. This can be very useful when your app has obfuscated attributes, or when you don't want to reveal the names of the fields so bots can't put in fake data.

To configure them, go to the General section of the Settings tab and enter the fields and mappings you want to be hidden, separated by a colon, separated by commas. For example, if you enter `hj67:name, 6sgh2:message` then the `hj67` field from your form will be displayed as `name` on Typus, and the `6sgh2` field on your form will be displayed as `message`.

