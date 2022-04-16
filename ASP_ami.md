## Amazon EC2 machine image with NASA ASP 3.0.0 and s3fs-FUSE installed

The AMI ID for this image is **ami-072577843b570e56f** and has the name **FCG NASA ASP 3.0.0**

Amazon's instructions on how to launch an instance using a Community AMI can be [found here](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/finding-an-ami.html).

The links below may help with scaling your ASP run to multiple compute instances using an S3 bucket as the
backing storage shared between them.

 * [How to mount an S3 bucket on an EC2 Linux instance using an IAM role](https://medium.com/tensult/aws-how-to-mount-s3-bucket-using-iam-role-on-ec2-linux-instance-ad2afd4513ef) -
s3fs is already installed on instances created with the shared AMI, so you can skip to Step 6 if you're using the AMI above.

 * [parallel_stereo](https://stereopipeline.readthedocs.io/en/stable/tools/parallel_stereo.html) - documentation for the ASP parallel_stereo command
