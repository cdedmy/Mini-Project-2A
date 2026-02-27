# Mini-Project-2A
Both of these projects should work just by running in collab without any changes. They just show the same data in different formats. 

In this project, I built a simple end-to-end workflow to record accelerometer data from a micro:bit and classify motion state as either steady or shaking. I wrote a MakeCode/Python data-logging script to collect x/y/z acceleration over time and recorded a ~20-second sequence that alternates between 5 seconds still and 5 seconds shaking (repeated twice). The recorded data was transferred to a computer and loaded into a Python notebook for preprocessing (cleaning, formatting, and feature selection).

Using the notebook, I trained a binary classifier (logistic regression) to predict the motion state from the accelerometer signals and evaluated performance using classification accuracy. Finally, I discussed ways to improve the model, such as collecting more training data, balancing classes, adding better features (e.g., acceleration magnitude, rolling variance/energy), filtering noise, and testing additional models (e.g., decision trees, random forests, SVM, or rule-based thresholds).
