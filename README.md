# ether
```
function addEvent(obj,EventName,fn){
			if (window.addEventListener) {
				obj.addEventListener(EventName,fn,false);
			}else{
				obj.attachEvent(EventName,fn);
			}
}
```
