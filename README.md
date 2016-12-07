# frontend-app

## Running the app

1. Checkout code

    git clone https://github.com/boztek/ember-drupal-demo-front.git

2. Download dependencies:

    cd ember-drupal-demo-front
    npm install
    bower install
    curl -o vendor/gmaps.js https://maps.googleapis.com/maps/api/js\?v\=3.22

3. Run the dev server

    ember s

### Same application before Drupal chosen as data source

See the tag before-drupal (https://github.com/boztek/ember-drupal-demo-front/releases/tag/before-drupal).

Compare the differences in the payload fixture in mirage/config.js and the reflected data model in the models.

## Prerequisites

You will need the following things properly installed on your computer.

* [Git](https://git-scm.com/)
* [Node.js](https://nodejs.org/) (with NPM)
* [Bower](https://bower.io/)
* [Ember CLI](https://ember-cli.com/)
