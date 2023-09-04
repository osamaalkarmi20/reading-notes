# How to Use HTTP Cookies in ASP.NET Core MVC

## Dependencies
Make sure you have the necessary packages added to your project.

## Cookie Basics
In ASP.NET Core MVC, you can use cookies to store small pieces of data on a user's browser.

## Setting a Cookie
Use `Response.Cookies.Append` to create a cookie with a name, value, and optional settings like expiration and security.

## Reading a Cookie
Access cookies with `Request.Cookies`. Check if a cookie exists with `Request.Cookies.ContainsKey` and get its value with `Request.Cookies["CookieName"]`.

## Deleting a Cookie
Remove a cookie with `Response.Cookies.Delete`.

## Cookie Options
Customize cookies with options like `Expires`, `HttpOnly`, `Secure`, and `SameSite`.

## Data Handling
Cookies store data as strings. Serialize complex data to JSON before storing, and deserialize when reading.
