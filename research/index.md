---
title: Research
nav:
  order: 2
  tooltip: Our science
---
<h2>Prokaryotic immunity</h2>

{% capture text %}
Bacteriophages, viruses that infect bacteria, outnumber their hosts tenfold. The fierce selective pressure from phage predation has driven bacteria to evolve a vast variety of defense mechanisms. **The molecular mechanisms for most of these immune systems remain unknown, and many more systems remain to be discovered.**

Our recent work demonstrated a direct evolutionary link between tRNA-targeting antiviral effectors in bacteria and humans, highlighting the remarkable conservation of viral defense across domains of life. We found that homologs of human antiviral Schlafen tRNases protect bacteria from phage (Perez Taboada *et al.*, *Nature Microbiology*, *in press*).

Prokaryotic Schlafens (pSchlafen) act as tRNA-targeting anti-phage effectors that are fused to a variety of phage sensors. We aim to understand how diverse pSchlafen proteins sense phage infection and determine the molecular mechanisms of phage defense.

{% endcapture %}

{%
  include feature.html
  image="images/schlafen_defense.png"
  link="research"
  text=text
  flip = true
%}

<h2>Targeting RNA with CRISPR</h2>
{% capture text %}
How do cells cope with RNA damage? The prevailing view is that defective RNA is cleared and replaced as the new RNA is transcribed. **Why repair RNA if cells can re-synthesize it?**

Our recent work challenges this paradigm. We discovered that human cells repair RNA breaks induced by CRISPR ribonucleases and leveraged this mechanism to make programmable deletions in the human transcriptome (Nemudraia, Nemudryi & Wiedenheft, *Science*, 2024). 

We use programmable CRISPR ribonucleases to break RNA, study how it is repaired, and develop RNA editing tools with therapeutic potential.

{% endcapture %}

{%
  include feature.html
  image="images/rna_editing_rna_repair.png"
  link="research"
  text=text
  flip = true
%}
