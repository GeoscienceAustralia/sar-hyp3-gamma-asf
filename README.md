# Hyp3-Gamma ASF
A notebook to request Sentinel-1 scenes to be processed using the asf-hyp3 tool. These scenes can then be uploaded to a specified s3 bucket.

# Requirments
- Mamba (recommmended) or simillar environment management tool such as conda

# Setup
- Add user credentials to the files stored in the credentials folder
    - Earthdata credentials - https://urs.earthdata.nasa.gov/users/new
        - Add these to *credentials_earthdata.yaml*
    - AWS credentials
        - Add these to *credentials_aws.yaml* to enable upload to desired destination

Create the environment and run the notebook
```bash
conda env create --file=environment.yaml
```