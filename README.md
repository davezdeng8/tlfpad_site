## Temporal LiDAR Frame Prediction for Autonomous Driving

### Additional Flow Visualizations

Red points are from t and green points are from t+1. The magnitude of the vectors are visualized on this scale:

![colorbar](https://github.com/davezdeng8/tlfpad_site/blob/master/images/colorbar.png)

**Scene 1**
In this scene, the ego vehicle is driving past a full parking lot. The images show the predicted motion vectors of the parked cars. Here PN++ w/ DS outperforms  the other architectures, producing smooth, accurate flow for the cars.

FN3DOOB

![FN3DOOB 0655](https://github.com/davezdeng8/tlfpad_site/blob/master/images/FlowNet3DOOB_0655_vis.png)

FN3DA

![FN3DA 0655](https://github.com/davezdeng8/tlfpad_site/blob/master/images/FlowNet3D_0655_vis.png)

PN++ w/ DS

![PN++DS 0655](https://github.com/davezdeng8/tlfpad_site/blob/master/images/PPNPPD_0655_vis.png)

PN++ w/o DS

![PNNDS 0655](https://github.com/davezdeng8/tlfpad_site/blob/master/images/PPNPP_0655_vis.png)

EC w/ DS

![ECDS 0655](https://github.com/davezdeng8/tlfpad_site/blob/master/images/PCPD_0655_vis.png)

EC w/o DS

![ECNDS 0655](https://github.com/davezdeng8/tlfpad_site/blob/master/images/PCPb_0655_vis.png)

**Scene 2**
In this scene, the ego vehicle is moving forward, and there is a car behind it travelling at about the same velocity. This car is at the bottom left of the images. PN++ w/ DS, EC w/ DS, and EC w/o DS are able to capture the global movement of the scene, while also predicting that the car moves independently from the rest of the scene ie. it stays still relative to the ego vehicle's coordinate frame. 

FN3DOOB

![FN3DOOB 0757](https://github.com/davezdeng8/tlfpad_site/blob/master/images/FlowNet3DOOB_0757_vis.png)

FN3DA

![FN3DA 0757](https://github.com/davezdeng8/tlfpad_site/blob/master/images/FlowNet3D_0757_vis.png)

PN++ w/ DS

![PN++DS 0757](https://github.com/davezdeng8/tlfpad_site/blob/master/images/PPNPPD_0757_vis.png)

PN++ w/o DS

![PNNDS 0757](https://github.com/davezdeng8/tlfpad_site/blob/master/images/PPNPP_0757_vis.png)

EC w/ DS

![ECDS 0757](https://github.com/davezdeng8/tlfpad_site/blob/master/images/PCPD_0757_vis.png)

EC w/o DS

![ECNDS 0757](https://github.com/davezdeng8/tlfpad_site/blob/master/images/PCPb_0757_vis.png)
