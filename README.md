<html>
<head>
  <title>My Example</title>

<script>
// Wait for DOM to load
document.addEventListener("DOMContentLoaded", function(event) {

  // Put the button into a variable
  var e = document.getElementById("myForm");
  
  // Wait for user to click the button
  e.addEventListener( "change", function() {
  
    // Put the selected value into a variable
    var myColor = this.color.value;
    
    // The "Switch" statement.
    switch ( myColor ) {
    
    case "Blue":
      alert("Just like the sky!");
      break;

    case "Red":
      alert("Quite daring!");
      break;

    case "Green":
      alert("Like... grass?");
      break;
      
    }
  }, false);
});
</script>

<!-- Replace '{action page}' with your own action page to support non-JavaScript users -->
<form id="myForm" name="myForm" action="{action page}">
  <label>
    <input type="radio" name="color" value="Blue"> Blue
  </label>
  <label>
    <input type="radio" name="color" value="Red"> Red
  </label>
  <label>
    <input type="radio" name="color" value="Green"> Green
  </label>
</form>
<style> body {background-color:aqua;}
</style>
</head>
<body>
  <header>
      <h1>
          No fun No life
      </h1>
      <nav>
          <ul>
              <li>
                   <a href="https://ibrahim-hikari.github.io/entertainment/">
                       Home
                   </a>
               </li>
              <li>
                  <a href="https://omar7100.github.io/entertainment/
">
                      TV-shows
                  </a>
              </li>
              <li>
                  <a href="https://ahmadboxx.github.io/Entertainmentnew/">
                      Anime
                  </a>
              </li>
              <li>
                  <a href="https://obadeh.github.io/ENTERTAINMENT/">
                      Movies
                  </a>
              </li>
              <li>
                  <a href="https://www.facebook.com/ibrahim.ajarmeh.3">
                      Contact us
                  </a>
              </li>
          </ul>
      </nav>
  </header>
  <main>
  <article>
      <section>
      </section>
      <section>
      </section>
  </article>  <main>
       <img src="https://imgix.ranker.com/user_node_img/50084/1001673145/original/l-was-lying-to-the-orphans-about-his-motivations-photo-u1?w=650&q=50&fm=pjpg&fit=crop&crop=faces"/>

   <h3>
       L Lawliet known mononymously as L, is a fictional character and one of the primary protagonists in the manga series Death Note, created by Tsugumi Ohba and Takeshi Obata. He is an enigmatic, faceless, and highly-esteemed international consulting detective who communicates only through his equally inexplicable handler/assistant: Watari, who serves as his official liaison with the authorities. Though his entire past is shrouded in a void of mystery, he has gained a highly-esteemed reputation for solving numerous crime cases and perplexing homicidal mysteries around the globe and is considered to be one of the world's best detectives.
Throughout the series, he observes and spies on the activities of the series' main character, Light Yagami: a high school genius, in an effort to expose him as the infamous serial-killer: "Kira", who is responsible for massacring numerous high-profile criminals around the world, through apparent supernatural means. As the series progresses, the psychological mind-game of cat and mouse between L and Light intensifies, with each one of them being bent on uncovering their true identities, through a series of intricate ploys and schemes, before their cover is blown.
   </h3>
  <article>
      <section>
      </section>
      <section>
      </section>
  </article>
  </main>
  <footer>
      copyrights 2022
  </footer>
</body>
</html>
