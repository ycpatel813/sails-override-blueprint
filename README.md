# sails-override-blueprint

a [Sails](http://sailsjs.org) application

Rest API override for cats controller.

    GET /cats -> CatsController.find
    GET /cats/:id -> CatsController.findOne
    POST /cats -> CatsController.create
    PUT /cats/:id -> CatsController.update
    DELETE /cats/:id -> CatsController.destroy
