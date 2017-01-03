
### Quick Installation

1. Download
2. Extract the package and copy all files to your webserver / webspace.
3. Open `http://your-domine/index.php/setup` and follow the instructions.

#### Remove `index.php` from the URL

1. Make sure that [mod_rewrite](https://go.domine.com/apachemodrewrite) is enabled on your web server.
2. Remove `index.php` from `$config['index_page'] = 'index.php';` in the file `/application/config/config.php`
3. Rename the `htaccess` file to `.htaccess`

If you want to install system in a subfolder (e.g. `http://your-domain.com/invoices/`) you have to change the .htaccess file. The instructions can be found within the file.
---

