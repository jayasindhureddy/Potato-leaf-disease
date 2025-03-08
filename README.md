Potato Leaf Disease Detection 
This project is a deep learning-based system for detecting potato diseases using image classification. The model is trained on a dataset containing healthy and diseased potato leaves.
1.	Input
•	The process starts with an image of leaves, some of which may have diseases.
•	This image serves as the raw data for further analysis.
2.	Instance Segmentation
•	This step identifies individual leaves in the image.
•	Each detected leaf is assigned a distinct label and highlighted with different colors.
•	It allows the system to focus on each leaf separately for further analysis.

3.	Classification
•	Each segmented leaf is classified as either healthy or diseased.
•	The model categorizes diseases such as "Late blight" or "Healthy" based on visual characteristics.
•	This classification helps in understanding the spread of diseases.
4.	Semantic Segmentation
•	The diseased regions within each leaf are segmented.
•	This step highlights specific areas affected by disease rather than just labeling the entire leaf.
•	It provides a more precise analysis of the disease’s spread.
5.	Output
•	The final output includes the segmented leaf images with identified disease proportions.
•	A quantified measure (e.g., "Disease proportion: 0.38") indicates how much of the leaf is affected.
•	This information is useful for assessing the severity of the disease and making agricultural decisions.
