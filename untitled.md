# Untitled

[https://facebook.github.io/react-native/docs/network.html](https://facebook.github.io/react-native/docs/network.html)

```javascript
fetch('https://mywebsite.com/endpoint/', { 
    method: 'POST', 
    headers: { 
        Accept: 'application/json', 
        'Content-Type': 'application/json', 
    }, 
    body: JSON.stringify({ 
        firstParam: 'yourValue', 
        secondParam: 'yourOtherValue', 
    }), 
});
```

