# Mount-Amazon-S3-cloud-storage-as-disk-using-CloudMounter


## Scenario
This document guide you the step to mount Amazon S3 as disk by using CloudMounter and provide the solution for users with low-capacity SSD-drives.

## Prerequisites
> An AWS account.

> CloudMounter License (The license fee depends on the OS that you use), you can also use free trial for testing (15-day for Mac Finder and 14-day for Windows).

## Tutorial
### Install CloudMounter
1.1. Download the product from CloudMounter website: https://cloudmounter.net , for Mac user, CloudMounter can also be found on App Store.

1.2. Follow the installation steps to install.

### Start your Mounting process
2.1.	Open the CloudMounter, and click **Continue**.

![2.1.png](/images/2.1.png)

2.2.	To activate your license, click **Activate**. Or click **Continue Trial**.

![2.2-1.png](/images/2.2-1.png)
![2.2-2.png](/images/2.2-2.png)

2.3.	On the CloudMounter panel, choose **Amazon S3**.

![2.3.png](/images/2.3.png)

2.4.	In Name, give a specific name that you can identify the cloud storage.

![2.4.png](/images/2.4.png)

2.5.	Go to **Amazon Web Services** console and click on the name of your account (it is located in the top right corner of the console). Then, in the expanded drop-down list, select **My Security Credentials**.

![2.5.png](/images/2.5.png)

2.6.	Click **Continue to Security Credentials**.

![2.6.png](/images/2.6.png)

2.7.	Expand the **Access keys (access key ID and secret access key)** option. You will see the list of your active and deleted access keys.

![2.7.png](/images/2.7.png)

2.8.	To generate new access keys, click the **Create New Access Key** button.

2.9.	Click **Show Access Key** to have it displayed on the screen. You can download it to your machine as a file and open it whenever needed. To download it, just click the **Download Key File** button. 

![2.9.png](/images/2.9.png)

***Remember!** If you do not write down the key or download the key file to your computer before you click ”Close”, you will not be able to retrieve the secret key in the future. Then you’ll have to delete the keys which you created and start to create new keys.*

2.10.	Go back to CloudMounter, and insert the **Access Key** and **Secret Key**.

![2.10.png](/images/2.10.png)

2.11.	Let the server endpoint as default, or insert your specific endpoint.

2.12.	Insert the bucket name which you want to connect.

![2.12.png](/images/2.12.png)

2.13.	Click **Mount**.

2.14.	And you will see the cloud storage has successfully mounted as a disk in your finder.

![2.14.png](/images/2.14.png)

2.15.	For encryption, right click your file, and click **Encrypt**.

![2.15.png](/images/2.15.png)

2.16.	Setup a password and verify it, you can also choose to encrypt file names and encrypt only new file for options in this step, and click **Encrypt**.

![2.16.png](/images/2.16.png)

2.17.	Now, you will see the lock on the right side of file. Right click and choose **Lock** to encrypt your file.

![2.17.png](/images/2.17.png)

2.18.	Then, you can see the file encrypted successfully.

![2.18.png](/images/2.18.png)

2.19.	Right click and choose **Unlock** or **Decrypt** and insert the **password** to see your file or to decrypt the file.


## Conclusion

Congratulations! You now have learned how to:
* Find your AWS access key and secret key
* CloudMounter mounting solution

