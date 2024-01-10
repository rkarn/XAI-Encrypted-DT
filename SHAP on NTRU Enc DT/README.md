Status:

I attempted to apply SHAP to a decision tree. However, the SHAP model does not satisfy the OPE criterion. The accuracy of the surrogate model significantly decreases when encrypted data is utilized for inference, resulting in a substantial disparity between the accuracy of the primary model and the surrogate model.


I have attached the PDF of the Jupyter notebook demonstrating the application of SHAP for both unencrypted and encrypted decision trees. Notably, the output of the encrypted decision tree (cells 15 and 16) differs from that of the unencrypted decision tree (cells 4 and 5).