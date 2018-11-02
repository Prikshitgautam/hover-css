# hover-css
css
<div class="zoom-image">
	<img src="image/vege.jpg">

</div>

#css

.zoom-image{
width:500px;
height:250px;
overflow:hidden;
text-align:center;
}

img{
max-width:100%;
max-height:100%;
transition:0.75s;
}
.zoom-image:hover img{
transform:scale(1.2);
}
