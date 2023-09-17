<script type="text/javascript">
    document.getElementById("myButton").onclick = function () {
        location.href = "http://www.google.com";
    };
</script>

```{r, echo=F}
actionButton("myButton", "Redirect")
```
