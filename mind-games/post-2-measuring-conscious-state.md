### 2) The Mind Game: trying to measure conscious state

### May 30, 2012

### (trying to predict introspection results from EEG and similar things)

Various measures might correlate with conscious states.

The most obvious thing to record is multi-channel EEG (if possible with a high-end helmet), but many other measures can be taken (various brain imaging, skin conductance, cardiomonitor, voice, accelerometer held in one’s hand while moving, “magic measurement machines” with unknown principles of operation, etc). It is important to time-stamp the recordings.

The next step is to provide various methods for **extracting a variety of features** from those recordings. This is quite an open-ended project, there is a great diversity of possible features, and many existing software components can be used. For example, the dominant frequency of the EEG is one of the many possible features. At the beginning it’s fine to extract features offline, although at some later point it will be very useful to be able to extract some subset of features in real time.

In parallel, it is important to maintain a time-stamped log where a person would record the results of introspection on this person’s own conscious state, and how this state changes with time.

Then various schemes from machine learning (various **predictive modelling** schemes) can be applied to learn to predict this person’s conscious state from the features of measurements. In the process of doing so one can learn which features are especially meaningful in terms of their predictive power.

It is likely that this protocol would need to be repeated for every person wishing to play the Mind Game, although it is possible that some common features would also be discovered.

### May 12, 2019 comment

7 years later: it is very obvious that this was written before the start of deep learning revolution (Dec. 2012).

In particular, consider all the emphasis on **feature extraction**, whereas today it is customary to let a deep neural net to figure out the right features on its own...

### Oct 7, 2021 comment

There is a nice library with a uniform API for a wide class of devices, and with bindings for a variety of programming languages including Julia:

https://brainflow.org/

https://brainflow.readthedocs.io/en/stable/

https://github.com/brainflow-dev/brainflow/

https://github.com/brainflow-dev/brainflow/tree/master/julia-package

### Oct 20, 2021 comment

What class of brain imaging devices such as EEGs is sufficient? 

It is almost certain that a high-end EEG helmet is sufficient, see for example
_Natural image reconstruction from brain waves: a novel visual BCI system with native feedback_,
by Grigory Rashkov et al (2019): https://www.biorxiv.org/content/10.1101/787101v3

If one can reconstruct images from an EEG recording to the extent reported in this paper,
one can be reasonably confident that sufficient information about all aspects of
a cognitive state of a person is transmitted.

But would something close to an inexpensive wireless dry-contact few electrodes consumer EEG device
such as **Muse** be sufficient for meaningful results? This remains to be seen.

### Dec 3, 2023 comment

I was able to make BrainFlow on a Windows 10 laptop to see an old MUSE 2016 even without a dongle (--board-id 39),
however I had to first install https://github.com/kowalej/BlueMuse, and only then BrainFlow started to work OK
with this hardware.
