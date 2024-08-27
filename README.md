# bikkeedas
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home</title>
    <script crossorigin src="https://unpkg.com/react@18/umd/react.development.js"></script>
<script crossorigin src="https://unpkg.com/react-dom@18/umd/react-dom.development.js"></script>
<script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>
<script type="text/babel">
  /* 
  Upto react 17
  ReactDOM.render(
        "Welcome to react !!",
        document.querySelector("p")
    )
    */

    //react 18
   const root = ReactDOM.createRoot(document.querySelector("h2"))
   root.render(" Hello React");
</script>
</head>
<body>
    <h2>Home - Using react</h2>
   <h2></h2>
    <a href="index.html">back to index page</a>
</body>
</html>
