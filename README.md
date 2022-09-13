# Uploading a File to Dropbox Using PHP

A basic example of uploading a file to your Dropbox account using vanilla PHP and a generated access token.

To make this upload scripte work just follow these setps:

1. Login to your Dropbox account and go to the [Dropbox developers portal](https://www.dropbox.com/developers/).

2. Click on ```App Console```.

3. Create a new app or use an existing app. Make sure the app has ```files.content.write``` checked in the ```Permissions``` tab.

4. On the ```Settings``` tab generate an Access Token. Place the Access Token in the ```.env``` file. 

5. Test the upload script. 

This cose sample uses a ```.env``` files as described on the [php-env](https://github.com/codeadamca/php-env) repo. 

## Tutorial Requirements:

* [Visual Studio Code](https://code.visualstudio.com/)
* [PHP](https://www.php.net/)
* [Dropbox](https://www.dropbox.com/)

<a href="https://codeadam.ca">
<img src="https://codeadam.ca/images/code-block.png" width="100">
</a>
