### Description

This base template uses a default nginx.conf without exposing configurations but includes existing user files to avoid interference. 
It can be used as-is, allowing users to inject Augment templates, each creating its own .conf file under /etc/nginx/conf.d. 
This enables one Augment template per application, with each defining its own server, upstream, and location details. 
Keep content within curly braces unchanged; other elements can be modified. 

This template is ready to use and also helps users understand the templates feature.