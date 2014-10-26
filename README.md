# README
This is a simple encryption app.
## Getting started
Navigate to the secret_sauce directory. Then start a webserver (must use port 4000):
```
$ ruby -run -e httpd . -p 4000
```
Navigate to enrypt your message `0.0.0.0:4000`.
To encrypt your message:

#### Encrypt
- Type your message into the text area
- Click on the 'Lock Down' button
- Enter a password into the prompt. Remember this password, you will use it to decrypt your message.
- Copy the url placed into the same textarea you entered your message

#### Decrypt
- Paste the url into your browser
- Click on 'Decrypt' button
- Enter the password into the prompt
- The message will be revealed in a prompt if the password is correct