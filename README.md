# Socket Programming and Web Server Implementation

## 🧠 Overview
This project demonstrates key networking concepts through hands-on implementation of:
- ICMP and DNS diagnostic tools (`ping`, `tracert`, `nslookup`, `telnet`).
- UDP-based communication (client-server messaging over a local network).
- A fully functional web server built using socket programming.

## 💡 Project Objectives
1. Explore foundational networking utilities and their behavior.
2. Implement a UDP client that broadcasts messages and a server that listens and logs them.
3. Build a custom web server that:
   - Responds to various HTTP requests.
   - Serves HTML/CSS/images.
   - Redirects users.
   - Handles 404 errors with custom responses.

## 🛠️ Technologies Used
- Python (Socket Library).
- HTML5, CSS3.
- Command Line (for network tools).


## ✨ Features
- **Network Diagnostics:**
  - Execute and interpret results from `ping`, `tracert`, `nslookup`, `telnet`.
- **UDP Client/Server:**
  - Client sends name as a broadcast message every 2 seconds.
  - Server logs the sender’s name, IP, and timestamp.
- **Web Server:**
  - Serves HTML/CSS/image files.
  - Handles Arabic/English content.
  - Redirects based on custom paths (`/yt`, `/so`, `/rt`).
  - Returns `404 Not Found` with client info for invalid paths.

## 🌐 Demo URLs
Try these after running the web server on `localhost:9977`:
- `/` → English main page.
- `/ar` → Arabic main page.
- `/about_us_en.html`.
- `/yt` → Redirects to YouTube.
- `/so` → Redirects to Stack Overflow.
- Invalid URL → Triggers custom 404 page.


## 👥 Contributors

- [**Razan Abdalrahman**](https://github.com/razanodeh01) 
- [**Maisam Alaa**](https://github.com/maisamjuma)

