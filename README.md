# NCKU_resilient-case

Declaration: <br />
Sorry, I can't provide any dataset or experiment details without my instructors' permission. <br>
If you want futher information about this research, just feel free to contact me.

Experiment Info: <br />
This experiment explores how the emotion affects the subjects' reactions. By reviewing subjects' brain activities corresponding to various testing cases, we can gain more general perspective about the relationship between emotion and decisions as well as the principles of our brains' reactions.

Work Flow:

1. Converting raw fMRI image data into NIFTI files with MRIcroGL.
3. Extracting the event timepoints during fMRI scanning session and convert the data into three-columns timing files (see TimeFile_Processing.ipynb)
4. fMRI data analysis by FSL.
5. Extracting the significant area of brain info from the result of FSL (see BrainExtraction.ipynb)
6. Visualizing and implementing statistical testing on behavior data.(see RainCloud.ipynb)
7. Implement Drift Diffusion Models on the behavior data.(see DDM.ipynb)

Analysis Result (Partial):
 ![Alt text](https://github.com/aposkend/NCKU_resilient-case/blob/main/NCKU_github/result_examples.png)

Visualization Result (Partial)
![Alt text](https://github.com/aposkend/NCKU_resilient-case/blob/main/NCKU_github/visualization_example.png)
