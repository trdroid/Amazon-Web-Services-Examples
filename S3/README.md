# Amazon Simple Storage Service (S3)

Amazon S3 is a managed service on AWS that offers an Object Store. 

### Object Store

An *Object Store* stores data as objects. 

**Objects**

Each object in an *Object Store* contains the following

* *Globally Unique Identifier*/*key* 
* Metadata
* Data

**Globally Unique Identifier/key**

The *Globally Unique Identifier/key* allows objects from different devices and machines to be addressed. 

**Metadata**

The metadata includes the following attributes about the data stored

* Creation Date
* File Type
* Size
* Access Control
* Tags

**Data**

Object Stores can be used to store

* Documents (HTML, CSS etc.)
* Binaries/Executables
* Images
* Videos
* JSON 
* BLOB

### Amazon S3 Object Store

Amazon S3 Object Store has all of the aforementioned properties of a general *Object Store*.

**Upper Limit**

The size of an object should not exceed 5 TB.

### Buckets

Amazon S3 groups *objects* into containers called *buckets*. 

**Globally Unique Name**

Each bucket should be assigned a globally unique name, unique across all customers in all regions. 
The convention is to prefix the bucket's name with the user's domain name. 

**Upper Limit**

A maximum of 100 buckets can be created.

### Accessing S3

Amazon S3 is a web service that offers an API to store/upload and retrieve/download data (objects) over HTTPS. 

Amazon S3 can be accessed via

* The Management Console
* The CLI
* The SDKs
* Any third-party tools

### Summary

A summary of features of Amazon S3 are

* S3 stores data in a highly available and a durable way
* S3 offers an unlimited storage space (charges incurred per GB of storage, per request, per data transferred)
* S3 puts a maximum limit of 5 TB on the size of a single object i.e. the size of an object should not exceed 5 TB

