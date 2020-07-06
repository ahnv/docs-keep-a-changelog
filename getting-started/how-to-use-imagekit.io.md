# How to use ImageKit.io?

There are two ways to use ImageKit.io. Depending upon your needs, either you can plug ImageKit.io with your existing infrastructure without moving or re-uploading any existing images, or you can upload pictures in ImageKit.io media library.

## 1. Integration with existing storage or server

ImageKit.io can be integrated into your existing infrastructure within minutes. 

{% hint style="success" %}
\*\*\*\*🧙♂ **Recommended if you don't want to move your existing images**  
If you have a running website or application, you don't need to move your images anywhere. Just configure your existing image origin and ImageKit.io will fetch the images on the first request and cache the response.
{% endhint %}

ImageKit.io supports the following types of origin:

1. [Amazon S3 bucket origin](../integration/configure-origin/amazon-s3-bucket-origin.md)
2. Any [web server origin](../integration/configure-origin/web-server-origin.md), for example - Magento, WordPress, etc.
3. [Azure Blob storage](../integration/configure-origin/azure-blob-storage.md)
4. [Google Storage](../integration/configure-origin/google-cloud-storage.md)
5. [Firebase Storage](../integration/configure-origin/firebase-storage.md)
6. [Cloudinary backup bucket](../integration/configure-origin/cloudinary-backup-bucket.md)

## 2. Using ImageKit storage \(Media Library\)

If you don't want to handle image upload to your own storage, then ImageKit's media library is excellent for you. The media library is an available unlimited internal storage provided by ImageKit.io to all its users. ImageKit.io media library is built on top of the Amazon S3, and it is co-located with core image processing servers in all the regions.

{% hint style="success" %}
**Automatic storage replication** 😎   
****All files uploaded in the media library are automatically replicated in two geographic regions to handle failovers.
{% endhint %}

Media library allows you to:

1. Upload images via ImageKit.io dashboard, upload API or SDKs.
2. Create folders to manage your images.
3. Tag files for better organization.
4. Search files by name, folder name, and tags.
5. Delete a file.
