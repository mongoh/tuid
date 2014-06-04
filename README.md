tuid
====

Truly Unique ID - A pure javascript unique id generator that guarantees uniqueness globally.

##Usage
Download and include tuid.js<br/>
```<script type="text/javascript" src="tuid.js"></script>```

##Example

```
<script>
    // Pass the tuid() function a callback that will handle the generated id
    tuid(function(tuid){
      console.log(tuid);
    });
</script>
```
