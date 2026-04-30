
### 2–4. Network Tab Observation

Opened BBC as an example, right clicked then inspect then go to Network:
 
| Type | What I Found |
|------|-------------|
| HTML document | The main `.html` page loaded first (status 200) |
| CSS file | A `.css` stylesheet for page styling |
| JS file | A `.js` script for interactivity |
| Image | A `.jpg` or `.webp` image resource |
 
**HTML request headers observed:**
- `Request URL` – https://www.bbc.com/
- `Request Method` – `GET`
- `Status Code` – `200 OK`
- `Response Headers` – included `Content-Type: text/html`, `Cache-Control`, `Server`
### 5–6. Built hello.html in VS Code
Created `hello.html` using the slide 10 example structure (`<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`).  
Double-clicked the file → browser opened it locally (`file:///...`). 
 
### 7. Committed to GitHub
```bash
Created a folder with readme.md inside web101-labs/README.md
git clone the folder
git add week-01/hello.html
git commit -m "Add hello.html into week-01 folder"
```
