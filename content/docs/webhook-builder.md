---
Title: Webhook Builder
---

# Introduction
It's hard to balance making a tool easy to use but also feature rich and our webhook builder falls right into that so we're making this guide to try and make things simpler! Things are separated a lot so when looking for something specific, read the **big** text to find what you want!

## 1. Canvas Builder
Here is where you setup the messages that the bot sends. This is probably the most confusing part of the builder so here is a list of each option and what they do!

### 1.1 Layout & Structure
- **Containers:** This is the base of a embed! This is where you add differnt components like colors, messages, images, and more! Once you add at least one container, it will unlock the options to add content to the active container! The active container is determined by whichever one was last clicked on!

- **Separator / Spacer:** This options lets you add either a line or space between differnt containers or message content! This is not to be confused with the "Inner Separator" which goes *inside* containers.

### 1.2 Content & Inputs
- **Text Display:** This allows you to add another message field along with the main one! This means you could have a embed right in-between two or more message fields!

- **Button Row:** This allows you to add buttons at the *bottom* of your message and set a link for people to go too! This is not to be confused with the "Button Section" option for containers which lets you add buttons within containers.

### 1.3 Media & Attachments
- **Media Gallery:** This allows you to add multiple images to your message.

- **Attached File:** This allows you to attach a file to your message.

### 1.4 Container Elements
- **Title:** Adds a title to your embed (max of 1).

- **Description:** Give your message plain text. Can be more than one.

- **Accent Color Bar:** Adds color to the side of your message. Your message won't have any color bar if you don't include this field.

- **Field Component:** Give you a little bold heading and text below it as a component for your container.

- **Author Header:** This allows you to set an author name and avatar for a container. Can be differnt for separate containers.

- **Button Section:** Allows you to add buttons *within* the container.

- **Thumbnail Image:** Allows you to set the thumbnail (Small image) of that container.

- **Banner Image:** Allows you to set the banner (large image) of that container.

- **Inner Separator:** Allows you to put a separator (your choice between a line or a space) between components of your container.

- **Footer Note:** Give you the option to set the footer of the container.

- **Timestamp:** Allows you to configure a timestamp for your container.

## 2. Bot & Signals
- **Username:** Lets you override the username for the webhook.

- **Avatar URL:** Lets you override the avatar for the webhook.

- **Forum Title:** If this is set, it will open a new post in a forum channel (if the webhook comes from a forum channel) with that title.

- **Forum Tag IDs:** Automatically gives the new forum the related tags if possible.

- **Silent Ping:** Allows you to silence all pings your webhook includes.

- **Supress Link Previews:** Hides all the link embeds your webhook has.

## 3. Deploy & Webhook
- **Discord Webhook URL:** This is the most important field of the builder! This determines where your message will go. If you do not have a webhook URL, go to channel settings -> integrations -> create webhook -> copy webhook URL than paste it here!

- **Discord Message Link:** Allows you to both load and edit a webhook message that has already been sent. Keep in mind that you can only edit it if the webhook url you are using to edit it is the same as the one that originally sent it.

- **Target Thread ID:** Allows you to target a already exsisting thread!

## 3. Json Editor
This allows you to edit the raw json of your webhook! It also allows you to paste json! When you paste json, it will update the builder accordingly so you can always pick up from where you left off or import exsisting embeds (though we would recommend using our message link option)!