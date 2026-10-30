# Collective Access - FIAF Cataloging Rules (2016)

This Github repository contains files for managing a moving image collection using [Collective Access](https://collectiveaccess.org) and cataloging rules as described in [The FIAF Moving Image Cataloging Manual (2016)](https://www.fiafnet.org/pages/e-resources/cataloguing-manual.html).

## About
This setup is currently being developed at [Anthology Film Archives](http://www.anthologyfilmarchives.org) for use as a central cataloging database for our moving image collections. The goal is to develop a two-level hierarchy (Work/Variant and Manifestation/Item) profile that follows the cataloging standards as described in [The International Federation of Film Archives's](http://fiafnet.org) [Moving Image Cataloguing Manual (2016)](https://www.fiafnet.org/pages/e-resources/cataloguing-manual.html) as closely as possible.

## Structure
* __Level 1, Work (object type work):__ title, form, genre, date, country, language, original running time, credits and cast statements, summary, source and notes.
    * __Variants:__ FIAF’s Variant level is not a separate level. Record a variant as its own Work, linked with the variant relationship on ca_objects_x_objects         
* __Level 2, Manifestation + Item (object type manifestation_item, a child of a Work):__ one record per physical or digital copy. It carries the manifestation data (gauge or carrier, base, colour, sound, aspect ratio, generation, extent, languages, publication and distribution) together with the item data (holding institution, storage location, acquisition, provenance, access, condition, preservation history).

## Collective Access Installation Profile
This profile was written for [Collective Access 2.0.11](https://collectiveaccess.org/) (CA). 
Instructions for installing CA with an external profile are available in [CA's documentation](https://docs.collectiveaccess.org/providence/user/dataModelling/profiles/).

## Status
In development and testing.

## Contact
* John Klacsmann, Archivist [Anthology Film Archives](http://www.anthologyfilmarchives.org)



