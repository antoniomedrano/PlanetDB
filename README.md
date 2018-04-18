# PlanetDB
## An iOS Planet Database app made with Swift 3.1 

#### The homepage

The homepage contains a list or table of the planets that have been added to the database
along with their name, size, distance and ordinality.

For example:

    Ordinality  Name     Size    Distance
    1           Mercury  0.05    0.34
    2           Venus    0.08    0.72

The name of the object links to that object's detail page.

#### The input form

A simple form for adding a planet to the database. The form has 4 inputs:
Name, Size (in Earth Masses), Distance (from the sun, In Astronomical Units), Ordinality (Mercury: 1, Neptune: 8)
and Description.

Name and ordinality uniqueness is enforced. Size, Ordinality and Distance are restricted to numerical input.

#### The detail page
The detail page displays all the available information about the planet.

For example:

    Mars
    Mars is the dry and inhospitable 4th planet from the Sun. It is here that Matt Damon
    grew potatoes using his own poop.

    Ordinality: 4
    Size: 0.107 Earth Masses
    Distance: 1.41 AU
