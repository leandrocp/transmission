[![logo](http://blogmmix.ch/sites/default/files/imagecache/gross/6/transmission-bittorrent1.png)](https://www.transmissionbt.com/)

# Transmission

Transmission docker container

# How to use this image

    sudo docker run --name transmission -p 9091:9091 \
                -v /path/to/directory/downloads:/var/lib/transmission-daemon/downloads \
                -v /path/to/directory/watch:/var/lib/transmission-daemon/watch \
                -d leandrocp/transmission

## More info

[dperson/transmission](https://registry.hub.docker.com/u/dperson/transmission/).
