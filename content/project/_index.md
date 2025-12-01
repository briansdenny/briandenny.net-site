---
title: 'Projects'
date: 2024-05-19
type: landing

design:
  spacing: '5rem'
---

<div id="password-screen">
  <h2>Enter Password to View Projects</h2>
  <input type="password" id="pw" placeholder="Password">
  <button onclick="checkPassword()">Enter</button>
  <p id="error" style="color: red;"></p>
</div>

<div id="protected-content" style="display: none;">
  <section>
    <h2>Selected Portfolio Projects</h2>

    {{< collection
      title="Selected Portfolio Projects"
      view="article-grid"
      folders="project"
      columns="3"
    >}}

  </section>
</div>

<script>
  function checkPassword() {
    const correct = "secretshowcase"; // 👉 Change this to your password
    const input = document.getElementById("pw").value;
    if (input === correct) {
      document.getElementById("password-screen").style.display = "none";
      document.getElementById("protected-content").style.display = "block";
    } else {
      document.getElementById("error").textContent = "Incorrect password.";
    }
  }
</script>
