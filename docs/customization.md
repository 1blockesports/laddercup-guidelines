---
layout: default
title: Colores
nav_order: 6
---

# Colores

Dentro de los colores el logo es versátil aunque tiene tres opciones estáticas.


<div style="display:flex;flex-direction:row;flex-wrap:wrap;justify-content:space-between;align-items:center">
<div style="width:33%;display:flex;flex-direction:column;align-items:center;justify-content:center">
<div style="width:90%;height:70px;background-color:#FFFFFF"></div><br>

<ul style="margin:0;padding:0;list-style:none;">
<li><strong>HEX</strong>: #FFFFFF</li>
<li><strong>RGB</strong>: 255, 255, 255</li>
<li><strong>CMYK</strong>: 0, 0, 0, 0</li>
</ul>

</div>
<div style="width:33%;display:flex;flex-direction:column;align-items:center;justify-content:center">
<div style="width:90%;height:70px;background-color:red"></div>
<dl>
  <dt>RGB</dt>
  <dd>Godzilla</dd>
  <dt>Born</dt>
  <dd>1952</dd>
  <dt>Birthplace</dt>
  <dd>Japan</dd>
  <dt>Color</dt>
  <dd>Green</dd>
</dl>
</div>
<div style="width:33%;display:flex;flex-direction:column;align-items:center;justify-content:center">
<div style="width:90%;height:70px;background-color:red"></div>
<dl>
  <dt>RGB</dt>
  <dd>Godzilla</dd>
  <dt>Born</dt>
  <dd>1952</dd>
  <dt>Birthplace</dt>
  <dd>Japan</dd>
  <dt>Color</dt>
  <dd>Green</dd>
</dl>
</div>
</div>

### Gradiente en css

```css
.gradiente {
  background: rgb(253,231,139);
  background: -moz-linear-gradient(-45deg,  rgba(253,231,139,1) 0%, rgba(226,183,93,1) 100%);
  background: -webkit-linear-gradient(-45deg,  rgba(253,231,139,1) 0%,rgba(226,183,93,1) 100%);
  background: linear-gradient(135deg,  rgba(253,231,139,1) 0%,rgba(226,183,93,1) 100%);
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#fde78b', endColorstr='#e2b75d',GradientType=1 );
}
```