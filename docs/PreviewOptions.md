# Zuora::PreviewOptions

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**preview_thru_type** | **String** | The options on how the preview through date is calculated. Available for preview only. The &#39;TermEnd&#39; option is invalid when any subscription included in this order is evergreen.    If set the value of this field to &#39;SpecificDate&#39;, you must specify a specific date in the &#39;specificPreviewThruDate&#39; field.  | [optional] 
**preview_types** | **Array&lt;String&gt;** |  | [optional] 
**specific_preview_thru_date** | **Date** | The end date of the order preview. You can preview the invoice charges through the preview through date. (Invoice preview only)   **Note:** This field is only applicable if the &#39;previewThruType&#39; field is set to &#39;SpecificDate&#39;.   | [optional] 


