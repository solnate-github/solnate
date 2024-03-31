# Solnate
Solnate is a lightweight donation tool for Solana that can be seamlessly embedded into any website using JavaScript. Simply add the provided code snippet to your HTML and customize the button text, height, and width as needed. 
Donors can contribute SOL directly to your specified wallet address with ease.

```html
<div id="solnate-button"></div>
    
<script type="text/javascript" src="https://cdn.solnate.com/package/solnate/master/js/solnate.min.js"></script>
<script>
    let amount = "0.1"; // SOL amount
    let address = "3uYbnorJUpJK3ePXrxn86dfXC7poeoeWw6QEPf2oB5g7"; // Your SOL wallet address
    let buttonStyle = "Light"; // Refers to the color scheme of the website (Light = Dark button)
    /* --- Additional --- */
    let buttonPrefix = "Donate"; // Default
    let buttonSuffix = ""; // Defaults to ''
    let buttonHeight = "30px"; // Default
    let buttonWidth = "200px"; // Default
    /* --- Additional --- */
    const solnate = new SolnateDare(amount, address, buttonStyle, buttonPrefix, buttonSuffix, buttonHeight, buttonWidth);
    solnate.render("solnate-button");
</script>
```

Customize the appearance of the donation button using CSS to match your website's design.

**Example**

[Link to the donation page](https://solnate.com/dare?w=3UrCwB5uJpXxX7W6o50YrJPnfpeQ2g.boKe8dooEf70n36eP$)
