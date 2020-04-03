# jQuery Easing
Add easing functions to jQuery. Based on easing equations from Robert Penner.

## Install
1. Include jQuery:
```
<script src="https://code.jquery.com/jquery-3.4.1.min.js" integrity="sha256-CSXorXvZcTkaix6Yvo6HppcZGetbYMGWSFlBw8HfCJo=" crossorigin="anonymous"></script>
```
2. Include `jquery.easing.js` below it:
```
<script src="https://{YOUR_HOST}/jquery.easing.js"></script>
```

## Example Install
```
<head>
...
<script src="https://code.jquery.com/jquery-3.4.1.min.js" integrity="sha256-CSXorXvZcTkaix6Yvo6HppcZGetbYMGWSFlBw8HfCJo=" crossorigin="anonymous"></script>
<script src="https://{YOUR_HOST}/jquery.easing.js"></script>
...
</head>
```

## Usage
```
$('#el').stop(true, false).animate({
  top: 10px,
  left: 10px
}, 500, 'easeOutCubic');
```

## Reference
- http://www.robertpenner.com/easing
- https://jquery.com
- https://code.jquery.com
- https://easings.net
