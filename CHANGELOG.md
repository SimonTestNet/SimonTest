### [1.9.1] - 2021-10-15

- Fix issue with unknown parameters

### [1.9.0] - 2020-10-03

- Use TestBed.inject for Angular 9+

### [1.8.10] - 2020-09-07

- Add line breaks before major sections of the test file

### [1.8.9] - 2020-07-29

- Don't include models in provider list

### [1.8.8] - 2020-06-07

- Fix issue calling prototype methods of dependencies.

### [1.8.7] - 2020-05-15

- Fix issue with property defaults of array of strings.

### [1.8.6] - 2020-03-15

- Import RouterTestingModule if the template uses routerLink.

### [1.8.2] - 2020-03-01

- Import FormsModule if the template uses ngModel.

### [1.6.0] - 2020-01-03

- Use ng-cache-testing-module if it's in the project's package.json

### [1.5.2] - 2019-08-05

- Fix issue with unused imports.

### [1.5.1] - 2019-07-23

- Fix issue with stubs used by the constructor.

### [1.5.0] - 2019-07-21

- Create better tests for HttpClient calls, using HttpClientTestingModule.

### [1.4.4] - 2019-07-15

- Fix issue with not getting the stubbed parameter for methods in certain cases.

### [1.4.3] - 2019-06-14

- Fix issue with direct imports in files.

### [1.4.1] - 2019-06-02

- Fix issue with services referencing entire modules and setting default properties to undefined.

### [1.4.0] - 2019-05-12

- Add DevExpress import when it detects a template uses a DevExpress control.

### [1.3.1] - 2019-05-04

- Add "Ctrl + Shift + P" command (SimonTest: Update License) to add/update SimonTest License.

### [1.3.0] - 2019-04-28

- Add parameters to function stubs

### [1.2.0] - 2019-04-20

- Add .and.callThrough() to default spies. This makes it easier to add the logic to test things like services.

### [1.1.4] - 2019-03-11

- Improve time to install the extension.

### [1.1.3] - 2019-03-10

- Fix issue when getting user settings.

### [1.1.2] - 2019-03-07

- Directive tests don't include assertions for default values. The recommended way to test them is via the elements themselves.

### [1.1.1] - 2019-03-04

- Fix error with import \* and private properties

### [1.1.0] - 2019-03-03

- Add scaffold tests for directives

### [1.0.5] - 2019-02-28

- Fix error when right clicking a file while having another selected and open. It will process the right clicked file as expected.
- Try to get quotation mark from the code when tslint isn't present or doesn't specify the quotation mark.

### [1.0.0] - 2019-01-19

- 1.0 release

### [0.20.0] - 2018-12-24

- Mock dependencies of services and pipes

### [0.19.0] - 2018-10-02

- Use TestBed for injectables

### [0.18.1] - 2017-12-01

- SimonTest can now read tslint and package.json files with comments in them.

### [0.18.0] - 2017-11-16

- Add types to stubs

### [0.17.4] - 2017-11-04

- Show better errors when something goes wrong.

### [0.17.3] - 2017-10-21

- Fix tests for static properties.

### [0.17.2] - 2017-08-31

- Fix issue generating new components (missing slash dependency)
- Show warning if it can't find the appropriate module when generating a
  component

### [0.17.1] - 2017-08-28

- Fix adding newly generated components to the module

### [0.17.0] - 2017-08-25

- Generate scaffold for services

### [0.15.2] - 2017-07-30

- Add error reporting

### [0.15.1] - 2017-07-29

- Use const on pipe tests

### [0.15.0] - 2017-07-20

- Generate scaffold for pipes

### [0.14.0] - 2017-06-26

- Create .gen.spec.ts file when test already exists.

### [0.13.1] - 2017-06-20

- Fix forEach error on some Components

### [0.13.0] - 2017-06-15

- Now stubs models and passes them to methods that take them as parameters.

### [0.12.2] - 2017-06-11

- Fix issue with private methods still getting tests generated.

### [0.12.1] - 2017-06-09

- Fix issue where it created a test for private methods if they used injected
  services.

### [0.12.0] - 2017-06-06

- Use `fixture.debugElement.injector.get` to get the stubbed services.

### [0.11.3] - 2017-04-16

- Fix exception with implicit any parameter.

### [0.11.2] - 2017-04-15

- Don't test private methods.

### [0.11.1] - 2017-04-09

- Fix indentations. It correctly uses the editor's choice of tabs or spaces.

### [0.11.0] - 2017-04-08

- Use the quotation marks specified in the tslint.json file

### [0.10.1] - 2017-03-31

- Don't throw error when a method receives a parameter that's not a service.

### [0.10.0] - 2017-03-13

- Create tests for when a method uses a service.

### [0.9.1] - 2017-02-19

- Fix tests when a method calls another method already called by the
  constructor.

### [0.8.0] - 2017-02-15

- Add newly generated components to the appropriate module.

### [0.7.0] - 2017-02-13

- Create new components by right-clicking a component in the html

### [0.6.0] - 2017-02-11

- Display warning if user tries to generate on a file that doesn't have a
  component.

### [0.5.1] - 2017-01-28

- Fix issue with `import 'foo';`

### [0.5.0] - 2017-01-28

- spy on all calls made by methods (on the same `it` block)

### [0.4.0] - 2017-01-27

- Add tests when component methods call other methods (spying on them).
- Spy on methods called by the constructor.
- Spy on super methods.

### [0.3.2] - 2017-01-17

- Fix indentation for stubbed properties.

### [0.3.0] - 2017-01-17

- Initial release
