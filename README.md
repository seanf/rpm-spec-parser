The rpm-spec-parser is a java API and Ant task that allows you to parse an 
RPM spec file and extract items that are defined inside it. 

It's useful for building java code that is to be shipped inside an RPM. 
The RPM can be used as the single place where the version of the software 
is defined and the ant scripts can query the spec file when building to get 
the version number and other interesting fields.

Warwick Hunter 2012-02-23 