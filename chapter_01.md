# Überschrift

<!-- data-type="line" -->
| x  | y   |
| :--------- | :--------- |
| 0          | <script input default="0">@input</script>  |
| 0.5        | <script input default="0">@input</script>  |
| 1        | <script input default="0">@input</script>  |
| 1.5        | <script input default="0">@input</script>  |

<!-- calc: <script input default="@0">@input</script> -->

<!-- Test -->

| Header 1   | Header 2   |
| :--------- | :--------- |
| 1     | @calc(1)     |


<!--
calc: <script input default="0">@input</script>
-->

| Header 1   | Header 2   |
| :--------- | :--------- |
| 1     | @calc(1)     |

# Überschrift
<!-- 
calc: <script input default="?">@input</script>
-->
<!-- data-type="line" -->
| Header 1 | Header 2 |
| :--- | :--- |
| 1     | @calc()     |
| 2     | @calc()     |__