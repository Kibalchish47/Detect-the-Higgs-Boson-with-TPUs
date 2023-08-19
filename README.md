# Detect-the-Higgs-Boson-with-TPUs

This is a small project of mine that originally started as a Kaggle.com guided project for the "Intro to Deep Learning" course, but that evolved into a more sofisticated model. 

## Searching for the Higgs Boson
The Standard Model is a theory in particle physics that describes some of the most basic forces of nature (and the most successful theory yet!). One fundamental particle, the Higgs boson, is what accounts for the mass of matter. First theorized in the 1964, the Higgs boson eluded observation for almost fifty years. In 2012, it was finally observed experimentally at the Large Hadron Collider. These experiments produced millions of gigabytes of data.

Large and complicated datasets like these are where deep learning excels. In this notebook, we'll build a Wide and Deep neural network to determine whether an observed particle collision produced a Higgs boson or not.

## The Collision Data
The collision of protons at high energy can produce new particles like the Higgs boson. These particles can't be directly observed, however, since they decay almost instantly. So to detect the presence of a new particle, we instead observe the behavior of the particles they decay into, their "decay products".

The Higgs dataset contains 21 "low-level" features of the decay products and also 7 more "high-level" features derived from these.