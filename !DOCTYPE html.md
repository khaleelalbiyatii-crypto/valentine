#   
```
<!DOCTYPE html>
<
```
```
html lang="en">

```
```
<head>
<
```
```
meta charset="UTF-8">

```
```
<
```
```
title>Valentine</title>

```
```
<style>
body
```
```
 {

```
```
  background: linear-gradient(135deg, #ff9a9e, #fad0c4);
  height: 100vh;
  
```
```
display: flex;

```
```
  justify-content: center;
  align-items: center;
  
```
```
font-family: Arial;

```
```
  
```
```
text-align: center;

```
```
}

.container
```
```
 {

```
```
  
```
```
background: white;

```
```
  padding: 40px;
  
```
```
border-radius: 20px;

```
```
  
```
```
box-shadow: 0 10px 25px rgba(0,0,0,0.2);

```
```
}

button {
  
```
```
padding: 15px 30px;

```
```
  
```
```
font-size: 18px;

```
```
  
```
```
margin: 10px;

```
```
  border: none;
  
```
```
border-radius: 10px;

```
```
  cursor: pointer;
}

#yes {
  background: #ff4d6d;
  
```
```
color: white;

```
```
}

#no {
  
```
```
background: #999;

```
```
  color: white;
  position: relative;
}
</style>
</
```
```
head>

```
```
<body>

<
```
```
div class="container">

```
```
  <h1>Haya, will you be my Valentine? ❤️</h1>
  <button id="yes">Yes 💖</button>
  <button id="no">No 💔</button>
  <p id="message"></p>
</
```
```
div>

```
```

<
```
```
script>

```
```
const noBtn = document.getElementById("no");
const yesBtn = document.getElementById("yes");
const
```
```
 msg = document.getElementById("message");

```
```

noBtn.addEventListener("mouseover", () => {
  noBtn.style.position = "absolute";
  noBtn.style.left = Math.random() * window.innerWidth + 
```
```
"px";

```
```
  noBtn.style.top = Math.random() * window.innerHeight + 
```
```
"px";

```
```
});

yesBtn.addEventListener(
```
```
"click", () => {

```
```
  msg.innerHTML = 
```
```
"You just made me the happiest person alive ❤️";

```
```
});
</script>

</body>
</
```
```
html>
```
```


```
