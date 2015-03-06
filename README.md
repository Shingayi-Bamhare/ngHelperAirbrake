# ngHelperAirbrake

Integrate AirBrake into an angular.js application

### Install ng-helper-airbrake 
```
bower install ng-helper-airbrake --save
```

### Include the angular module
```javascript
angular.module('appApp', [
    'ngHelperAirbrake'
]);
```
### Register the project id 
Airbrake requires a project id and secret. This can be configured via the application start in the run function as follows:

```javascript
.run([ '$airbrake', function($airbrake,) {

      // configure airbrake
      $airbrake.setProject('<<PROJECTID>>', '<<PROJECTSECRET>>');
}]);
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :)

## Contributors

* [CSS3 activity indicators](https://github.com/lukehaas/css-loaders)

## License

[MIT License](https://github.com/lukehaas/css-loaders/blob/step2/LICENSE)