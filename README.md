# test-week8

**What do jQuery selectors start with?**

$


**What's the problem with this code
in your html:
`<div class="my-element">Hide me</div>`
in your javascript:
`$(".another-element").hide();`**

The classes don't match. $(".another-element") selects the tag with the class "another-element" but the elemnt we're trying ot hide has the class "my-element


**What's wrong with this code:
in your html:
`<div class="my-element">Hide me</div>`
in your javascript:
`$("#hideMe").hide();`**

$('#hideMe') is selecting the element with **ID** hideMe but our element has the **CLASS** my-element


**If you have a FOLDER named lib and a FILE named app.js, why won't this link to your javascript work?
`<script src="app.js"></script>`**

you need to include the **folder** in the file path. So it should be `<script src="lib/app.js"></script>` (with **lib**)


**What can you tell me about this: <input type="text"/> what is it? what will we be using them for?**

`<input type="text">` creates a TEXT field where users can enter information on a page. Then we can grab that information and do stuff with it using JavaScript/jQuery
