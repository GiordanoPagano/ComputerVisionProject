# ComputerVisionProject: End-to-End Object Detection with Transformers

The main ingredients of the DEtection TRansformer or DETR, are a set-based global loss that forces unique predictions via bipartite matching, and a transformer encoder-decoder architecture. 
Given a fixed small set of learned object queries, DETR reasons about the relations of the objects and the global image context to directly output the final set of predictions in parallel. The model does not require a specialized library, unlike many other modern detectors. DETR demonstrates accuracy and run-time performance on par with the well-established and highly-optimized Faster RCNN baseline on the challenging COCO object detection dataset. Moreover, DETR can be easily generalized to produce panoptic segmentation in a unified manner.

# How to use
The code is on a "ipynb" file, so it can be uploaded on a CoLab session and then each cell can been run sequentially.
Since the training of a transformer require a lot of computational resources, the free version of CoLab will shut down the running session while training.
Therefore are done only few ephocs of training and the results obtained are not satisfactory.
