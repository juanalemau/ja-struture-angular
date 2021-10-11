# JaStrutureAngular

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 12.2.9.

## Urls 

https://itnext.io/choosing-a-highly-scalable-folder-structure-in-angular-d987de65ec7
https://github.com/mathisGarberg/angular-folder-structure/tree/master/src
https://aglowiditsolutions.com/blog/angular-best-practices/
https://blogs.halodoc.io/angular-best-practices/


|-- app
     |-- modules
       |-- home
           |-- [+] components
           |-- [+] pages
           |-- home-routing.module.ts
           |-- home.module.ts
     |-- core
       |-- [+] authentication
       |-- [+] footer
       |-- [+] guards
       |-- [+] http
       |-- [+] interceptors
       |-- [+] mocks
       |-- [+] services
       |-- [+] header
       |-- core.module.ts
       |-- ensureModuleLoadedOnceGuard.ts
       |-- logger.service.ts
     |
     |-- shared
          |-- [+] components
          |-- [+] directives
          |-- [+] pipes
          |-- [+] models
     |
     |-- [+] configs
|-- assets
     |-- scss
          |-- [+] partials
          |-- _base.scss
          |-- styles.scss