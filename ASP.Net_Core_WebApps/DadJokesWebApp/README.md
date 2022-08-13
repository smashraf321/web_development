### Welcome to my Dad Jokes Web App

In its simplest form, this is a web app to display dad jokes.

#### Development tutorial for noobs:

* **Basic Updates:**\
  **1.** Edit [`DadJokesWebApp/Views/Home/Index.cshtml`](Views/Home/Index.cshtml) to update home page text.\
  **2.** Edit [`DadJokesWebApp/Views/Home/Privacy.cshtml`](Views/Home/Privacy.cshtml) to update Privacy page text.

* **Create models:**\
  **1.** Create C# classes which are essentially placeholders for data we primarily work with under [`DadJokesWebApp/Models/`](Models/)

* **Controllers:**\
  **1.** Right click `Controllers` in Visual Studio Solution Explorer and add a new controller. This step generates a ton of code for us.
  * **Note:** Ensure Data Context class is `DadJokesWebApp.Data.ApplicationDbContext` when adding new controller and select check boxes for generate views, etc.
