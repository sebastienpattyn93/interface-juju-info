# Juju-Info Interface

The juju info interface is a special and implicit relationship that works with
subordinate charms. When building from layers, if your subordinate uses this
interface, you will implicitly receive private-address.

There is no provides or peering mechanism on this interface.


### States

`{{name}}.available`

`{{name}}.connected`

Both states signify the subordinate is successfully connected to the parent
"container". 
