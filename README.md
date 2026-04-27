#  Code Snippets Manager

A simple **static HTML tool** to store, organize, search, and copy your most frequently used code snippets.

No backend. No setup. Just open and use 

---

##  Live Demo

 **Live at:** https://your-username.github.io/your-repo-name/

---

##  Features

-  Global search across all snippets  
-  Section-based filtering (Navbar)  
-  One-click copy button  
-  Syntax highlighting (Prism.js)  
-  Fast & lightweight  
-  Designed for personal productivity  

---

##  How It Works

- Navbar → filters snippets by category  
- Search → searches across **all sections**  
- Snippets → reusable blocks with title + code  

---

## + Add New Section (Navbar)

```html
<button class="nav-btn" data-section="postgre-backend">Postgre Backend</button>
```

---

## + Add New Code Snippet

```html
<div class="snippet" data-section="react">
     <div class="tag">Package installation for React + Tailwind + Axios + react-router-dom</div>

     <div class="snippet-title">
          Frontend Setup with Vite + React + Tailwind + Axios 
          <span class="file_name">install packages</span>
     </div>

     <button class="copy-btn">Copy</button>

     <!-- RAW CODE -->
     <textarea class="raw-code" style="display:none;">
npm install axios react-router-dom  # cors package is not installed in frontend .
     </textarea>

     <!-- RENDERED CODE -->
     <pre style="background-color: #272822;padding: 20px;">
          <code class="language-bash"></code>
     </pre>
</div>
```

---

##  What You Need to Edit

When adding a snippet:

- `data-section` → category (must match navbar button)  
- `tag` → optional label  
- `snippet-title` → used for search 
- `textarea.raw-code` → paste your code here (**no leading space**)  
- `language-xyz` → Prism language (js, jsx, sql, bash, etc.)  

---

##  Usage Tip

> Add your snippet once → reuse forever  
> until the tech becomes outdated 

---

## Tech Used

- HTML  
- CSS  
- JavaScript  
- Prism.js  

---

##  Future Ideas

- Multi-tag filtering  
- Code search (inside snippets)  
- Export / import snippets  
- Cloud sync  

---

##  Motivation

Built for developers who:
- forget where they wrote that one perfect query  
- want a fast personal snippet manager  
- don’t want heavy tools  

---

##  License

Free to use for personal and educational purposes.
