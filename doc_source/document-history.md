# Document History<a name="document-history"></a>

**Latest documentation update:** September 19, 2018

The following table describes the important changes in each release of the *Amazon Simple Storage Service Console User Guide* from June 19, 2018, onward\. For notification about updates to this documentation, you can subscribe to an RSS feed\.

| Change | Description | Date | 
| --- |--- |--- |
|  Filtering enhancements in cross\-region replication \(CRR\) rules  |  In a CRR rule, you can specify an object filter to choose a subset of objects to apply the rule to\. Previously, you could filter only on an object key prefix\. In this release, you can filter on an object key prefix, one or more object tags, or both\. For more information, see [How Do I Add a Cross\-Region Replication \(CRR\) Rule to an S3 Bucket?](http://docs.aws.amazon.com/AmazonS3/latest/user-guide/enable-crr.html)\.  | September 19, 2018 | 
| Updates now available over RSS | You can now subscribe to an RSS feed to receive notifications about updates to the Amazon Simple Storage Service Console User Guide guide\. | June 19, 2018 | 

## Earlier Updates<a name="earlier-doc-history"></a>

The following table describes the important changes in each release of the *Amazon Simple Storage Service Console User Guide* before June 19, 2018\. 


| Change | Description | Date Changed | 
| --- | --- | --- | 
| New storage class  |  Amazon S3 now offers a new storage class, ONEZONE\_IA \(IA, for infrequent access\) for storing objects\. For more information, see [Storage Classes](http://docs.aws.amazon.com/AmazonS3/latest/dev/storage-class-intro.html) in the *Amazon Simple Storage Service Developer Guide*\.   |  April 4, 2018  | 
| Support for ORC\-formatted Amazon S3 inventory files | Amazon S3 now supports the [Apache optimized row columnar \(ORC\)](https://orc.apache.org/) format in addition to comma\-separated values \(CSV\) file format for inventory output files\. For more information, see [How Do I Configure Amazon S3 Inventory?](configure-inventory.md)\.  |  November 17, 2017 | 
| Bucket permissions check | Bucket permissions check in the Amazon S3 console checks bucket policies and bucket access control lists \(ACLs\) to identify publicly accessible buckets\. Bucket permissions check makes it easier to identify S3 buckets that provide public read and write access\. For more information, see [Identifying Public Buckets Using Bucket Permissions Check](bucket-permissions-check.md)\.  |  November 06, 2017  | 
| Default encryption for S3 buckets |  Amazon S3 default encryption provides a way to set the default encryption behavior for an S3 bucket\. You can set default encryption on a bucket so that all objects are encrypted when they are stored in the bucket\. The objects are encrypted using server\-side encryption with either Amazon S3\-managed keys \(SSE\-S3\) or AWS KMS\-managed keys \(SSE\-KMS\)\. For more information, see [How Do I Enable Default Encryption for an S3 Bucket?](default-bucket-encryption.md)\.  |  November 06, 2017 | 
| Encryption status in Amazon S3 inventory | Amazon S3 now supports including encryption status in Amazon S3 inventory so you can see how your objects are encrypted at rest for compliance auditing or other purposes\. You can also configure to encrypt Amazon S3 inventory with server\-side encryption \(SSE\) or SSE\-KMS so that all inventory files are encrypted accordingly\. For more information, see [How Do I Configure Amazon S3 Inventory?](configure-inventory.md)\.  |  November 06, 2017 | 
| Cross\-region replication enhancements | Cross\-region replication now supports the following: [\[See the AWS documentation website for more details\]](http://docs.aws.amazon.com/AmazonS3/latest/user-guide/document-history.html)  |  November 06, 2017 | 
| Added functionality and documentation |  The Amazon S3 console now supports enabling object\-level logging for an S3 bucket with AWS CloudTrail data events logging\. For more information, see [How Do I Enable Object\-Level Logging for an S3 Bucket with AWS CloudTrail Data Events?](enable-cloudtrail-events.md)\.   |  October 19, 2017 | 
| Old Amazon S3 console no longer available |  The old version of the Amazon S3 console is no longer available and the old user guide was removed from the Amazon S3 documentation site\.   |  August 31, 2017 | 
| General availability of New Amazon S3 console |  Announced the general availability of the new Amazon S3 console\.   |  May 15, 2017  | 