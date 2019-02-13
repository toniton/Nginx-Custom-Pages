# Nginx Custom Pages
This project contains the custom pages that can serve as alternatives to nginx default pages such as: index.htm, 50x.htm, 40x.htm.

## Usage ##
Go to the directory where nginx default files are stored.
```sh
    $ cd /usr/share/nginx/html
```

Then, clone the current repository into it.
```sh
    $ git clone https://github.com/toniton/nginx-custom-pages
```
Finally, reload your nginx installation.
```sh
    $ sudo systemctl reload nginx
```
or
```sh
    $ sudo systemctl restart nginx
```

## License
[MIT](https://choosealicense.com/licenses/mit/)

***Disclaimer:***

*This project is tailored for Silicon Bear's nginx installation, please ensure you follow all our guidelines before using this on your production server, as you are be liable for your use of this product*

