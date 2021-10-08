<!DOCTYPE html>
<html lang="en">
<head>
<title>Who am I</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
  font-family: Arial, Helvetica, sans-serif;
}

/* Style the header */
header {
  background-color: #666;
  padding: 30px;
  text-align: center;
  font-size: 35px;
  color: white;
}

/* Create two columns/boxes that floats next to each other */
nav {
  float: left;
  width: 30%;
  height: 300px; /* only for demonstration, should be removed */
  background: #ccc;
  padding: 20px;
}

/* Style the list inside the menu */
nav ul {
  list-style-type: none;
  padding: 0;
}

article {
  float: left;
  padding: 20px;
  width: 70%;
  background-color: #f1f1f1;
  height: 300px; /* only for demonstration, should be removed */
}

/* Clear floats after the columns */
section::after {
  content: "";
  display: table;
  clear: both;
}

/* Style the footer */
footer {
  background-color: #777;
  padding: 10px;
  text-align: center;
  color: white;
}

/* Responsive layout - makes the two columns/boxes stack on top of each other instead of next to each other, on small screens */
@media (max-width: 600px) {
  nav, article {
    width: 100%;
    height: auto;
  }
}
</style>
</head>
<body>

<h2>Who Am I</h2>



<header>
  <h2>Who Am I</h2>
</header>

<section>
  <nav>
<h1>10 Word Summary</h1>
<p>I am an outgoing, active, go-getting 16 year old teen.</p>
  </nav>

  <article>
    <h1>50 Word Summary of me and my career plans</h1>
    <p>Outgoing, active, funny, go-getting, positive, persistent, passionate, enthustiastic, tenacious, generous, considerate, courageous, fearless, genuine, open-minded, practical, sincere, adaptable, kind, warmhearted, optimistic, easygoing, versatile, energetic, gentle, understanding, determined, attentive, helpful, cheerful, sensitive, flexible, affectionate, adventurous, loyal, reliable, friendly, truthful, motivated, witty, independant, introverted, modest, dynamic, disciplined, patient, straightforward, intelligent, tough, sympathetic.
    <p>I plan on becoming an architect because it is a job that is pretty stress free and has a good work-life balance. On top of having a stress-free social life, you will also be able to have a good financial life too. Being an architect requires a lot of creative thinking, which I possess.
  </article>
</section>

<footer>
  <p>Ahmad El-Haj</p>
</footer>

</body>
</html>
