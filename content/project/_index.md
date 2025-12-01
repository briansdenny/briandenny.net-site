---
title: 'Projects'
date: 2024-05-19
type: landing
---

<div id="password-screen">
  <h2>Enter Password to View Projects</h2>
  <input type="password" id="pw" placeholder="Password">
  <button onclick="checkPassword()">Enter</button>
  <p id="error" style="color: red;"></p>
</div>

<div id="protected-content" style="display: none;">
  <h2>Project Access Granted</h2>
  <p>You’ve unlocked the portfolio content. 🎉</p>
  <!-- You can list links or tiles here manually or with a partial later -->
</div>

<script>
  function checkPassword() {
    const correct = "secretshowcase";
    const input = document.getElementById("pw").value;
    if (input === correct) {
      document.getElementById("password-screen").style.display = "none";
      document.getElementById("protected-content").style.display = "block";
    } else {
      document.getElementById("error").textContent = "Incorrect password.";
    }
  }
</script>

