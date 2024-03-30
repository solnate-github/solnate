# Solnate
Solnate is a lightweight donation tool for Solana that can be seamlessly embedded into any website using JavaScript. Simply add the provided code snippet to your HTML and customize the button text, height, and width as needed. 
Donors can contribute SOL directly to your specified wallet address with ease.

```html
<div id="solnate-button"></div>
    
<script type="text/javascript" src="https://cdn.solnate.com/package/solnate/master/js/solnate.min.js"></script>
<script>
    let amount = "0.1"; // SOL amount
    let address = "3uYbnorJUpJK3ePXrxn86dfXC7poeoeWw6QEPf2oB5g7"; // Your SOL wallet address
    const solnate = new SolnateDare(amount, address);
    solnate.render("solnate-button");
</script>
```

Customize the appearance of the donation button using CSS to match your website's design.
