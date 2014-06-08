tuid
====

Truly Unique ID - A pure javascript unique id generator that guarantees uniqueness globally.<br/>

The generated id is a string with the first 32 characters being system generated, and the remaining digits representing the number of milliseconds since epoch (a handy timestamp!). <br/>

E.g.:<br/>
id -> ufqSJh_5h9sal7m_EC1R5EZIB59ZOwVP1401910420816<br/>
system_generated -> ufqSJh_5h9sal7m_EC1R5EZIB59ZOwVP<br/>
milliseconds since epoch -> 1401910420816<br/><br/>

This is especially useful for client-side id generation. It's also not monotonically increasing!

##Demo
See the demo on <a href="http://jsfiddle.net/9AsmJ/1/" target="_blank">jsFiddle<a>

##Usage
Download and include tuid.js<br/>
```<script type="text/javascript" src="tuid.js"></script>```

##Example

```
<script>
    // Pass the tuid() function a callback that will handle the generated id
    tuid(function(tuid){
      console.log(tuid); // => ufqSJh_5h9sal7m_EC1R5EZIB59ZOwVP1401910420816 
    });
</script>
```
