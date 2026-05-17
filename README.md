## Task 6: CNN Concept Explanation
1.The convolution layer extracts important visual features from images.
Examples:
edges,
scratches,
dents,
stains,
textures.

2.Pooling is used to reduce the size of feature maps while keeping the most important information.
The most common type is Max Pooling, which selects the maximum value from a small region.
Benefits of pooling:
reduces computation,
speeds up training,
reduces overfitting,
keeps important visual features.

3.ReLU (Rectified Linear Unit) is an activation function used after convolution layers.It is simple and fast,helps deep networks learn efficiently,reduces vanishing gradient problems.

4.CNNs are designed specifically for image data.
Advantages of CNNs:
preserve spatial information,
automatically learn features,
require fewer parameters,
work efficiently on large images.
Regular feed-forward neural networks is not used becuase it flatten images immediately,casued lose of image structure and requires very large numbers of parameters.

## Task 7: Business Use Case Mapping

Manufacturing Quality Inspection

This CNN-based computer vision system can be used in the manufacturing industry for automated quality inspection.
Real-World Application-Factories can install cameras on production lines to capture product surface images in real time.
The CNN model can automatically classify products into: normal, scratch, dent, stain. 
Defective products can then be removed automatically before packaging or shipment.

Benefits of This Solution
Faster Inspection-Inspects products in real time
Improved Accuracy-Detects defects consistently
Reduced Human Error-Minimizes manual inspection mistakes
Lower Costs-Reduces labor and inspection costs
Better Product Quality- Improves customer satisfaction
