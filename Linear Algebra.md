In CS Vector is pretty much a fancy name for list.
Linear Aalgebra helps in describing the manipulations of space and solve the systems of linear equations. 
Origin in a Cartesian plane is the centre of space and the root of all vectors.
Linear algebra revolves around two fundamental concepts i.e. vector addition and scalar multiplication.
The process of stretching , squishing or sometimes reversing the direction of the vector is called sacling.
i hat and j hat are called the basis of an xy coordinate system.
If one vector is equal to the sum of scalar multiples of other vectors, it is said to be a linear combination of the other vectors. 
Span is the set of all the linear combinations of a number vectors.
If at least one of the vectors in among 3 or more vectors can be written as a linear combination of the others, then they is said to be linearly dependent, or if a vector is already in the span of other vectors then it is a redundant and linearly dependent vector.
If a vector add to te span of other vectors then it is called linearly independent.
The basis of a vector space is the set of linearly independent vectors that span the full space.
Linear Transformations are the ways to move around space.
Linear Transformation needs just the coordinates of where each of the basis vectors i and j land.
Linear Transformation of matrices have two rules, i.e. the origin must stay at the same point and the vector and grid lines must not be curved.
Every time a matrix can be interpreted as a certain transformation of space.
Composition is a way of chaining transformations together.
Matrix multiplication is not commutative whereas it is assosiative.
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
Inverse of a matrix is a unique transformation , that simply undo the original trasformation and you end up where you started.
A*A^-1=identity tranformation or identity matrix, i.e. [1 0 , 0 1].
The rank of a matrix  is the dimension of the vector space generated or spanned by its columns. This corresponds to the maximal number of linearly independent columns of a matrix. This, in turn, is identical to the dimension of the vector space spanned by its rows. In simple terms rank is the number of dimensions in the output of any transformation.
Column space is the span of all possible outputs after a transformation of the matrix.
The set of all transformed vectors that land on the origin are called the null space. 
When two vectors are pointing in the same direction the dot product is positive, when they are perpendicular then the dot product is 0 and when they point in opposite directions then the dot product is negative. 
