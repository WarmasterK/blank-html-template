### Html Boilerplate
the simplest html template

#### Doctype
`<!DOCTYPE html>`
the simple html5 doctype

#### Metatags
- content
	- http-equiv / content
	- charset
- mobile
	- content / name
- caching
	- http-equiv / content
- description
	- content / name

#### Scripts and Styles
standards-based script and style includes

```
<!DOCTYPE html>
<html>
    <head>
        
        <!-- meta tags -->
        <!-- encoding -->
        <meta http-equiv="content-type" content="text/html"/>
        <meta charset="utf-8"/>

        <!-- reset viewport for mobile -->
        <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
        
        <!-- caching - default is no cache-->
        <meta http-equiv="Expires" content="Tue, 01 Jan 1995 12:12:12 GMT"/>
        <meta http-equiv="PRAGMA" content="NO-CACHE"/>
        <meta http-equiv="CACHE-CONTROL" content="NO-CACHE"/>

        <!-- description -->
        <meta name="description" content="..."/>

        <!-- title -->
        <title>
         Blank Html Template
        </title>

        <!-- favicon -->

        <!-- styles -->
        <!-- <link href='https://fonts.googleapis.com/css?family=Source+Sans+Pro:400,300,700' rel='stylesheet' type='text/css'></link> -->
        
    </head>

    <body>

        <!-- scripts -->
        <script src=""></script>

    </body>

</html>
```