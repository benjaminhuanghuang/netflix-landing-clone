# Build a Netflix Landing Page Clone with HTML, CSS & JS
- https://www.youtube.com/watch?v=P7t13SGytRk
- https://codepen.io/bradtraversy/pen/yWPONg


## 





## put image in the middle
```
.showcase-top {
	position: relative;
	z-index: 2;
	height: 90px;
}

.showcase-top img {
	width: 170px;
	position: absolute;
	top: 50%;
	left: 50%;
	transform: translate(-50%, -50%);
	margin-left: 0;
}
```

## decorate image
```
.showcase::after {


}
```

## grid 
```
.tabs .container {
	display: grid;
	grid-template-columns: repeat(3, 1fr);
	grid-gap: 1rem;
	align-items: center;
	justify-content: center;
	text-align: center;
}
```