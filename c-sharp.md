##### Define typealiases
``` using RedefinedName = Full type name ```
Note that this directive is scoped to the file it is included only.

##### Expression<T> for accessing expressions structure
To get the member information for an expression of the ``` obj => obj.member ``` kind, use the ``` (expression.Body as MemberExpression).Member ``` code.