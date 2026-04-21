# Lab-7-Polynomial-Interpretation
To obtain the linear/polynomial interpolation using Newton/Lagrange’s polynomial

The problem involved a dataset where the values of x and corresponding f(x) were given, and the task was to estimate intermediate values using interpolation techniques. Polynomial interpolation is based on the concept that for n data points, there exists a unique polynomial of degree (n−1) that passes through all the points . A first-order polynomial connects two points with a straight line, a second-order polynomial forms a parabola through three points, and a third-order polynomial creates a cubic curve through four points.

The results indicated distinct variations among the interpolation orders. First-order interpolation delivered smoother results, though with reduced accuracy. Second-order interpolation enhanced the approximation but revealed discrepancies because of the inclusion of non-local points. Third-order interpolation offered increased flexibility but also resulted in greater variations due to its high sensitivity to point selection. At the boundary points, the interpolated values coincided precisely with the original values because those points were explicitly used in the calculation.

From this study, I discovered that the precision of interpolation is influenced more by the selection of data points than by the polynomial's degree alone. Raising the order doesn't always enhance accuracy and may occasionally cause instability. It is crucial to verify that interpolation nodes are unique and near the target value to obtain dependable outcomes.

In summary, Lagrange interpolation serves as a useful approach for estimating intermediate values, but its effectiveness relies significantly on appropriate point selection. The tailored method of adjusting endpoints and modifying intermediate points is legitimate but brings in non-local influences that may decrease precision. Optimal results are achieved when interpolation points are selected as near as feasible to the target value

