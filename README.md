# Moo.Notifications
This program will pop customized Windows notifications at regular intervals that are difficult to get rid of unless clicked. When clicked, they will launch the configured URL in the default browser. 

## Quickstart
Create a folder named Images and place your image files in it. Edit Notifications_sample.json to use your own images and text, and save a copy as Notifications.json.

## JSON Configuration
- `ImagePath`: The path to the file relative to Images that will appear on the notification. You can create subdirectories to organize sets of images and provide paths to images inside them.
- `Description`: The description text that will appear on the notification.
- `ButtonText`: The text that will appear inside the button.
- `URL`: The URL that will be opened when the notification is clicked.
- `Enabled`: The specific entry can be disabled by setting this to `false`.