# image-proxy

## How to use
1. Execute `docker-compose up -d`
1. Add prefix in your image URL. Let's say our it deployed in `cdn.tanggalnya.com`.
    - Original URL: https://link.us1.storjshare.io/s/jvmlrxmm5ekm7qxowmbcskxj3knq/website/our-project/port-26-o.jpg?wrap=0
    - New URL: https://cdn.tanggalnya.com/?url=https://link.us1.storjshare.io/s/jvmlrxmm5ekm7qxowmbcskxj3knq/website/our-project/port-26-o.jpg?wrap=0
1. It can do rezise on the fly just adding `w=xxx&h=yyy`.
    -  https://cdn.tanggalnya.com/?url=https://link.us1.storjshare.io/s/jvmlrxmm5ekm7qxowmbcskxj3knq/website/our-project/port-26-o.jpg?wrap=0&w=300&h=300
    Read more on [docs](https://images.weserv.nl/docs/size.html)
1. It can do more! Please read the docs [here](https://images.weserv.nl/docs/)

## Docs
- [source](https://github.com/weserv/images)
