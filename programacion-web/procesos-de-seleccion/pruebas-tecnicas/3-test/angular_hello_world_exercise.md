# UX exercise

You have to develop the HTML front end for an IUD (AKA CRUD) example application. We provide the HTTP REST endpoints and you have to build everything from there.

The only mandatory requirement is to use Angular as framework, version >= 5.

Other optional and desirable features:
(Choose those which you feel comfortable with)

- functional

  - Google style guide
  - (client side) list filtering
  - implement different screens for each section (list / edition) and use Angular Router to access them (Using of lazy load is desired)
  - form validation
  - undo feature in edition
  - server error handling
  - unit testing with Jasmine (or similar)
  - multi-language support
  - follow google’s best practices recommendation for modularization
  - try to lean on typescript OO features (inheritance, encapsulation, abstraction, etc)
  - _optional_: execute a pre app bootstrap routine, ie for fetching environment configuration

- design
  - Bootstrap or material
  - validation error message (i.e.: required field, invalid date format)
  - custom notifications (instead of JS native alert)
  - Sass (or Less) for CSS generation
  - responsive design
  - transitions
  - … and any little detail you like(i.e.: server loading icon, “there is no data” message for empty lists, etc.)

## Suggestions

Feel free to use any external directive or third party library you like.

Small files and semantic folder structure will be appreciated.

We like external templates (ng-include or similar), they help to keep the files small.

We know is a very stupid simple app (it’s an exercise), but work thinking it’s the beginning of a larger project. Some elements have no sense for the IUD requirement (angular service to encapsulate generic behavior) but it would be great if anyone want to add the IUD for another entity.

We are very (VERY) strict with naming and conventions ([the “other” hard problem](martinfowler.com/bliki/TwoHardThings.html)). There is no Good Convention, just choose one and keep it coherent.

## API

data format: JSON
user model
int Id // database identity
string Name
DateTime Birthdate
endpoints
get all

- url: http://hello-world.innocv.com/api/user
- method: GET
- params: <none>
- returns: List<user>

get

- url: http://hello-world.innocv.com/api/user/{id}
- method: GET
- params: id (int)
- returns: user

create

- url: http://hello-world.innocv.com/api/user
- method: POST
- body:
  string Name
  DateTime Birthdate

- returns: user (with generated id)

update

- url: http://hello-world.innocv.com/api/user
- method: PUT
- body:
  int Id // database identity
  string Name
  DateTime Birthdate

- returns: user

delete

- url: http://hello-world.innocv.com/api/user/{id}
- method: DELETE
- params: id (int)
- returns: <void>
