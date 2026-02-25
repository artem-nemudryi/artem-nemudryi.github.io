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
      <img src="{{ '/internal/app_icons/gene_diagrams.png' | relative_url }}" alt="96-well plate icon">
    </div>
    <div class="app-tile__title">Gene Diagrams</div>
  </a>

</div>


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

