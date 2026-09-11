---
permalink: /internal/home/
---

<script>
if (localStorage.getItem("lab_internal_auth") !== "true") {
  window.location.href = "/internal/";
}
</script>

# Lab Apps

<div class="app-grid">

  <a class="app-tile" href="https://qpcr-planner-nemudryi-lab.vercel.app">
    <div class="app-tile__thumb">
      <img src="{{ '/internal/app_icons/qpcr_plate.png' | relative_url }}" alt="96-well plate icon">
    </div>
    <div class="app-tile__title">qPCR planner</div>
  </a>
  
 <a class="app-tile" href="https://plate-planner-nemudryi-lab.vercel.app">
    <div class="app-tile__thumb">
      <img src="{{ '/internal/app_icons/plate_planner.png' | relative_url }}" alt="plate icon">
    </div>
    <div class="app-tile__title">Plate planner</div>
  </a>

 <a class="app-tile" href="https://genomic-diagrams-nemudryi-lab.streamlit.app">
    <div class="app-tile__thumb">
      <img src="{{ '/internal/app_icons/gene_diagrams.png' | relative_url }}" alt="gene diagram">
    </div>
    <div class="app-tile__title">Gene Diagrams</div>
  </a>

   <a class="app-tile" href="https://ecoli-calc-nemudryi-lab.vercel.app/">
    <div class="app-tile__thumb">
      <img src="{{ '/internal/app_icons/ecoli-calc.png' | relative_url }}" alt="Ecoli calculator">
    </div>
    <div class="app-tile__title">OD600 and MOI calculator</div>
  </a>

</div>

# Lab Calendar

<iframe src="https://calendar.google.com/calendar/embed?height=600&wkst=2&ctz=America%2FNew_York&showPrint=0&src=Y180MGFmMTFkZDIwYzI2M2UyNjA0YTY1YmNhYTBkNzEwYjY4YmMwMTYyODZkODdiYTQwMDA5MjRhYjg4OGZlNTdlQGdyb3VwLmNhbGVuZGFyLmdvb2dsZS5jb20&src=ZW4udXNhI2hvbGlkYXlAZ3JvdXAudi5jYWxlbmRhci5nb29nbGUuY29t&color=%23f09300&color=%230b8043" style="border:solid 1px #777" width="800" height="600" frameborder="0" scrolling="no"></iframe>

<button onclick="logout()" style="margin-top:20px; font-size:18px;" >Logout</button>

<script>
function logout() {
  localStorage.removeItem("lab_internal_auth");
  window.location.href = "/internal/";
}
</script>

<div class="iframe-container">

<iframe 
  data-testid="embed-iframe"
  style="border-radius:12px; margin: 50px;"
  width="560" 
  height="315" 
  src="https://www.youtube.com/embed/PDtcKVkyJPY?autoplay=1&mute=0&loop=1&playlist=PDtcKVkyJPY"
  title="YouTube video player" 
  frameborder="0" 
  allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"
  allowfullscreen>
</iframe>
</div>

