**1.** **Methodology**

a. The user uploads a CSV dataset and provides weights, impacts, and an email address through a web interface.
b. The backend receives the inputs and loads the dataset for processing.
c. The decision matrix is normalized to bring all criteria to a common scale.
d. Normalized values are multiplied by their respective weights.
e. Ideal best and ideal worst values are identified based on the impacts.
f. Euclidean distances from the ideal best and worst are calculated.
g. TOPSIS scores are computed and alternatives are ranked accordingly.
h. The final ranked results are saved as a CSV file and sent to the user via email.
