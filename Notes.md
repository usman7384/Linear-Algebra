# The Essence of Linear Algebra

In CS Vector is pretty much a fancy name for list.

Linear Aalgebra helps in describing the manipulations of space and solve the systems of linear equations. 

Origin in a Cartesian plane is the centre of space and the root of all vectors.

Linear algebra revolves around two fundamental concepts i.e. vector addition and scalar multiplication.

The process of stretching , squishing or sometimes reversing the direction of the vector is called sacling.

i hat and j hat are called the basis of an xy coordinate system.

If one vector is equal to the sum of scalar multiples of other vectors, it is said to be a linear combination of the other vectors. 

#### Span
Span is the set of all the linear combinations of a number vectors.

#### Linearly  Dependent and independent Vectors
If at least one of the vectors in among 3 or more vectors can be written as a linear combination of the others, then they is said to be linearly dependent, or if a vector is already in the span of other vectors then it is a redundant and linearly dependent vector.

If a vector add to te span of other vectors then it is called linearly independent.

#### Basis of a Vector
The basis of a vector space is the set of linearly independent vectors that span the full space.

#### Linear Transformation
Linear Transformations are the ways to move around space.

Linear Transformation needs just the coordinates of where each of the basis vectors i and j land.
Linear Transformation of matrices have two rules, i.e. the origin must stay at the same point and the vector and grid lines must not be curved.

Every time a matrix can be interpreted as a certain transformation of space.

#### Matrix Multiplication as Compositions
Composition is a way of chaining transformations together.

Matrix multiplication is not commutative whereas it is assosiative.


#### Determinant
The factor by which the linear transformation changes any area is called the determinant of that transformation.

The determinant of a 2D transformation is 0 if it squishes all of the space onto a single line or onto a single point.

The determinant of a 3D transformation is 0 if it squishes all of the space onto a single plane or onto a single point.

Whenever in the transformation , the orient of space is inverted the determinant will be negative where as the absolute value of determinant will still show that by how much factor is the area changed.

As in 2D transformation the area get scaled , similarly in 3D transformation the volume gets scaled.

As in 2D transformation we take a 1 by 1 square whose edges are resting on the basic vector i and j , and then we find the scaling of area or transformation of other vectors, similarly in 3D tranformation we take a 1 by 1 by 1 cube whose edges are resting in the basis vector.

When the determinant of a 3D matrix is 0 then the columns of the matrix are linearly dependent.

Let X be a vector matrix of variables, V be a matrix of constants then, 

                                 AX=V  where A is also a constant matrix.
                 
So while doing the geometric interpretation of this system of equations we see that X is some vector matrix which after transformation (A corresponds to some linear transformation) lands on V.


#### Inverse of a Matrix
Inverse of a matrix is a unique transformation , that simply undo the original trasformation and you end up where you started.

A*A^-1=identity tranformation or identity matrix, i.e. [1 0 , 0 1].


#### Rank of a Matrix
The rank of a matrix  is the dimension of the vector space generated or spanned by its columns. This corresponds to the maximal number of linearly independent columns of a matrix. This, in turn, is identical to the dimension of the vector space spanned by its rows. In simple terms rank is the number of dimensions in the output of any transformation.


#### Column Space
Column space is the span of all possible outputs after a transformation of the matrix.


#### Null Space
The set of all transformed vectors that land on the origin are called the null space. 


#### Dot Product
When two vectors are pointing in the same direction the dot product is positive, when they are perpendicular then the dot product is 0 and when they point in opposite directions then the dot product is negative. 

Any time there is a linear transformation whose output space is a number line , no matter how it was defined there is going to be some unique vector V corresponding to that transformation.


#### Duality
Duality is natural but surprising correspondence between two types of mathematical things.

The dual of some vector from a space to some one dimension is a certain vector in that space.

Dot product is a useful geometric tool to understand projections and to check wether they point is same direction or not.


#### Cross Product
In cross product Order matters i.e. w*x=-w*x.

Cross product is a vector.

Direction of cross product can be found by cross product.

Measuring the "perpendicularity" is the same as measuring the area between the paralelogram formed by the two vectors, the more perpendicularity, higher the area that is formed.

The main motivation behind defining cross product is that the duality between planes and vectors perpendicular to them in 3D allows us to identify complicated mathematical-objects with vectors.


#### Cramer's Rule
Cramer’s Rule uses determinants to solve for a solution to the equation Ax=b, when A is a square matrix.

Cramer’s Rule only works on square matrices that have a non-zero determinant and a unique solution.

#### Change of Basis

i hat and j hat are the two basis vectors of the standard coordinate system.

Change of basis is a technique applied to finite-dimensional vector spaces in order to rewrite vectors in terms of a different set of basis elements. It is useful for many types of matrix computations in linear algebra and can be viewed as a type of linear transformation.

#### Eigenvector and eigenvalue

An eigenvector is a vector whose direction remains unchanged when a linear transformation is applied to it.

                                             Av = λv

In linear algebra, an eigenvector or characteristic vector of a linear transformation is a nonzero vector that changes at most by a scalar factor when that linear transformation is applied to it. The corresponding eigenvalue, often denoted by \lambda, is the factor by which the eigenvector is scaled.
