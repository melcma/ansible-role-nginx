# melcma.nginx

Ubuntu 16.04 and Ubuntu 18.04 supported

Define virtual hosts list and import it, example:

    vhosts:
      - myapp.com.conf
      - myapp.com.80.conf

You will also need to put general nginx config file:

    files/nginx.conf

And virtual hosts folder that match above vhosts list:

    files/vhosts/myapp.com.conf
    files/vhosts/myapp.80.com.conf