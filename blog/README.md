Key points learnt:

1. The term `resource` used for a collection of similar objects, such as articles. You can perform `CRUD` operations on a resource.
2. The primary form builder for Rails is provided by a helper method called `form_with`.
3. Calling `form_with` requires an identifying scope, e.g. `:article`. `FormBuilder` object - represented by `form` - is used to build form fields.
4. Rails uses handlers for difference formats. e.g. default handler for `HTML` is `erb`, `builder` handler is used to build `XML` templates etc.
5. Migrations are Ruby classes that simplifies the creation and modification of database tables. To run a migration `rails db:migrate`.

Ref: 
1. https://guides.rubyonrails.org/getting_started.html#getting-up-and-running