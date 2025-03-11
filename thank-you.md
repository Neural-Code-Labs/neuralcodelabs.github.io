---
layout: default
title: Thank You!
permalink: /thank-you/
---

# 🎉 Thank You, <span id="userName">Friend</span>!

We’ve received your message and will get back to you soon.

🔗 [Return to Home](/)

<script>
    // Extract query parameters from the URL
    const params = new URLSearchParams(window.location.search);
    const name = params.get("name");

    // Update the thank you message if a name was provided
    if (name) {
        document.getElementById("userName").textContent = name;
    }
</script>
