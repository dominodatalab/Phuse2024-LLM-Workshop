# Domino Hands-On Retrieval Augmented Generation Workshop

#### In this workshop you will work through an end-to-end workflow broken into various labs to -

* Read in data from a live source
* Prepare your data in an IDE of your choice, with an option to leverage distributed computing clusters
* Train several models in various frameworks
* Compare model performance across different frameworks and select best performing model
* Deploy model to a containerized endpoint and web-app frontend for consumption
* Leverage collaboration and documentation capabilities throughout to make all work reproducible and sharable!


# Section 1: Project Set Up

### Lab 1.1 - Git
text

<p align="center">
<img src = images/account_settings.png width="800">
</p>

<p align="center">
<img src = images/git_credentials.png width="800">
</p>

<p align="center">
<img src = images/add_credentials.png width="800">
</p>

<p align="center">
<img src = images/git_token.png width="800">
</p>

### Lab 1.2 - Project Template
text

<p align="center">
<img src = images/projects_templates.png width="800">
</p>

<p align="center">
<img src = images/llm_template.png width="800">
</p>

<p align="center">
<img src = images/projects_templates.png width="800">
</p>

<p align="center">
<img src = images/create_project.png width="800">
</p>

<p align="center">
<img src = images/new_project1.png width="800">
</p>

<p align="center">
<img src = images/new_project2.png width="800">
</p>

<p align="center">
<img src = images/project_overview.png width="800">
</p>

### Lab 1.3 - Data Source
text

<p align="center">
<img src = images/data_source1.png width="800">
</p>

<p align="center">
<img src = images/AddS3.png width="800">
</p>

### Lab 1.4 - Workspace
text

<p align="center">
<img src = images/workspace1.png width="800">
</p>

<p align="center">
<img src = images/workspace2.png width="800">
</p>

<p align="center">
<img src = images/workspace3.png width="800">
</p>

<p align="center">
<img src = images/workspace4.png width="800">
</p>

# Section 2: Notebooks

### Lab 2.1 - Notebook + Data Source
text

<p align="center">
<img src = images/notebook1.png width="800">
</p>

<p align="center">
<img src = images/notebook2.png width="800">
</p>

<p align="center">
<img src = images/notebook_datasource1.png width="800">
</p>

<p align="center">
<img src = images/notebook_datasource2.png width="800">
</p>

'''python
dataset_path = "copy your dataset in here"

for my_bucket_object in objects:
    object_store.download_file(my_bucket_object.key, dataset_path+"/"+my_bucket_object.key)
'''

<p align="center">
<img src = images/notebook_dataset1.png width="800">
</p>

<p align="center">
<img src = images/notebook_dataset2.png width="800">
</p>

<p align="center">
<img src = images/notebook_docs.png width="800">
</p>

<p align="center">
<img src = images/notebook_embeddings.png width="800">
</p>

Change 'mlops' to 'nissan'

<p align="center">
<img src = images/notebook_qdrant_nissan.png width="800">
</p>

### Lab 2.2 - Configure Model
text

<p align="center">
<img src = images/setup_prompt.png width="800">
</p>

<p align="center">
<img src = images/bitsandbytes.png width="800">
</p>

<p align="center">
<img src = images/download_model.png width="800">
</p>

<p align="center">
<img src = images/pipeline.png width="800">
</p>

### Lab 2.2 - Test Model
text

<p align="center">
<img src = images/question_test.png width="800">
</p>

<p align="center">
<img src = images/question_answer.png width="800">
</p>

# Section 3: Model API Set Up And Deployment
model.py


### Lab 3.1 - Model API Configuration
text

<p align="center">
<img src = images/model_api_collection.png width="800">
</p>

### Lab 3.2 - Model API Deployment
text

# Section 4: Application Setup and Deployment

### Lab 4.1 - Tailor App 
text

<p align="center">
<img src = images/app_header_image.png width="800">
</p>
'''
https://poctemppublic.s3.us-west-2.amazonaws.com/n_car.png
'''

<p align="center">
<img src = images/app_api_endpoint.png width="800">
</p>
'''python
response = requests.post("https://ws.domino-eval.com:443/models/65bcac2e5f71323e384cec13/latest/model",
                auth=(
                    "JbvObvS7MDxXZrBn0tUGd603CTpVTzyH3bmbMV4yEv82EZfiJYOsCVbieciwsE64",
                    "JbvObvS7MDxXZrBn0tUGd603CTpVTzyH3bmbMV4yEv82EZfiJYOsCVbieciwsE64"
                ),
'''

<p align="center">
<img src = images/app_logo.png width="800">
</p>

'''
https://poctemppublic.s3.us-west-2.amazonaws.com/n_logo.png
'''

### Lab 4.2 - Deploy App 
text

# Summary