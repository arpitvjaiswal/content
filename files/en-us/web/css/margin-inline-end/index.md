---
title: margin-inline-end
slug: Web/CSS/margin-inline-end
tags:
  - CSS
  - CSS Logical Property
  - CSS Property
  - Experimental
  - NeedsContent
  - Reference
  - margin-inline
  - margin-inline-end
  - 'recipe:css-property'
browser-compat: css.properties.margin-inline-end
---
<div>{{CSSRef}}</div>

<p>The <strong><code>margin-inline-end</code></strong> <a href="/en-US/docs/Web/CSS">CSS</a> property defines the logical inline end margin of an element, which maps to a physical margin depending on the element's writing mode, directionality, and text orientation. In other words, it corresponds to the {{cssxref("margin-top")}}, {{cssxref("margin-right")}}, {{cssxref("margin-bottom")}} or {{cssxref("margin-left")}} property depending on the values defined for {{cssxref("writing-mode")}}, {{cssxref("direction")}}, and {{cssxref("text-orientation")}}.</p>

<div>{{EmbedInteractiveExample("pages/css/margin-inline-end.html")}}</div>

<h2 id="Syntax">Syntax</h2>

<pre class="brush:css no-line-numbers">/* &lt;length&gt; values */
margin-inline-end: 10px;   /* An absolute length */
margin-inline-end: 1em;    /* relative to the text size */
margin-inline-end: 5%;     /* relative to the nearest block container's width */

/* Keyword values */
margin-inline-end: auto;

/* Global values */
margin-inline-end: inherit;
margin-inline-end: initial;
margin-inline-end: revert;
margin-inline-end: unset;
</pre>

<p>It relates to {{cssxref("margin-block-start")}}, {{cssxref("margin-block-end")}}, and {{cssxref("margin-inline-start")}}, which define the other margins of the element.</p>

<h3 id="Values">Values</h3>

<p>The <code>margin-inline-end</code> property takes the same values as the {{cssxref("margin-left")}} property.</p>

<h2 id="Formal_definition">Formal definition</h2>

<p>{{cssinfo}}</p>

<h2 id="Formal_syntax">Formal syntax</h2>

{{csssyntax}}

<h2 id="Examples">Examples</h2>

<h3 id="Setting_inline_end_margin">Setting inline end margin</h3>

<h4 id="HTML">HTML</h4>

<pre class="brush: html">&lt;div&gt;
  &lt;p class="exampleText"&gt;Example text&lt;/p&gt;
&lt;/div&gt;
</pre>

<h4 id="CSS">CSS</h4>

<pre class="brush: css">div {
  background-color: yellow;
  width: 120px;
  height: 120px;
}

.exampleText {
  writing-mode: vertical-lr;
  margin-inline-end: 20px;
  background-color: #c8c800;
}</pre>

<h4 id="Result">Result</h4>

<p>{{EmbedLiveSample("Setting_inline_end_margin", 140, 140)}}</p>

<h2 id="Specifications">Specifications</h2>

{{Specifications}}

<h2 id="Browser_compatibility">Browser compatibility</h2>

<p>{{Compat}}</p>

<h2 id="See_also">See also</h2>

<ul>
 <li>{{cssxref("margin-inline-start")}}</li>
 <li>The mapped physical properties: {{cssxref("margin-top")}}, {{cssxref("margin-right")}}, {{cssxref("margin-bottom")}}, and {{cssxref("margin-left")}}</li>
 <li>{{cssxref("writing-mode")}}, {{cssxref("direction")}}, {{cssxref("text-orientation")}}</li>
</ul>