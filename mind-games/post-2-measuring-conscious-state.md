### 2) The Mind Game: trying to measure conscious state

May 30, 2012

(trying to predict introspection results from EEG and similar things)

Various measures might correlate with conscious states.

The most obvious thing to record is multi-channel EEG (if possible with a high-end helmet), but many other measures can be taken (various brain imaging, skin conductance, cardiomonitor, voice, accelerometer held in one’s hand while moving, “magic measurement machines” with unknown principles of operation, etc). It is important to time-stamp the recordings.

The next step is to provide various methods for extracting a variety of features from those recordings. This is quite an open-ended project, there is a great diversity of possible features, and many existing software components can be used. For example, the dominant frequency of the EEG is one of the many possible features. At the beginning it’s fine to extract features offline, although at some later point it will be very useful to be able to extract some subset of features in real time.

In parallel, it is important to maintain a time-stamped log where a person would record the results of introspection on this person’s own conscious state, and how this state changes with time.

Then various schemes from machine learning (various predictive modelling schemes) can be applied to learn to predict this person’s conscious state from the features of measurements. In the process of doing so one can learn which features are especially meaningful in terms of their predictive power.

It is likely that this protocol would need to be repeated for every person wishing to play the Mind Game, although it is possible that some common features would also be discovered.

