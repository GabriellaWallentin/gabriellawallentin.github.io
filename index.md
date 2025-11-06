<h2>Contact Me</h2>

<!-- Copy-to-clipboard button -->
<button id="copyEmail" style="font-size:1.5em; cursor:pointer;">
  📧 Copy Email
</button>

<script>
const email = "gabriella.wallentin@kit.edu";  // replace with your email
document.getElementById("copyEmail").addEventListener("click", () => {
  navigator.clipboard.writeText(email).then(() => {
    alert("Email copied to clipboard!");
  }, () => {
    alert("Failed to copy email.");
  });
});
</script>
