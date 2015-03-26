#Getting started

This is a documentation repository to start develop for XYZ

To start with you will need a repository with a Dockerfile. In the section *xyz-docker-docs* on this page you can find some different repositories for different type of projects that you can start with.

If you want something else you can easily create one yourself, just inspect the other ones and you will figure it out ;)

The thing about XYZ, that makes it soooo cool, is that it will be deployed instantly( or maybe in a few minutes in real life :P ). The only thing we need to do to activate this behavious is to add a webhook to our repostory that will be triggered everytime something gets merged to Master.

## Webhook


![](https://raw.githubusercontent.com/guzmo/xyz-docker-docs/master/images/image01.png)

![https://raw.githubusercontent.com/guzmo/xyz-docker-docs/master/images/image00.png](https://raw.githubusercontent.com/guzmo/xyz-docker-docs/master/images/image00.png)

![](https://raw.githubusercontent.com/guzmo/xyz-docker-docs/master/images/image02.png)

![](https://raw.githubusercontent.com/guzmo/xyz-docker-docs/master/images/image03.png)


## xyz-docker-docs

Below are repositories ready for use.

**Python 2**

[https://github.com/jonaseck2/xyz-python-2-flask](https://github.com/jonaseck2/xyz-python-2-flask)

**Python 3**

[https://github.com/jonaseck2/xyz-python-3-flask](https://github.com/jonaseck2/xyz-python-3-flask)

**Javascript ( Starts a simple express server )**

[https://github.com/guzmo/xyz-docker-nodejs](https://github.com/guzmo/xyz-docker-nodejs)

**Java**

[https://github.com/jonaseck2/xyz-java-jetty](https://github.com/jonaseck2/xyz-java-jetty)

**Ruby**

[https://github.com/guzmo/xyz-docker-ruby](https://github.com/guzmo/xyz-docker-ruby)

**PHP**

[https://github.com/jonaseck2/xyz-php](https://github.com/jonaseck2/xyz-php)

**Django**

[https://github.com/tibysko/xyz-docker-django](https://github.com/tibysko/xyz-docker-django "Django")


**Api for local development**

XYZ should try to use the same REST API when handling storage/data.

The repository and more info about this can be found at [https://github.com/guzmo/xyz-docker-dev-api](https://github.com/guzmo/xyz-docker-dev-api "Dev api")










## Troubleshooting ##

**Something goes wrong when you use *vagrant up:***

Use *vagrant destroy* to remove everything and then do *vagrant up* again.

**Error when docker containers are starting?**

Enter the Vagrant box by using the command *vagrant ssh* in the same folder as the Vagrantfile.
When inside:

    cd /vagrant
    docker-compose up

This should recreate the boxes and hopefully work.

**Other errors**

If you get this error below: 

    ==> default: Waiting for machine to boot. This may take a few minutes...
    The guest machine entered an invalid state while waiting for it
    to boot. Valid states are 'starting, running'. The machine is in the
    'poweroff' state. Please verify everything is configured
    properly and try again.

or if you get timeout or ssh problems to the box, the cause may be Virtualizaion(VT-x) being turned off in the BIOS.






