## [From API to Location Map](http://vocane.com/)

This web application is deployed on AWS and is on my website http://vocane.com/

This web application takes public API of company Volta Charging and searches for closest charging stations to the address, entered in the search box or all charging stations of a city.
It displays these stations on Google Map and also shows them in a table.

By default the table's rows are sorted by distance to the entered address.
By clicking on a column's header you can sort the table's rows by this column.
Clicking on a name of a station in the table will show this station on Google Map.
Google might show a popup saying "This page can't load Google Maps correctly."
This is because right now I am not paying for Google Maps API. It will go away when the website's owner pays for Google Maps API. 

