# GraphQL Websocket Concrete5 Sample Composer Package
We build a C5 Version with Siler GraphQL, Apollo V2, React and Material UI. checkout the showdown here [concrete5.lemonbrain.ch](https://concrete5.lemonbrain.ch/index.php/person#/)
The idea of this repo is to show how to use GraphQL and Websockets in Concrete5.

The documentation for it is in this [wiki](https://github.com/lemonbrain-mk/graphql_websocket/wiki)

This project is a concrete5 package that is powered entirely by [composer](https://getcomposer.org). It adds the ability to use graphql and websockets on a standard apache hosting with concrete5.

To install this package on a [composer based concrete5](https://github.com/concrete5/composer) site, make sure you already have `composer/installers` then run:

```sh
$ composer require lemonbrain/concrete5_graphql_websocket_sample
```

Then install the package

```sh
$ ./vendor/bin/concrete5 c5:package-install concrete5_graphql_websocket_sample
```

After insallation of this package refresh your entities /index.php/dashboard/system/environment/entities/view. If you wanna have exact the same look and feel activate also the theme from this package /index.php/dashboard/pages/themes. And then navigate to the /person single page. 

## To dos