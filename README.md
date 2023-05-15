# Dry_Beans_Classification
Can you predict the type of a dry bean from its shape features?
## Dataset Description
The dataset consists of features describing the shape of the bean and you're required to predict it's type.
## File descriptions
train.csv - the training set.<br/>
test.csv - the test set.<br/>
sample_submission.csv - a sample submission file in the correct format <br/>
## Data fields
ID - an ID for this instance <br/>
Area - (A), The area of a bean zone and the number of pixels within its boundaries. <br/>
Perimeter - (P), Bean circumference is defined as the length of its border.<br/>
MajorAxisLength - (L), The distance between the ends of the longest line that can be drawn from a bean.<br/>
MinorAxisLength - (l), The longest line that can be drawn from the bean while standing perpendicular to the main axis.<br/>
AspectRatio - (K), Defines the relationship between L and l.<br/>
Eccentricity - (Ec), Eccentricity of the ellipse having the same moments as the region.<br/>
ConvexArea - (C), Number of pixels in the smallest convex polygon that can contain the area of a bean seed.<br/>
EquivDiameter - (Ed), The diameter of a circle having the same area as a bean seed area.<br/>
Extent - (Ex), The ratio of the pixels in the bounding box to the bean area.<br/>
Solidity - (S), Also known as convexity. The ratio of the pixels in the convex shell to those found in beans.<br/>
Roundness - (R), Calculated with the following formula: (4piA)/(P^2) <br/>
Compactness - (CO), Measures the roundness of an object: Ed/L <br/>
ShapeFactor1 - (SF1) <br/>
ShapeFactor2 - (SF2) <br/>
ShapeFactor3 - (SF3)<br/>
ShapeFactor4 - (SF4) <br/>
y - the class of the bean. It can be any of BARBUNYA, SIRA, HOROZ, DERMASON, CALI, BOMBAY, and SEKER.<br/>
