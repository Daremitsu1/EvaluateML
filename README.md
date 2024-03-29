# Evaluate a machine learning model
\nThis sample project has one tutorial to teach you about evaluating a machine learning model using Watson OpenScale.
## Click a tutorial to get started
- <a href=\"https://dataplatform.cloud.ibm.com/docs/content/wsj/getting-started/get-started-openscale.html\" rel=\"noopener noreferrer\">Evaluate a machine learning model
</a>: Deploy a trained model to a deployment space, and evaluate the model in OpenScale.\n\nThe tutorial instructions open in a new window.\n\n## Required services\n\nVerify your services:\n\n1. From the Cloud Pak for Data navigation menu, choose **Services &gt; Service instances** and look for these services:\n    - **Watson Studio**: For building models.\n    - **Watson Machine Learning**:  For saving and deploying the model.\n    - **watsonx.governance**: For monitoring models.\n2. If necessary, click **Add service** to provision any missing services.\n\n## Assets in this sample project\nThis project contains these sample data assets on the **Assets** page:\n- The **Data Fabric Trial - Db2 Warehouse** connection to the data for training the model.\n- The **GoldenBank_HoldOutData.csv** data set for evaluating the model.\n- The **Mortgage Approval Prediction Model** machine learning model to evaluate.\n\nThis project also contains two sample notebooks. Follow the instructions in the first few cells of the notebook to configure the project token and API key. Then execute the notebooks step-by-step.\n- **monitor-wml-model-with-watson-OpenScale**: 
This notebook performs the following functions: 
- Loads the model deployed in the deployment space.
- Programmatically sets up and configure OpenScale.     
- Creates a data mart for the model with Watson OpenScale and configure OpenScale to monitor that deployment, and inject records and measurements for viewing in the OpenScale Insights dashboard.
- Creates a de-biased model if Watson OpenScale reports a bias.
- Creates explanations for mortgage approval predictions on sample records.
### Terms and Conditions
This project contains Sample Materials, provided under this <a href=\"https://github.com/IBM/Industry-Accelerators/blob/master/CPD%20SaaS/LICENSE\" rel=\"noopener noreferrer\">license</a>. <br>\nLicensed Materials - Property of IBM. <br>\n© Copyright IBM Corp. 2024. All Rights Reserved. <br>\nUS Government Users Restricted Rights - Use, duplication or disclosure restricted by GSA ADP Schedule Contract with IBM Corp.<br>\n\n\n"}
