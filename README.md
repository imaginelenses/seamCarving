# Seam Carving
## Content Aware Resizing - An application of Seam Carving.

[Seam Carving](https://en.wikipedia.org/wiki/Seam_carving) is an algorithm for content-aware image resizing.

It functions by establishing a number of seams (paths of least importance) in an image and automatically removes seams to reduce image size or inserts seams to extend it. Seam carving also allows manually defining areas in which pixels may not be modified, and features the ability to remove whole objects from photographs.

|Original | Scaling | Croping | Seam Carving | 
|:-------:|:-------:|:-------:|:------------:|
|![Original](https://upload.wikimedia.org/wikipedia/commons/c/cb/Broadway_tower_edit.jpg) |![Scaling](https://upload.wikimedia.org/wikipedia/commons/a/a3/Broadway_tower_edit_scale.png)|![Croping](https://upload.wikimedia.org/wikipedia/commons/e/ef/Broadway_tower_edit_cropped.png)|![Seam Carving](https://upload.wikimedia.org/wikipedia/commons/e/ed/Broadway_tower_edit_Seam_Carving.png)|

## Computing seams
Computing a seam consists of finding a path of minimum energy cost from one end of the image to another.

To do this we use Dynamic Programming.

## References

* [Harvard CS50 - Dynamic Programming](https://youtu.be/0y5UkZc-C8Y)
* [MIT - Introduction to Computational Thinking](https://computationalthinking.mit.edu/Fall20/lecture3/)
