##### Multiple bodies in tables
Tables can have multiple ``` tbody ``` children. These are accessible in the DOM using ``` HTMLTableElement.tBodies ```.
To have an header at the start of each body, one should create a ```<tr>``` element as the first child of the body with a single ``` <th> ``` child with a ``` colspan ``` value or many of these.N