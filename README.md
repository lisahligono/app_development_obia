# Application Development (Object Based Image Analysis)
<h2> Morphology Assignment</h2>
Minkowski addition and subtraction are two operations used in mathematical morphology to modify the shape of objects in an image.
<h3> Minkowski Addition</h3>
Minkowski addition is an operation that takes two sets and creates a new set by adding the elements of one set to the elements of the other set. In simple terms, imagine that you have two different shapes, like a square and a circle. If you were to perform Minkowski addition on these shapes, you would create a new shape that is formed by adding the two shapes together.
       <h3> A ⊕ B = {a + b : a ∈ A, b ∈ B}</h3>
where ⊕ represents the Minkowski addition operator, + represents the pointwise addition of two sets, and a and b represent points in the sets A and B, respectively
        
<h3> Minkowski Subtraction</h3>
Minkowski subtraction, on the other hand, is an operation that takes two sets and creates a new set by removing the elements of one set from the elements of the other set. In simple terms, imagine that you have a shape, like a square, and you want to remove the shape of a smaller object, like a circle, from the square. If you were to perform Minkowski subtraction on these shapes, you would create a new shape that is formed by subtracting the circle from the square. 
        <h3> A ⊖ B = {a ∈ A : (a + B) ⊆ A} </h3>
where ⊖ represents the Minkowski subtraction operator, + represents the pointwise addition of two sets, and a and b represent points in the sets A and B, respectively.
Example in python: [![Binder](https://mybinder.org/badge_logo.svg)(https://mybinder.org/v2/gh/lisahligono/app_development_obia.git/HEAD)
