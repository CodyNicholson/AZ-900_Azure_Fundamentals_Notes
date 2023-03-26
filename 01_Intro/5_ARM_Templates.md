# Azure Resource Manager (ARM) Templates

The ARM Templates are a way to describe which resources you want to create, update, delete, or do any number of actions to. It is a common language and syntax that could be used for idempotent actions (Every ARM template can be applied multiple times and the result is always the same). 

In addition to being idempotent, you can also track your ARM Templates using version control. You can reuse a a combination of multiple partial ARM templates to achieve a result. It is Declarative: Meaning you will specify what you want, not how it is done. Also, ARM Templates are free of human errors since they are automated.
