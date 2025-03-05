---
hideInToc: true
layout: cover
background: ./external-images/2025-02-24-landscape1-01.jpg
---

# <config-var name="title"/>

<config-var type="p" name="subtitle" nbsp="<br/>" class="bg-black py-5 py-2"/>

<p>
  <template v-for="v in 'date author venue'.split(' ')">
  <config-var :name="v"/><br/>
  </template>
  <c>this is a comment</c>
</p>

<div style="position: absolute; left:0; bottom:0; right:0; padding: .5em 5em; background: rgba(0 0 0 / 0.75)">
<img src="./media/logo-bar-inria-iogs-darkbg.svg" class="logos dark"/>
</div>


