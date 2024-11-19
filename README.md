# Exercise: Fetch and Display Data About Football Clubs on a Website

---

## **Objective:**

Learn how to fetch data from a JSON file, dynamically create HTML elements, and display the data on a webpage using JavaScript.

---

## **Scenario:**

You are given a JSON file containing information about football clubs. Your task is to write a JavaScript script to:

1. Fetch the data from the JSON file.
2. Dynamically create `<li>` elements inside a `<ul>` tag with the class `football-clubs`.
3. Populate the `<li>` elements with the data about each football club.

---

## **Requirements:**

1. Fetch the JSON data from the file using the **Fetch API**.
2. Use a `forEach` loop or another iterator to go through the JSON data.
3. Create a `<li>` element for each football club.
4. Populate the `<li>` element with:
   - The club name (`<h3>` tag).
   - The stadium name (`<p>` tag).
   - The seating capacity (`<p>` tag).
   - The build year of the stadium (`<p>` tag).
   - An image of the stadium (`<img>` tag).
5. Append each `<li>` element to the `<ul>` tag with the class `football-clubs`.

---

## **HTML Structure:**

Ensure your HTML file has the following structure:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Football Clubs</title>
  </head>
  <body>
    <section class="content">
      <ul class="football-clubs"></ul>
    </section>
    <script src="js/script.js"></script>
  </body>
</html>
```
