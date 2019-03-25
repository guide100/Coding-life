Coding life
===
# js-important
## object.keys
<br/>
![xxx](pics/object-keys.jpg)
<img src="pics/object-keys.jpg" width="600px"/>

## debounce & throttle
```javascript
function debounce(fn){
    var timer;
    return function(){
        if(timer) 
        clearTimeout(timer);
        timer=setTimeout(()=>fn.call(this,arguments),1000);
    }
}

function throttle(fn){
    let timer;
    return function(){
        if(timer) 
        return;
        timer=setTimeout(()=>{fn.call(this,arguments);console.log(arguments);timer=null;},1000);
    }
}
```
![blockchain](https://ss0.bdstatic.com/70cFvHSh_Q1YnxGkpoWK1HF6hhy/it/
u=702257389,1274025419&fm=27&gp=0.jpg "区块链")

# java-important