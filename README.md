# ReverseProxy-nginx-ssl


[![nginx-image]][nginx-url]


<!-- ABOUT THE PROJECT -->
## About The Project

ReverseProxy-nginx-ssl is just a simple example of nginx reverse proxy config for ssl.

It contains:
* nginx.conf file for the proxy
* nginx.conf file for the upstream server example (work in progress)

You can find more details in the Nginx official documentation. (http://nginx.org/en/docs/)



<!-- GETTING STARTED -->
<!-- GETTING STARTED -->
## Getting Started
* Replace the existing nginx config file first.
(The default config file location is below.)
* Change all 'YOUR_DOMAIN_HERE' to your domain.
* Change SSL certs location if necessary.


## Default nginx.conf location

Linux (apt-get install):

```sh
/etc/nginx
```

Linux (compiled from source):

```sh
/usr/local/nginx/conf
```

Windows (uncompressed file):

```sh
/conf/
```


<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


<!-- CONTACT -->
## Contact

studio.alfred.walker@gmail.com


<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [othneildrew/Best-README-Template](https://github.com/othneildrew/Best-README-Template)
* [Img Shields](https://shields.io)


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[nginx-image]: https://img.shields.io/badge/nginx-v1.14.0-blue
[nginx-url]: https://nginx.org/en/
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=flat-square
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
