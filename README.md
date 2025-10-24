<html>
<head>
<title> Uc kaleen kartel | Hey lets keep this secret ok?</title>
<style>
    h2{
        font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif
        
    }
    h1{
        font-family:  'Segoe UI' 
        
    }
    p{
        font-family:  'Segoe UI';
        bold
        -webkit-text-fill-color: ;color: black;
        
    }
    p1{
        font-family:  'Segoe UI';
        bold
        -webkit-text-fill-color: ;color: black;
        
    }
        .text-box1 {
  border: 2px solid #333; /* Adds a solid border */
  padding: 20px; /* Adds space between the text and the border */
  background-color: #f0f0f0; /* Sets a background color */
  margin: 10px; /* Adds space around the entire box */
  border-radius: 8px; /* Rounds the corners of the box */
  box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2); /* Adds a subtle shadow */
  
}
.money-counter
{
color:green;
}
.socials{
    font-family: 'Segoe UI',;
    
}


</style>

</head>

<body>
<h2>
    Uc kaleen kartel
</h2>
<h3>
<div class = socials> 
<p2>Message us to buy stuff</p2>
<br>
<br>
<p2>Insta: <a href="https://www.instagram.com/aldikanye69/">Aldikanye69</a></p2>
<br>
<p3>sms 049320189</p3>
<br>
<p4>
Whatsapp: +6193270189
</p4>
<br>
<p5>Tiktok: <a href="https://www.tiktok.com/@uckaleenkartel"> uckaleenkartel</a>
</p5>
<br>
<p6>Pay id +61-493-270-189</p6>
    </div>
</h3>

<h1>
    Items.
</h1>
<h1>
    <div class = text-box1>
        <p>
        56 mm Rocktopus <div class = "money-counter">$3</div>
        </p>
        </div>
<div class = text-box1>
<p> 
6 orange notes <div class = "money-counter">$1</div>
</p>
</div>
<div class = text-box1>
<p>
1 fruit roll up (import from america) <div class = "money-counter">¢50 </div> </p> 

</div>
<div class = text-box1>
<p>
bag of shit Cheez-Its 120g  <div class = "money-counter">$1</div>
</p> 
</div>
</h1>
<h1>Websites <br><br>
    <p2>
        ⚠️if a website gets blocked or you get a virus its not on us⚠️</p>

<p1>
    <div class = text-box1>unblocked games <div class = "money-counter">50¢ a pop </div></div></p1>

<p1><div class = text-box1>Pirated movie websites <div class = "money-counter"> 1 for $1 </div></div></p1>

<p1><div class = text-box1>Website with everything unblocked (video's dont work) <div class = "money-counter"> $3 </div></div></p>

 </h1>

</body>









<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>Games Unblocked — Enter code</title>
<style>
  body { font-family: Arial, sans-serif; background:#0d0d0d; color:#fff; text-align:center; margin-top:80px; }
  .secret-text { color:#00ccff; cursor:pointer; text-decoration:underline; }
  #hiddenContent { display:none; margin-top:30px; font-size:18px; color:#00ff99; }
</style>
</head>
<body>

  <h1>Games Unblocked <br> (scroll down if you've entered the pass.)</h1>
  <p class="secret-text" onclick="enterPassword()">Click here to enter</p>

  <div id="hiddenContent" aria-hidden="true">
    welcome ig.<br><br>
    <a href="https://hypackellite.github.io/library.html">hypackellite</a><br><br>
    <a href="https://buttertoasty.github.io/Bowl/">buttertoast</a><br><br>
    <a href="https://fortnite-game.github.io/">Fortnite game </a>
  </div>

<script>
/*
 Client-side password check using SHA-256 hash comparison.
 The plaintext password is NOT in the code. Only the hash is stored.
 Note: Client-side hashing prevents casual discovery, but is not foolproof.
*/


const correctHashHex = "0738b0c530718b75e1641296c300cda1cc028991784cd79aa4f65423d9dc10f0";

/**
 * Compute SHA-256 hash of a string and return hex digest (lowercase).
 * Uses Web Crypto API.
 * @param {string} message
 * @returns {Promise<string>} hex digest
 */
async function sha256Hex(message) {
  const encoder = new TextEncoder();
  const data = encoder.encode(message);
  const hashBuffer = await crypto.subtle.digest('SHA-256', data);
  // convert buffer to hex string
  const hashArray = Array.from(new Uint8Array(hashBuffer));
  const hashHex = hashArray.map(b => b.toString(16).padStart(2, '0')).join('');
  return hashHex;
}

async function enterPassword() {
  const input = prompt("Enter the password:");
  if (input === null) return; // user cancelled

  try {
    const digest = await sha256Hex(input);
    if (digest === correctHashHex) {
      // show the content
      const hidden = document.getElementById("hiddenContent");
      hidden.style.display = "block";
      hidden.setAttribute("aria-hidden", "false");
      // optionally scroll to revealed content
      hidden.scrollIntoView({behavior: "smooth"});
    } else {
      alert("Incorrect password. Try again.");
    }
  } catch (err) {
    console.error("Hashing failed:", err);
    alert("An error occurred. Try again.");
  }
}
</script>

</body>
</html>
