## Roles & Permissions

### Team Leader

- Description: is the responsible of all the Goods donated in a Donation Point, hands a Shipment of Goods to a Driver
- Parmissions:
  - Can see/edit the assigned Collection Point
  - Can add/edit/remove Shipments associated to a Collection Point (until a Shipment is approved from an Operator)

### Driver

- Description: has a list of Donation Points from which will collect Goods from, then delivers them to one Collection Point
- Permissions:
  - Can see a list of Donation Points he is associated whith

### Operator

- Description: has visibility over a set of Donation Points assigned by the Area Leader, he/she is responsible for manually prompt all the Good of a Shipment for one or more Collection Points
- Permissions:
  - Can add/remove/edit Collection Points
  - Can add/edit Team Leaders
  - Can associate/change one Team Leader to a Collection Point
  - Can approve a Shipment associated to a Collection Point
  - Can add/edit/remove Shipments associated to a Collection Point

### Area Operator

Has visibility over Collection Points, Operators, Team Leaders and Drivers of a specified area (collection of cities)
Can add/remove/edit Collection Points
Can add/edit/remove Drivers
Can associate Drivers with Collection Points
Can add/edit Team Leaders
Can associate one Team Leader to a Collection Point

### Area Leader

Has visibility over Collection Points, Operators, Area Operators, Team Leaders and Drivers of a specified area (collection of cities)
Can add/edit/remove Operators and Area Operators
Can associate one or more Collection Points to one or more Operators (Operators can share Collection Points)
Has the same permissions as an Operator and an Area Operator

### Admin

Has visibility over Collection Points, Team Leaders, Operators, Drivers of multiple Areas
Has the same permissions as an Area Leader

### Super Admin

Can create a Food Drive event
Can add/edit/remove Administrators
Has the same permissions as an Admin
