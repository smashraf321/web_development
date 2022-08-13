## Welcome to my Dad Jokes Web App

In its simplest form, this is a web app to display dad jokes.

### Development tutorial for noobs:

* **Basic Updates:**
  * Edit [`DadJokesWebApp/Views/Home/Index.cshtml`](Views/Home/Index.cshtml) to update home page text.
  * Edit [`DadJokesWebApp/Views/Home/Privacy.cshtml`](Views/Home/Privacy.cshtml) to update Privacy page text.

* **Create Models:**
  * Create C# classes which are essentially placeholders for data we primarily work with under [`DadJokesWebApp/Models/`](Models/)

* **Create Controllers:**
  * Right click `Controllers` in Visual Studio Solution Explorer and add a new controller. This step generates a ton of code for us.\
    **Note:** Ensure Data Context class is `DadJokesWebApp.Data.ApplicationDbContext` when adding new controller and select check boxes for generate views, etc.

* **Create Database setup:**
  * Take our model built and create a database that goes behind it. We work with `"migrations"` for this.\
    Look for [`Data/Migrations/`](Data/Migrations/) in the solution explorer.
  * In Package Manager Console (can be displayed from View in Visual Studio) whose goal is to install new dependencies, we'll use it for database management.
  * Type `add-migration "initial setup"` and hit enter, this creates a new file that'll have initial setup in its name under [`Data/Migrations/`](Data/Migrations/).\
    **Note:** initial setup can be replaced with a name of your choice.
