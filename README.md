#Getting started

This is a documentation repository to start develop for XYZ


## First step
You need a repository with a Dockerfile. In section [xyz-docker-docs](#xyz-docker-docs) you can find some different repositories for different type of projects that you can start with. If you decide to use one of these you should Fork it and then change name on it to what your "homepage" will be called.

If you want something else you can easily create one yourself, just inspect the other ones and you will figure it out ;)

## Setup Webhook

The thing about XYZ, that makes it soooo cool, is that it will be deployed instantly( or maybe in a few minutes in real life :P ) when commiting to master branch. The only thing you need to do to activate this behaviour is to add a webhook to your repository.

Follow the images below and you will be fine.

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

**React.js**

[https://github.com/cfj/react-boilerplate](https://github.com/cfj/react-boilerplate)

**Java**

[https://github.com/jonaseck2/xyz-java-jetty](https://github.com/jonaseck2/xyz-java-jetty)

**Ruby**

[https://github.com/guzmo/xyz-docker-ruby](https://github.com/guzmo/xyz-docker-ruby)

**PHP**

[https://github.com/jonaseck2/xyz-php](https://github.com/jonaseck2/xyz-php)

**Django**

[https://github.com/tibysko/xyz-docker-django](https://github.com/tibysko/xyz-docker-django "Django")

##Retrieve logged in user

If you need to retrieve the user credentials you can do that in the header variables:

  - **Email:** x-forwarded-email
  - **Account name:**  x-forwarded-user 

For local development you can use the plugin called *modHeader*, it exists for FireFox and Chrome.
Just add both of the headers with fake values and you are ready to go. ( Ofc this doesn't work in production ;)... ).

##Api for local development

XYZ would love if you all developers used the same REST API when handling storage/data.

The repository and more info about this can be found at [https://github.com/guzmo/xyz-docker-dev-api](https://github.com/guzmo/xyz-docker-dev-api "Dev api")

##Contributing

Feel free to contribute to this repo and also all of the different xyz-docker repos to make it more awesome! 




