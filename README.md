# Piano-virtual-my-CDN
## Link demo <a href="https://riswan-nopiyar.github.io/Piano-virtual-my-CDN/">Open</a>
<img width="1363" height="298" alt="image" src="https://github.com/user-attachments/assets/3c78054e-0ac0-4774-b08c-c452906c0523" />

### 🎵 Piano Virtual Embed Guide

### 🇺🇸 Method 1: Direct iframe Embed  
### 🇮🇩 Cara 1: Langsung menggunakan iframe  

```html
<!-- Simple iframe embed -->
<iframe 
  src="https://riswan-nopiyar.github.io/Piano-virtual-my-CDN/" 
  width="100%" 
  height="500" 
  style="border:1px solid #ccc; border-radius:8px;">
</iframe>
```


### 🇺🇸 Method 2: Toggle Button with iframe (using script)
### 🇮🇩 Cara 2: Tombol buka/tutup dengan iframe (menggunakan script) 

```html
<!-- Button to toggle iframe -->
<button 
  onclick="var f=document.getElementById('Piano-frame'); f.style.display = (f.style.display==='none' ? 'block':'none');" 
  style="padding:8px 16px; background:#007BFF; color:#fff; border:none; border-radius:6px; cursor:pointer;">
  🎶 Show / Hide Piano Virtual
</button>

<!-- Iframe hidden by default -->
<div id="Piano-frame" style="margin-top:10px; display:none;">
  <iframe 
    src="https://riswan-nopiyar.github.io/Piano-virtual-my-CDN/" 
    width="100%" 
    height="500" 
    style="border:1px solid #ccc; border-radius:8px;">
  </iframe>
</div>
```
