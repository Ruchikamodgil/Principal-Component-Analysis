# Principal-Component-Analysis <br>
``` Principal component analysis (PCA)```  is a statistical procedure that is used to reduce the dimensionality. It uses an orthogonal transformation to convert a set of observations of possibly correlated variables into a set of values of linearly uncorrelated variables called principal components.<br> 
<b> It is often used as a dimensionality reduction technique.<br></b>
You can reduce dimensionality by limiting the number of principal components to keep based on cumulative explained variance.<br>
Particularly, in this, we need to transform variables into a new set of variables. As these are a linear combination of original variables. These new set of variables are known as principal components.
<br>
<br>
## Steps:<br>
-> Standardize the data<br>
-> Covariance: Find the covariance matrix for your dataset<br>
-> Eigenvectors: Find the eigenvectors of that matrix <br>
-> Ordering: Sort the eigenvectors/'dimensions' from biggest to smallest variance <br>
-> Projection / Data reduction: Use the eigenvectors corresponding to the largest variance to project the dataset into a reduced- dimensional space <br>
