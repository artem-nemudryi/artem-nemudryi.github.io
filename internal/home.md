---
title: internal
---

<script>
if (localStorage.getItem("lab_internal_auth") !== "true") {
  window.location.href = "/internal/";
}
</script>



# Lab Apps

<div class="app-grid">

  <a class="app-tile" href="https://qpcr-planner.vercel.app">
    <div class="app-tile__thumb">
      <img src="{{ '/internal/app_icons/qpcr_plate.png' | relative_url }}" alt="96-well plate icon">
    </div>
    <div class="app-tile__title">qPCR planner</div>
  </a>


 <a class="app-tile" href="https://genomic-diagrams-nemudryi-lab.streamlit.app">
    <div class="app-tile__thumb">
      <img src="{{ '/internal/app_icons/gene_diagrams.png' | relative_url }}" alt="96-well plate icon">
    </div>
    <div class="app-tile__title">Gene Diagrams</div>
  </a>

</div>

<button onclick="logout()" style="margin-top:20px;">Logout</button>

<script>
function logout() {
  localStorage.removeItem("lab_internal_auth");
  window.location.href = "/internal/";
}
</script>