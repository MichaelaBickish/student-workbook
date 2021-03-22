# 1 | 3/22/2021 Journal


## *What is Scope ?*
Where a variable is is available for use. For example, when var is declared outside a function, it's globally scoped vs when it's declared inside a function, it's function/locally scoped.

## *What is Hoisting ?*
A javascript mechanism where variables and function declarations are moved to the top of their scope before code execution.

## *In what cases might you use let vs const vs var?*
**let**:  Let has a block scope and can be updated. This would make it the preferred declaration, to prevent some of the potential issues that can happen when using var. 

If you want a variable to have one value inside a block and a different value outside that block, you could use the Let keyword.(let variables can be updated but not redeclared)

**const**: Const is block scoped. While const variables cannot be updated/redeclared, properties inside a const object can be updated. So you could use const if you want to be able to update the properties inside a const object. (const variables cannot be updated or redeclared)

**var**: var variables can be redeclared and updated within their scope. You could use var if you want var to be redefined when certain conditions are true. (var variables can be re-declared and updated)
