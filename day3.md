# Component Interaction

## Via HTML
* @Input
* @Output

## Via Typescript
* @ViewChild
* @ViewChildren

## Via Service

# Component Lifecycle

* constructor
* ngOnInit
* ngOnChanges
* ngDoCheck
* ngAfterViewInit
* ngAfterViewChecked
* ngAfterContentInit
* ngAfterContentChecked
* ngOnDestroy

# Dependency Injection

Dependency injection (DI), is an important application design pattern. Angular has its own DI framework, which is typically used in the design of Angular applications to increase their efficiency and modularity.

Dependencies are services or objects that a class needs to perform its function. DI is a coding pattern in which a class asks for dependencies from external sources rather than creating them itself.

## Providers Type

* Class Based Provider
* Value Provider
* factory

## Service Visibility

* @SkipSelf
* @Self
* @Optional
* @Host

# HTTP

* HttpClientModule
* HttpClient

## Methods

* get
* post
* put
* delete
* request

## HttpInterceptor