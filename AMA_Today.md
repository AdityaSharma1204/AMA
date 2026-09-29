# AMA Questions and Answers

## 1. What is `position: absolute`?

`position: absolute` removes an element from the normal document flow and positions it relative to its nearest positioned ancestor.  
You can use `top`, `right`, `bottom`, and `left` to control its exact position.

## 2. What is `INSTALLED_APPS`?

`INSTALLED_APPS` is a setting in Django's `settings.py` that contains the applications enabled in a project.  
It includes Django's default apps and custom apps created by the developer.

## 3. What is client-side scripting and server-side scripting?

**Client-side scripting** runs in the user's browser, mainly using JavaScript, and handles UI interactions.  
**Server-side scripting** runs on the server, such as Django/Python, and handles business logic, databases, and requests.

## 4. What is a Promise?

A Promise in JavaScript represents the eventual result of an asynchronous operation.  
It can be in three states: **pending, fulfilled, or rejected**, and is commonly handled using `.then()`, `.catch()`, and `async/await`.

## 5. What is a viewport?

A viewport is the visible area of a web page inside the browser window.  
The `<meta name="viewport">` tag helps control how a page is displayed and scaled on different devices, especially mobile devices.

## 6. What is the difference between `render()` and `HttpResponse`?

`HttpResponse` directly sends an HTTP response, usually containing text or HTML, to the client.  
`render()` combines a template with context data and returns an `HttpResponse`, making it convenient for rendering HTML pages.

## 7. Explain MVT in Django.

MVT stands for **Model, View, and Template**.  
**Model** handles data/database, **View** handles request and business logic, and **Template** handles the presentation or HTML displayed to the user.

## 8. What is `annotate()` in Django?

`annotate()` adds calculated or aggregated values to each object in a Django QuerySet.  
For example, it can be used with `Count()`, `Sum()`, or `Avg()` to calculate related data for each record.

## 9. What is a transaction in Django?

A transaction is a group of database operations treated as a single unit of work.  
Using Django's `transaction.atomic()`, either all operations are committed or, if an error occurs, the changes are rolled back.

## 10. What is ORM?

ORM stands for **Object-Relational Mapping**.  
Django ORM lets you interact with database tables using Python objects and QuerySets instead of writing SQL for every operation.
