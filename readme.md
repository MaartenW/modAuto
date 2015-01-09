# modAuto
## One file to automatically download and start installing MODX Revolution
**modAuto** Is aimed at making it as easy as possible to install [**MODX Revolution**](https://github.com/modxcms/revolution) on any (shared) hosting platform.
### Getting started ###
To download and start installing **MODX Revolution**, just [download the files](https://github.com/MaartenW/modAuto/archive/master.zip) to your computer, unzip and upload `start-modx.php` to your webhost.

After uploading, you visit
*http://www.your-website-address.com/start-modx.php*
and off you go!

## Credits

To make easy-installing as independent as possible I looked for ways to natively handle unzipping the download. While I was unable to find a truly native way, I did find a script which is only reliant on the PHP ZLib extension.

* The UnZip class is based on a library I found at PHPClasses:
http://phpclasses.org/package/2495-PHP-Pack-and-unpack-files-packed-in-ZIP-archives.html
* Which in turn is based on a [CodeIgniter](http://www.codeigniter.com/) class
