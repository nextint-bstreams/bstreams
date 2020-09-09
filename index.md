---
width: full
navbar:
  layout:               center    # Options: default, center
  color:                dark      # Text color, Options: dark or light
  animation:            true
  sticky:               true
  search:               false
  scroll_up:            true
  transparent:          true
  transparent_color:    dark

header:
  layout: 1-1 # Options: left, center, 1-1, 1-2, 1-3 or 2-3
  background_image: website-waves.svg
  #background_video: Working-Space.mp4
  #background_overlay: "linear-gradient(to left top,rgba(218, 91, 197, 0.8) 0%,rgba(151, 27, 191, 0.8) 30%,rgba(2, 8, 212, 0.8) 80%)"
  color: dark #light
  heading_size: medium
  height: full
  parallax: true
  container: small
  content:
    block: bs_header-1

---
<!-- raw 1 - grid for features 1-4 -->
{% include cards.html 
  block="bs-zerofootprint-1" 
  media="top" 
  card_style=""
  grid="1-4"
  gutter="medium"
  section_size="medium"
  section_background=""
  section_content_align="center"
%}

<!-- raw 2-6 - cards -->
{% include cards.html 
  block="bs-home-card-11" 
  media="left" 
  section_size="large"
  section_background="muted"
  section_content_align="left"
%}

{% include cards.html 
  block="bs-home-card-12" 
  media="right" 
  section_size="large"
  section_background=""  
  section_content_align="left"
%}
{% include cards.html 
  block="bs-home-card-13" 
  media="left" 
  section_size="large"
  section_background="muted"
  section_content_align="left"
%}
{% include cards.html 
  block="bs-home-card-14" 
  media="right" 
  section_size="large"
  section_background=""  
  section_content_align="left"
%}


<!-- raw 7 - enterprise -->
{% include cards.html 
  block="bs-home-card-15" 
  media="left" 
  card_style="default"
  section_size="large"
  section_background="muted"
  section_content_align="left"
%}

<!-- raw 8 - blockquote -->
{% include block.html 
  block="bs_content-citation"
  section_container="small"
  section_content_align="center"
  section_padding_remove="top"
  section_size="large"
  section_background="muted"
  block_title="false" 
%}

<!-- raw 9 - cta -->
{% include cta.html 
  section_size="large"
  section_image="website-waves-bottom.svg"
  section_overlay="rgba(0,0,0,0)"
  section_container="small"
  section_content_align="center"
  section_content_color="dark"
  layout="1"
  block="bs-cta-bottom-1"
%}

