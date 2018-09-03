# MpistoLite

Lightweight version of Mpisto with various article reading tools. Supports Opera 11.50

## Wrapper

[EnterMpistoLite](https://awikia.github.io/MpistoLite/MpistoLite.html)

# Article Markup

MpistoLite supports advanced markup. Everything you need to know is here:

## Buttons

Button are accounted for:
<ol>
  <li>When <code>mpisto-buttons2</code> is used, it parses the <code>legacy</code> attribute</li>
  <li>When <code>mpisto-buttons2-2nd</code> or the <code>wds-is-secondary</code> parsed to <code>wds-button</code> is used, it parses the <code>secondary</code> attribute</li>
  <li>When <code title="Does nothing on Mpisto War">hidden</code> parsed to <code>mpisto-buttons2-2nd</code> or the <code>wds-is-text</code> parsed to <code>wds-button</code> is used, it parses the <code>tabbed</code> attribute</li>
   <li>When <code>wds-is-square</code> parsed to <code>wds-button</code> is used, it parses the <code>square</code> attribute</li>
   <li>When <code>wds-nth-color</code> parsed to <code>wds-button</code> is used, it parses the <code>nth-color</code> attribute but button on MpistoLite will appear regular</li>
  <li>Both types of button group are accepted. Using <code>mpisto-button-group</code> will cause the <code>legacy</code> attribute to be parsed onto the button group</li>
  <li>Inline or Custom CSS used on buttons or in button groups will not be tolerated and won't get loaded</li>
</ol>

## Allowed properties

In Mpisto lite, inline CSS and custom CSS of any CCS3 selector is limited to the following:
<ol>
  <li>All CC1 and CC2.1 values except display value</li>
  <li>display (Only CSS1 values and inline-block will render while others will fallback to these):
     <ul>
       <li>Flex/Grid/Table: Block</li>
       <li>Inline-(Flex/Grid/Table)/Table-Cell: Inline-Block</li>
       <li>Any other value: Inline</li>
    </ul></li>
  <li>border-radius</li>
  <li>CSS3 Colors</li>
  <li>More-bg images</li>
  <li>text-overflow</li>
  <li>Gradients (Limited to linear only)</li>
  <li>text-shadow (It is limited to 3 values plus a color and up to two shadows will be recognised)</li>
  <li>box-shadow (Only position-related values and color will be recognized, only first two shadows are recognized)</li>
  <li>All SVG Properties</li>
  <li>Anonymous tables are not supported but their html tag counterparts <b>do</b></li>
</ol>

**More Coming Soon!**
