# From-Events-to-Spikes-Dataset-Transformation-for-Neuromorphic-Computing


we present a novel approach for generating spike train datasets from event-based datasets. Our approach involves processing the event-based data and generating a sequence of spikes that mimic the activity of neurons in the visual system. The resulting spike train dataset can be used for a variety of downstream applications, including training and testing machine learning models for tasks such as object recognition and motion tracking. The benefits of this approach include the ability to work with high-speed event-based data, the ability to simulate the behavior of neurons more accurately than traditional frame-based approaches, and the potential to improve the accuracy and efficiency of machine learning models.

# DVS128 Gesture Dataset

The DVS Dataset "https://research.ibm.com/interactive/dvsgesture/" used in this investogation, Our algorithm performs the transformation of events stored in a .aedat file to
spike trains. Spike trains are matrices that represent the rate of events for each pixel of a DVS dataset in a given time window. The algorithm processes the events in the .aedat file and preprocesses them to remove duplicates and fill in missing events.

Figure 1(B), shows the results of applying the ”PreprocessEvents” function to gesture 2, in the dataset, highlighting the removal of duplicate events and the filling in of missing events to create a more complete and accurate representation of the spike train. Figure 1(A), illustrates the Spike Train of gesture 1 without the ”PreprocessEvents” function.

![Spike Train Dataset](https://github.com/Rao-Sanaullah/From-Events-to-Spikes-Dataset/blob/main/1.png)


The release Spike Train Dataset can be download from: https://hsbi.sciebo.de/s/0Seqwz6hVUAaUEv


For any help, please contact

Sanaullah (sanaullah@hsbi.de)
