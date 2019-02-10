# Azure Storage Service

This sample demostrates how to upload photo images from the gallery in Android into a Block Blob in Azure Storage. This is a project for Android Studio, which uses Gradle and references the Microsot Azure Storage Library for Android available in the Central Maven Repository. Also, it runs against the actual service, so it is highly recommended that you use a test container, 
as you will be creating and deleting actual blobs.

# Running this demo

1. Open the solution with Android Studio.
2. Open the ImageManager.java file and change the "[ACCOUNT_NAME]" and "[ACCOUNT_KEY]" in the storageConnectionString variable with account and key provided in the Azure Portal. 
