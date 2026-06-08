<%*
const banners = {
  Monday:    "https://w.wallhaven.cc/full/3q/wallhaven-3q3z9d.jpg",
  Tuesday:   "https://w.wallhaven.cc/full/po/wallhaven-pojl63.png",
  Wednesday: "https://live.staticflickr.com/7192/26874801432_4bf1b77b96_b.jpg",
  Thursday:  "https://ultrawidewallpapers.net/wallpapers/329/highres/aishot-2141.jpg",
  Friday:    "https://thepulp.org/wp-content/uploads/2025/01/Twin-Peaks-Intro-1-10-screenshot-1024x768.png",
  Saturday:  "https://i.redd.it/xqdlg045fol91.png",
  Sunday:    "https://i.pinimg.com/1200x/46/51/4d/46514d91eb1198664d9660170e967b88.jpg"
};
const day = tp.date.now("dddd");
const banner = banners[day];
-%>
---
cssclasses:
  - daily
  - <% day.toLowerCase() %>
banner: <% banner %>
day: <% day.toLowerCase() %>
Bible Reading:
Chapter Read:
No Phone for First 15 Minutes:
Workout:

---
# <% tp.date.now("YYYYMMDD") %>
## [[Journal]]
----

## Reading
----
Reference: [[]]

---
<%* if (day === "Sunday") { %>
## Goals for the Week
----
1. 
2. 
3. 
4. 
5. 

---
<%* } %>
