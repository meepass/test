# test<!DOCTYPE html>
<html>
<title>Website Template</title>
<style>
* {
box-sizing: border-box;
}
h1 {
text-align: center;
}
.outer-grid {
display: flex;
flex-wrap: wrap;
padding: 0 4px;
}
.inner-grid {
flex: 25%;
max-width: %;
padding: 0 4px;
}
.inner-grid img {
margin-top: 8px;
width: 100%;
padding: 10px;
}
@media screen and (max-width: 800px) {
.inner-grid {
flex: 50%;
max-width: 50%;
}
}
@media screen and (max-width: 600px) {
.inner-grid {
flex: 100%;
max-width: 100%;
}
}
</style>
<body>
<h1>Responsive Image Grid Example</h1>
<div class="outer-grid">
<div class="inner-grid">
<img
src="https://images.pexels.com/photos/1083822/pexels-photo-1083822.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500"
/>
<img
src="https://images.pexels.com/photos/1083822/pexels-photo-1083822.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500"
/>
<img
src="https://images.pexels.com/photos/1083822/pexels-photo-1083822.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500"
/>
</div>
<div class="inner-grid">
<img
src="https://images.pexels.com/photos/3805102/pexels-photo-3805102.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500"
/>
<img
src="https://images.pexels.com/photos/3805102/pexels-photo-3805102.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500"
/>
<img
src="https://images.pexels.com/photos/3805102/pexels-photo-3805102.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500"
/>
</div>
<div class="inner-grid">
<img
src="https://images.pexels.com/photos/3863778/pexels-photo-3863778.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500"
/>
<img
src="https://images.pexels.com/photos/3863778/pexels-photo-3863778.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500"
/>
<img
src="https://images.pexels.com/photos/3863778/pexels-photo-3863778.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500"
/>
</div>
</div>
</body>
</html>
