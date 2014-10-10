react-bootstrap-typescript-definitions
======================================

Typescript definitions for [React Bootstrap](http://react-bootstrap.github.io/)

which may come in handy since jsx for typescript is not an option (yet) 

is depending on react.d.ts from the [DefinitlyTyped repo](https://github.com/flyon/DefinitelyTyped)

just import react-bootstrap.min.js in your project or require('react-bootstrap')
 and use
```  
     /// <reference path="path/to/react-bootstrap.d.ts" />
    declare var ReactBootstrap:ReactBootstrap;
```  
and your editor should recognise and autocomplete things like:
```
ReactBootstrap.ButtonToolbar({},
    ReactBootstrap.ButtonGroup({},
        ReactBootstrap.Button({},
            ReactBoostrap.Glyphicon({glyph:'align-left'})
        ),
        ReactBootstrap.Button({},
            ReactBoostrap.Glyphicon({glyph:'align-center'})
        ),
        ReactBootstrap.Button({},
            ReactBoostrap.Glyphicon({glyph:'align-right'})
        )
    )
);
```
 
 



