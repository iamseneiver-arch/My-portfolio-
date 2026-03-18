<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Aaditya | Editor Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    * { margin:0; padding:0; box-sizing:border-box; }
    body { font-family:'Poppins', sans-serif; background:#0a0a0a; color:#fff; }header {
  position:fixed; width:100%; top:0; left:0;
  display:flex; justify-content:space-between; align-items:center;
  padding:20px 50px; background:rgba(0,0,0,0.6); backdrop-filter:blur(10px);
  z-index:1000;
}

header h1 { font-size:24px; letter-spacing:2px; }

nav a {
  margin-left:25px; text-decoration:none; color:#fff; font-size:14px;
  transition:0.3s;
}

nav a:hover { color:#ff3c3c; }

section { padding:100px 50px; }

.hero {
  height:100vh; display:flex; flex-direction:column;
  justify-content:center; align-items:flex-start;
}

.hero h2 {
  font-size:60px; font-weight:700;
}

.hero span { color:#ff3c3c; }

.hero p { margin-top:20px; max-width:500px; opacity:0.7; }

.btn {
  margin-top:30px; padding:12px 25px;
  border:none; background:#ff3c3c; color:#fff;
  cursor:pointer; border-radius:30px;
  transition:0.3s;
}

.btn:hover { transform:scale(1.05); }

.portfolio {
  display:grid; grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
  gap:20px;
}

.card {
  position:relative; overflow:hidden; border-radius:15px;
}

.card img {
  width:100%; height:100%; object-fit:cover;
  transition:0.5s;
}

.card:hover img { transform:scale(1.1); }

.overlay {
  position:absolute; bottom:0; left:0; width:100%; height:100%;
  background:linear-gradient(to top, rgba(0,0,0,0.8), transparent);
  display:flex; align-items:flex-end; padding:20px;
  opacity:0; transition:0.5s;
}

.card:hover .overlay { opacity:1; }

.overlay h3 { font-size:18px; }

.about {
  max-width:800px;
}

footer {
  text-align:center; padding:30px;
  background:#000;
  opacity:0.6;
}

  </style>
</head>
<body><header>
  <h1>Aaditya</h1>
  <nav>
    <a href="#home">Home</a>
    <a href="#portfolio">Work</a>
    <a
