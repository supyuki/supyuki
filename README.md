<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>GitHub Profile</title>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
<style>
/* Style the header */
.header {
  text-align: center;
  margin-bottom: 20px;
  font-size: 24px;
  color: #333;
}

/* Style the search container */
.search-container {
  margin: 20px auto;
  text-align: center;
}

/* Style the search input field */
.search-input {
  padding: 10px;
  width: 300px;
  border: 1px solid #ccc;
  outline: none;
  font-size: 18px;
}

/* Style the search button */
.search-button {
  background-color: #f2f2f2;
  border: none;
  padding: 10px;
  cursor: pointer;
}

/* Style the search button icon */
.search-button i {
  color: #666;
}

/* Style the welcome message */
.welcome-message {
  margin-top: 40px;
}

/* Style the scroll buttons */
.scroll-button {
  background-color: #f2f2f2;
  border: none;
  padding: 15px;
  cursor: pointer;
  font-size: 20px;
}

/* Style the social media links */
.social-links {
  margin-top: 20px;
  text-align: center;
}

.social-links a {
  margin: 0 10px;
  color: #333;
  text-decoration: none;
}

.social-links a i {
  margin-right: 5px;
}

</style>
</head>
<body>

<div class="header">
  <h1>Yuki Search</h1>
  <p>Search whatever you want!</p>
</div>

<div class="search-container">
  <input type="text" id="searchInput" class="search-input" placeholder="Search...">
  <button onclick="search()" class="search-button"><i class="fas fa-search"></i></button>
</div>

<h1 class="welcome-message">Welcome to My GitHub Profile</h1>

<button onclick="scrollToBottom()" class="scroll-button">Scroll to Bottom</button>

<script>
function scrollToBottom() {
    var element = document.getElementById("bottom");
    element.scrollIntoView({ behavior: "smooth", block: "end", inline: "nearest" });
}

function search() {
    var query = document.getElementById("searchInput").value;
    var url = "https://www.google.com/search?q=" + encodeURIComponent(query);
    window.location.href = url;
}
</script>

<h2>Status</h2>
<ul>
  <li>🌟 Currently working on exciting projects!</li>
  <li>📚 Learning new things every day.</li>
  <li>💬 Open for collaboration and discussions.</li>
</ul>

<iframe width="560" height="315" src="https://www.youtube.com/embed/DVn8RP2wFf0?si=TniB-RrCpcRxWRJV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<hr>

<img src="https://i.imgur.com/4625wJP.gif" alt="random gif">

<hr>

<a href="https://facebook.com/61557439091041">Facebook</a>
<img src="https://i.imgur.com/PSzD5vG.jpeg" alt="facebook id">

<hr>

<h3>click on this image. ↓</h3>
<a href="https://open.spotify.com/playlist/6TOvF0GLHJVwMTiLS4ujnw?si=cr6KFacmQVOM0MvImcJzuw&pi=a-UsGfQbW1RNqQ">
  <img src="https://i.imgur.com/FuSkI8d.jpeg" alt="Level up your code with beats">
</a>

<p>Turn up the volume and code like a pro!</p>

<!-- Social media links with icons -->
<div class="social-links">
  <a href="https://facebook.com/61557439091041" target="_blank"><i class="fab fa-facebook"></i> Facebook</a>
  <a href="https://instagram.com/timrodai.us" target="_blank"><i class="fab fa-instagram"></i> Instagram</a>
  <a href="https://github.com/supyuki" target="_blank"><i class="fab fa-github"></i> GitHub</a>
  <a href="https://m.me/61557439091041" target="_blank"><i class="fab fa-facebook-messenger"></i> Messenger</a>
  <a href="https://wa.me/9816428079" target="_blank"><i class="fab fa-whatsapp"></i> WhatsApp</a>
</div>

<div id="bottom"></div>

<button onclick="scrollToTop()" class="scroll-button">Scroll to Top</button>

<script>
function scrollToTop() {
    window.scrollTo({ top: 0, behavior: 'smooth' });
}
</script>

</body>
</html>
