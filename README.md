<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title></title>
  </head>
  <body>
    <title>Who Am I</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <style>
    * {
      box-sizing: border-box;
    }

    body {
      font-family: Arial, Helvetica, sans-serif;
    }


    header {
      background-color: #FFA500;
      padding: 30px;
      text-align: center;
      font-size: 35px;
      color: white;
    }


    nav {
      float: left;
      width: 30%;
      height: 300px;
      background: #ccc;
      padding: 20px;
    }

    }

    nav ul {
      list-style-type: none;
      padding: 0;
    }

    article {
      float: left;
      padding: 20px;
      width: 70%;
      background-color: #f1f1f1;
      height: 300px;
    }


    section::after {
      content: "";
      display: table;
      clear: both;
    }


    footer {
      background-color: #777;
      padding: 10px;
      text-align: center;
      color: white;
    }


    @media (max-width: 600px) {
      nav, article {
        width: 100%;
        height: auto;
      }
    }
    </style>
    </head>
    <body>

    <h2>Who Am I </h2>
    <p>This is a project about me and my attributes.</p>


    <header>
      <h2>Who Am I</h2>
    </header>

    <section>
      <nav>
<h1>10 Word Summary</h1>
      </nav>

      <article>
        <h1>50 word description of myself and 50 word description of career plans</h1>
    50 Word Description
        <p>Ambitious, positive attitude, organized, determined, intelligent, hard working, enjoy facing challenges, dynamic, straightforward,
        ,patient, chill, clever, sympathetic, enjoyable, reliable, loyal, adventurous, capable, collaborative, direct, ethical,
      driven, efficient, honest, high-achieving, innovated, level-headed, mature, productive, quick, self-disciplined,
    unique, versatile, passionate, humble, wise, imaginative, tolerant, tidy, reflective, precise, multilingual, outgoing,
  independent, calm, cooperative, detailed, flexible, idealist, kind, and a learner.</p>
  50 Word Description of Career Plans

      </article>
    </section>

    <footer>
      <p>Footer</p>
    </footer>

    </body>
    </html>
