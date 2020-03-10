# Airflow Installation
## Steps
1. Download the files from the drive and move it to airflow instance. Untar the airflow_download.tar.gz  file.
https://drive.google.com/drive/u/2/folders/1XcJDzRMyGhXrS3v3aQpq_U2cTbbV6_sR
2. Create a new virtual python environment to test.
3. Prerequisites: sudo yum install -y python36u python36u-libs python36u-devel python36u-pip gcc gcc-c++ libffi-devel mariadb-devel cyrus-sasl-devel setuptools
4. source into the virtual environment and run the below command
python3 -m pip install --no-index --find-links=~/john_test_airflow/airflow_downloads/ [location of the installable] -r ~/john_test_airflow/requirements.txt [location of the requirements.txt]
5. issue cmd: airflow version (It should not throw error)
