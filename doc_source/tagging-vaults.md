# Tagging Your Amazon Glacier Vaults<a name="tagging-vaults"></a>

You can assign your own metadata to Amazon Glacier vaults in the form of tags\. A *tag* is a key\-value pair that you define for a vault\. For basic information about tagging, including restrictions on tags, see [Tagging Amazon Glacier Resources](tagging.md)\.

The following topics describe how you can add, list, and remove tags for vaults\.

**Topics**
+ [Tagging Vaults Using the Amazon Glacier Console](#tagging-console)
+ [Tagging Vaults Using the Amazon Glacier API](#tagging-api)
+ [Related Sections](#related-sections-tagging-vaults)

## Tagging Vaults Using the Amazon Glacier Console<a name="tagging-console"></a>

You can add, list, and remove tags using the Amazon Glacier console as described in the following procedures\.

**To view the tags for a vault**

1. Sign in to the AWS Management Console and open the Amazon Glacier console at [https://console\.aws\.amazon\.com/glacier](https://console.aws.amazon.com/glacier)\.

1. From the region selector, choose a region\.

1. On the **Amazon Glacier Vaults** page, choose a vault\.

1. Choose the **Tags** tab\. The tags for that vault will appear\.

**To add a tag to a vault**

1. Open the Amazon Glacier console, and then choose a region from the region selector\.

1. On the **Amazon Glacier Vaults** page, choose a vault\.

1. Choose the **Tags** tab\.

1. Specify the tag key in the **Key** field, optionally specify a tag value in the **Value** field, and then choose **Save**\.

   If the **Save** button is not enabled, either the tag key or the tag value that you specified does not meet the tag restrictions\. For more about tag restrictions, see [Tag Restrictions](tagging.md#tagging-restrictions)\.

**To remove a tag from a vault**

1. Open the Amazon Glacier console, and then choose a region from the region selector\.

1. On the **Amazon Glacier Vaults** page, choose a vault\.

1. Choose the **Tags** tab, and then choose the **x** at the end of the row that describes the tag you want to delete\.

1. Choose **Delete**\.

## Tagging Vaults Using the Amazon Glacier API<a name="tagging-api"></a>

You can add, list, and remove tags using the Amazon Glacier API\. For examples, see the following documentation:

 [Add Tags To Vault \(POST tags add\)](api-AddTagsToVault.md)   
Adds or updates tags for the specified vault\.

 [List Tags For Vault \(GET tags\)](api-ListTagsForVault.md)   
Lists the tags for the specified vault\.

 [Remove Tags From Vault \(POST tags remove\)](api-RemoveTagsFromVault.md)   
Removes tags from the specified vault\.

## Related Sections<a name="related-sections-tagging-vaults"></a>
+ [Tagging Amazon Glacier Resources](tagging.md)