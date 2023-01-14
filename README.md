![line](https://github.com/fwd/n2/raw/master/.github/line.png)

<h1 align="center">NanoPay.js (Beta)</h1>

![line](https://github.com/fwd/n2/raw/master/.github/line.png)

Monetize any website element. 

## Install

```html
<script src="https://dev.nano.to/pay.js"></script>
```

## Initialize

```html
<script>
    nano.lock({ 
        debug: false,
        element: '.premium', // all with class .premium
        amount: 0.1,
        text: 'Read',
        address: 'YOUR_ADDRESS', 
        endpoint: 'https://nanolooker.com/api/rpc', // optional
        success: (block) => {
        	// Element(s) are automatically shown.
        	console.log(block)
        }
    })
</script>
```