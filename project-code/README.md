# Visualizing Commodity Trade Statistics using Azure, Pyhton


| Authors : **Harika Putti, Pavan Kumar Madineni and Abhishek Rapelli**

## Data: 

* commodity_trade_statistics_data.csv – This data file was downloaded from Kaggle dataset of Global Commodity trade of the United Nations. The dataset has 10 columns and approximately 8.5 million rows. The dataset was stored on the Azure data storage cloud in the form of Azure blob. The dataset was put into a container named mycontainer in the storage account of arapelli.


## Requirements: 

The following are the requirements for this project.
  1.	Microsoft Azure Account
  2.	Python 3
  3.	Azure storage libraries for Python
  4.	Git

## Installation:

Two of the authors have used computers running macOS version 10.14.1 computers. The third one used Windows 10 OS computer.

### Data Setup:

This section focuses on getting the dataset from the source, setting up Azure account and loading the dataset into Azure cloud storage.
1.	Install all the required software and packages, which are listed above on your machine. Example, Python 3, Git, Azure-storage library etc.

2.	Clone our project repository from GitHub using the following command into a directory

```bash
$ git clone https://github.com/cloudmesh-community/fa18-523-81.git
```

3.	Microsoft Azure account is for free on trial for 12 months and Microsoft gives a credit of $200 per month during the period. The next step is to create Azure storage account, which is also free during the trial period for a limit of 5 Giga Bytes.

4. After the storage account is created, under the Resource group field, select Create new and enter the resource group name. The name has to be unique. Then select the location for the storage account, by default US West location is chosen. You can choose either hot or cool tier for your account depending on the usage frequency. For frequent usage, choose Hot, and for rare usage choose Cool option. Then review and then create the account. 

5. Once the resource group has been created, go to the blobs section in the left pane. It will be empty for a newly created resource group. We have to create a new container to store our data in the container. A container is nothing but a folder or a blob that contains files in it. On the top side, we can find create container option. Select it and name the container. Once the container has been created, the next job is to store the data files into the container.

6. Next step is to import our dataset into the blob container. This has to ben done through scripting in any programming languages like Python. It is required to install azure-storage package in Python for the interface to the Azure storage API. First, we create a BlockBlobService instance with the account name and account key of the Azure account. This instance serves as an interface to the Azure account. 

7. Then we can create a blob into the container of this account using the method create_blob_from_path in the instance created earlier. We give local file name, the path to the file name and the container in which we want to store the dataset. On running this script, the dataset is pushed into the Azure blob storage and is reflected in the account after few minutes, depending on the size of the dataset and the speed of server. We may login to the Azure portal and then check the container for the dataset file to confirm. We can also confirm this in Python itself using the method list_blobs with the name of the container as argument. This lists all the files in that particular container.

8. Once the dataset is pushed into the cloud, we can have access to it using the account_name and account_key. We can also download the file using get_blob_to_path method of the interface instance.

9.	The dataset in Azure blob storage can be loaded to Python script as a data frame for any Data science application, provided required packages like Pandas, sklearn, matplotlib etc. installed. To read the blob in Azure as a data frame, first we create an instance of the class BlockBlobService using the account_name and account_key. Then, we call get_blob_to_text method with container and dataset names as arguments. The .content method reads this as a raw text file directly from the cloud storage, which can be loaded into a pandas data frame using read_csv method of pandas library in Python.
  
10. The entire code with all the visualizations are created in jupyter notebook. Please run all the cells sequentially to ensure the code is run without any hassles. Also please check for any packages that are not installed in the local machine on which the code is executed. 

