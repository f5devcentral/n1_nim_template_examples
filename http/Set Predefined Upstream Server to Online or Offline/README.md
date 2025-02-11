### Description

An Augment template to mark servers in an upstream as up or down. 
You can configure and add upstream IP addresses in http.tmpl, then use this template to toggle their status. 
This is useful for understanding various use cases achievable with NGINX templates.

### To add additional servers changes must be made in both the http.tmpl file and http.json files. ###

Modify http.tmpl to add upstreams.
Update http.json to change UI and API values in the schema.


