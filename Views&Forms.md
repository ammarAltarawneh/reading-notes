# View Models
Definition of Views:

Views handle data presentation and user interaction in the Model-View-Controller (MVC) pattern.
They are HTML templates with embedded Razor markup, which combines C# code with HTML to create web pages.
File Structure:

Views in ASP.NET Core MVC are .cshtml files using Razor markup.
Views are typically organized in folders named after the app's controllers within the Views folder.
Layouts and Partial Views:

Layouts establish common webpage structures, including headers and footers.
Partial views enable the reuse of components across different views, enhancing modularity.
View Components:

View components are used to reduce repetitive code in views, especially for content requiring server-side code execution.
Benefits of Using Views:

Views promote Separation of Concerns (SoC), making apps more maintainable, modular, and testable.
They allow for independent development of views, business logic, and data access components.
Creating a View:

Views specific to a controller are placed in Views/[ControllerName] folders.
Naming conventions associate views with controller actions.
Passing Data to Views:

Strongly typed views are recommended, with data provided through view models.
Weakly typed data can be passed using ViewData, ViewBag, or model attributes.
CSS Isolation:

CSS styles can be isolated for individual pages or views to prevent conflicts and enhance maintainability.
Scoped CSS files are generated, and the associated style bundle is linked in the layout.
Customization and Configuration:

Scope identifier formats can be customized, and base paths for static web assets can be changed.
Automatic CSS bundling can be disabled for more control.

# Create Form In ASP.NET MVC
1- HTML Forms with Razor: Basic approach using HTML form elements and Razor syntax for controls.

2- HTML Helpers: Use built-in helpers like Html.TextBox for concise, strongly-typed form markup.

3- Tag Helpers: Modern approach using HTML-like tags

4- Model Binding: Define a model class and bind form fields using asp-for attributes for automatic data binding in the controller.