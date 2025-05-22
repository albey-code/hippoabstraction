### Rationale for General Linear Model (GLM) Regressors

On Day 2, participants only saw a sub-set of 7 out of the original 12 objects, namely: objects 2, 4, 6, 7, 8, 9 and 10. I am specifically interested in the neural fMRI-derived activity in ROIs when participants were presented with these objects. To "filter out" or regress out merely the neural activity for these objects, I created 7 seperate regressors. For these, there is no differentiation between the "patch" or "no patch" conditions. 

In addition, I created a seperate regressor for all objects in "patch" and another one for all objects in "no patch".

Lastly, I created a seperate regressor for "button-press". In total, this yielded 10 regressors in the GLM. 

The GLM is the crucial first step for further downstream analyses, e.g., the representational similarity analysis (RSA). From the GLM, I derived beta maps (from whole-brain fMRI activity). Later, I could apply the ROI masks to these beta maps to extract the object-related neural activity.
