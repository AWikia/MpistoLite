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
  <li>Both types of button group are accepted. Using <code>mpisto-button-group</code> will cause the <code>legacy</code> attribute to be parsed onto the button group
    <li>Inline or Custom CSS used on buttons or in button groups will not be tolerated and won't get loaded</li>
</ol>
