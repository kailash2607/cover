# Ex.06 Book Front Cover Page Design
## Date:03.11.2025

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Pulp Fiction - Book Cover</title>

<style>
body {
  margin: 0;
  padding: 0;
  background: #000;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  font-family: "Georgia", serif;
}

.book-cover {
  width: 550px;
  height: 700px;
  background-image:
    linear-gradient(rgba(0,0,0,0.45), rgba(0,0,0,0.6)),
    url("https://images.unsplash.com/photo-1616530940355-351fabd9524b?auto=format&fit=crop&w=800&q=80");
  /* ✅ Works — cinematic red/yellow tone similar to Pulp Fiction */
  background-size: cover;
  background-position: center;
  color: #FFD369;
  border: 6px solid #e50914;
  border-radius: 12px;
  box-shadow: 0 0 40px rgba(255, 0, 0, 0.4);
  text-align: center;
  position: relative;
  overflow: hidden;
  padding: 25px;
}

.book-title {
  font-size: 52px;
  font-weight: 900;
  letter-spacing: 3px;
  margin-top: 80px;
  text-transform: uppercase;
  color: #FFD369;
  text-shadow: 3px 3px 0 #B22222, 0 0 20px rgba(255, 0, 0, 0.7);
}

.subtitle {
  font-size: 18px;
  font-style: italic;
  color: #fff;
  margin-top: 10px;
  letter-spacing: 1px;
}

.hrstyle {
  width: 100px;
  height: 3px;
  background-color: #FFD369;
  border: none;
  margin: 30px auto;
}

.tagline {
  font-size: 15px;
  color: #fff;
  position: relative;
  top: 10px;
  letter-spacing: 1px;
}

.author {
  position: absolute;
  bottom: 130px;
  left: 40px;
  font-weight: bold;
  font-size: 20px;
  color: #fff;
}

.publisher {
  position: absolute;
  bottom: 60px;
  left: 40px;
  color: #FFD369;
  font-size: 16px;
}

.edition {
  position: absolute;
  bottom: 30px;
  left: 40px;
  color: #ccc;
  font-size: 14px;
  font-style: italic;
}

.photo {
  position: absolute;
  bottom: 30px;
  right: 30px;
  width: 130px;
  height: 130px;
  border-radius: 50%;
  border: 3px solid #FFD369;
  box-shadow: 0 0 15px rgba(255, 211, 105, 0.6);
  overflow: hidden;
}

.photo img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
</style>
</head>

<body>
  <div class="book-cover">
    <div class="book-title">PULP<br>FICTION</div>
    <div class="subtitle">A Novel Inspired by Quentin Tarantino’s Masterpiece</div>
    <hr class="hrstyle">
    <div class="tagline">“Stories of Crime, Chance, and Redemption”</div>
    
    <div class="photo">
      <img src="myphoto.jpg" alt="Author Photo">
    </div>

    <div class="author">By KAILASH PRABHU</div>
    <div class="publisher">CineVerse Publishing</div>
    <div class="edition">Collector’s Edition</div>
  </div>
</body>
</html>

 ```

## OUTPUT:

<img width="1912" height="979" alt="Screenshot 2025-11-03 140619" src="https://github.com/user-attachments/assets/c91b71cf-8777-461c-87de-e74677913e53" />

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
