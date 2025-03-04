---
title: "msdyn_AIModel table/entity reference (Microsoft Dataverse) | Microsoft Docs"
description: "Includes schema information and supported messages for the msdyn_AIModel table/entity."
ms.date: 05/23/2023
ms.service: "powerapps"
ms.topic: "reference"
ms.assetid: 3948cc48-07c8-7f60-0608-71c37158ad7c
author: "phecke"
ms.author: "pehecke"
search.audienceType: 
  - developer
---

# msdyn_AIModel table/entity reference

> [!NOTE]
> Unsure about table vs. entity? See [Developers: Understand terminology in Microsoft Dataverse](/powerapps/developer/data-platform/understand-terminology).



**Added by**: AISolution Solution


## Messages

|Message|Web API Operation|SDK class or method|
|-|-|-|
|AddToFeedbackLoop|<xref:Microsoft.Dynamics.CRM.AddToFeedbackLoop?displayProperty=nameWithType />|<xref:Microsoft.Xrm.Sdk.OrganizationRequest><br/> where <xref:Microsoft.Xrm.Sdk.OrganizationRequest.RequestName>="AddToFeedbackLoop"|
|Assign|PATCH [*org URI*]/api/data/v9.2/msdyn_aimodels(*msdyn_aimodelid*)<br />[Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) `ownerid` property.|<xref:Microsoft.Crm.Sdk.Messages.AssignRequest>|
|BatchPrediction|<xref:Microsoft.Dynamics.CRM.BatchPrediction?displayProperty=nameWithType />|<xref:Microsoft.Xrm.Sdk.OrganizationRequest><br/> where <xref:Microsoft.Xrm.Sdk.OrganizationRequest.RequestName>="BatchPrediction"|
|Create|POST [*org URI*]/api/data/v9.2/msdyn_aimodels<br />See [Create](/powerapps/developer/data-platform/webapi/create-entity-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.CreateRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Create*>|
|CreateMultiple||<xref:Microsoft.Xrm.Sdk.Messages.CreateMultipleRequest>|
|Delete|DELETE [*org URI*]/api/data/v9.2/msdyn_aimodels(*msdyn_aimodelid*)<br />See [Delete](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-delete)|<xref:Microsoft.Xrm.Sdk.Messages.DeleteRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Delete*>|
|GrantAccess|<xref:Microsoft.Dynamics.CRM.GrantAccess?displayProperty=nameWithType />|<xref:Microsoft.Crm.Sdk.Messages.GrantAccessRequest>|
|IsValidStateTransition|<xref:Microsoft.Dynamics.CRM.IsValidStateTransition?displayProperty=nameWithType />|<xref:Microsoft.Crm.Sdk.Messages.IsValidStateTransitionRequest>|
|ModifyAccess|<xref:Microsoft.Dynamics.CRM.ModifyAccess?displayProperty=nameWithType />|<xref:Microsoft.Crm.Sdk.Messages.ModifyAccessRequest>|
|Predict|<xref:Microsoft.Dynamics.CRM.Predict?displayProperty=nameWithType />|<xref:Microsoft.Xrm.Sdk.OrganizationRequest><br/> where <xref:Microsoft.Xrm.Sdk.OrganizationRequest.RequestName>="Predict"|
|PredictByReference|<xref:Microsoft.Dynamics.CRM.PredictByReference?displayProperty=nameWithType />|<xref:Microsoft.Xrm.Sdk.OrganizationRequest><br/> where <xref:Microsoft.Xrm.Sdk.OrganizationRequest.RequestName>="PredictByReference"|
|PredictionSchema|<xref:Microsoft.Dynamics.CRM.PredictionSchema?displayProperty=nameWithType />|<xref:Microsoft.Xrm.Sdk.OrganizationRequest><br/> where <xref:Microsoft.Xrm.Sdk.OrganizationRequest.RequestName>="PredictionSchema"|
|Retrieve|GET [*org URI*]/api/data/v9.2/msdyn_aimodels(*msdyn_aimodelid*)<br />See [Retrieve](/powerapps/developer/data-platform/webapi/retrieve-entity-using-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.RetrieveRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Retrieve*>|
|RetrieveMultiple|GET [*org URI*]/api/data/v9.2/msdyn_aimodels<br />See [Query Data](/powerapps/developer/data-platform/webapi/query-data-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.RetrieveMultipleRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.RetrieveMultiple*>|
|RetrievePrincipalAccess|<xref:Microsoft.Dynamics.CRM.RetrievePrincipalAccess?displayProperty=nameWithType />|<xref:Microsoft.Crm.Sdk.Messages.RetrievePrincipalAccessRequest>|
|RetrieveSharedPrincipalsAndAccess|<xref:Microsoft.Dynamics.CRM.RetrieveSharedPrincipalsAndAccess?displayProperty=nameWithType />|<xref:Microsoft.Crm.Sdk.Messages.RetrieveSharedPrincipalsAndAccessRequest>|
|RevokeAccess|<xref:Microsoft.Dynamics.CRM.RevokeAccess?displayProperty=nameWithType />|<xref:Microsoft.Crm.Sdk.Messages.RevokeAccessRequest>|
|SchedulePrediction|<xref:Microsoft.Dynamics.CRM.SchedulePrediction?displayProperty=nameWithType />|<xref:Microsoft.Xrm.Sdk.OrganizationRequest><br/> where <xref:Microsoft.Xrm.Sdk.OrganizationRequest.RequestName>="SchedulePrediction"|
|ScheduleRetrain|<xref:Microsoft.Dynamics.CRM.ScheduleRetrain?displayProperty=nameWithType />|<xref:Microsoft.Xrm.Sdk.OrganizationRequest><br/> where <xref:Microsoft.Xrm.Sdk.OrganizationRequest.RequestName>="ScheduleRetrain"|
|SetState|PATCH [*org URI*]/api/data/v9.2/msdyn_aimodels(*msdyn_aimodelid*)<br />[Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) `statecode` and `statuscode` properties.|<xref:Microsoft.Crm.Sdk.Messages.SetStateRequest>|
|UnschedulePrediction|<xref:Microsoft.Dynamics.CRM.UnschedulePrediction?displayProperty=nameWithType />|<xref:Microsoft.Xrm.Sdk.OrganizationRequest><br/> where <xref:Microsoft.Xrm.Sdk.OrganizationRequest.RequestName>="UnschedulePrediction"|
|Update|PATCH [*org URI*]/api/data/v9.2/msdyn_aimodels(*msdyn_aimodelid*)<br />See [Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update)|<xref:Microsoft.Xrm.Sdk.Messages.UpdateRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Update*>|
|UpdateMultiple||<xref:Microsoft.Xrm.Sdk.Messages.UpdateMultipleRequest>|

## Properties

|Property|Value|
|--------|-----|
|CollectionSchemaName|msdyn_AIModels|
|DisplayCollectionName|AI Models|
|DisplayName|AI Model|
|EntitySetName|msdyn_aimodels|
|IsBPFEntity|False|
|LogicalCollectionName|msdyn_aimodels|
|LogicalName|msdyn_aimodel|
|OwnershipType|UserOwned|
|PrimaryIdAttribute|msdyn_aimodelid|
|PrimaryNameAttribute|msdyn_name|
|SchemaName|msdyn_AIModel|

<a name="writable-attributes"></a>

## Writable columns/attributes

These columns/attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [ImportSequenceNumber](#BKMK_ImportSequenceNumber)
- [IntroducedVersion](#BKMK_IntroducedVersion)
- [IsCustomizable](#BKMK_IsCustomizable)
- [msdyn_ActiveRunConfigurationId](#BKMK_msdyn_ActiveRunConfigurationId)
- [msdyn_AIModelId](#BKMK_msdyn_AIModelId)
- [msdyn_ModelCreationContext](#BKMK_msdyn_ModelCreationContext)
- [msdyn_Name](#BKMK_msdyn_Name)
- [msdyn_RetrainWorkflowId](#BKMK_msdyn_RetrainWorkflowId)
- [msdyn_ScheduleInferenceWorkflowId](#BKMK_msdyn_ScheduleInferenceWorkflowId)
- [msdyn_ShareWithOrganizationOnCreate](#BKMK_msdyn_ShareWithOrganizationOnCreate)
- [msdyn_TemplateId](#BKMK_msdyn_TemplateId)
- [OverriddenCreatedOn](#BKMK_OverriddenCreatedOn)
- [OwnerId](#BKMK_OwnerId)
- [OwnerIdType](#BKMK_OwnerIdType)
- [statecode](#BKMK_statecode)
- [statuscode](#BKMK_statuscode)
- [TimeZoneRuleVersionNumber](#BKMK_TimeZoneRuleVersionNumber)
- [UTCConversionTimeZoneCode](#BKMK_UTCConversionTimeZoneCode)


### <a name="BKMK_ImportSequenceNumber"></a> ImportSequenceNumber

**Added by**: Basic Solution Solution

|Property|Value|
|--------|-----|
|Description|Sequence number of the import that created this record.|
|DisplayName|Import Sequence Number|
|Format|None|
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|importsequencenumber|
|MaxValue|2147483647|
|MinValue|-2147483648|
|RequiredLevel|None|
|Type|Integer|


### <a name="BKMK_IntroducedVersion"></a> IntroducedVersion

|Property|Value|
|--------|-----|
|Description|Version in which the form is introduced.|
|DisplayName|Introduced Version|
|FormatName|VersionNumber|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|introducedversion|
|MaxLength|48|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_IsCustomizable"></a> IsCustomizable

|Property|Value|
|--------|-----|
|Description|Tells whether the component can be customized.|
|DisplayName|Customizable|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|iscustomizable|
|RequiredLevel|SystemRequired|
|Type|ManagedProperty|


### <a name="BKMK_msdyn_ActiveRunConfigurationId"></a> msdyn_ActiveRunConfigurationId

|Property|Value|
|--------|-----|
|Description|Unique identifier for the active run configuration id associated with AIModel.|
|DisplayName|ActiveRunConfigurationId|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_activerunconfigurationid|
|RequiredLevel|None|
|Targets||
|Type|Lookup|


### <a name="BKMK_msdyn_AIModelId"></a> msdyn_AIModelId

|Property|Value|
|--------|-----|
|Description|Unique identifier for entity instances|
|DisplayName|AIModel|
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|msdyn_aimodelid|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|


### <a name="BKMK_msdyn_ModelCreationContext"></a> msdyn_ModelCreationContext

|Property|Value|
|--------|-----|
|Description||
|DisplayName|ModelCreationContext|
|Format|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_modelcreationcontext|
|MaxLength|1048576|
|RequiredLevel|None|
|Type|Memo|


### <a name="BKMK_msdyn_Name"></a> msdyn_Name

|Property|Value|
|--------|-----|
|Description|The name of the custom entity.|
|DisplayName|Name|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_name|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_msdyn_RetrainWorkflowId"></a> msdyn_RetrainWorkflowId

|Property|Value|
|--------|-----|
|Description|Unique identifier for Retrain Process associated with AI Model.|
|DisplayName|RetrainWorkflowId|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_retrainworkflowid|
|RequiredLevel|None|
|Targets|workflow|
|Type|Lookup|


### <a name="BKMK_msdyn_ScheduleInferenceWorkflowId"></a> msdyn_ScheduleInferenceWorkflowId

|Property|Value|
|--------|-----|
|Description|Unique identifier for Schedule Inference Process associated with AI Model.|
|DisplayName|ScheduleInferenceWorkflowId|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_scheduleinferenceworkflowid|
|RequiredLevel|None|
|Targets|workflow|
|Type|Lookup|


### <a name="BKMK_msdyn_ShareWithOrganizationOnCreate"></a> msdyn_ShareWithOrganizationOnCreate

|Property|Value|
|--------|-----|
|Description||
|DisplayName|ShareWithOrganizationOnCreate|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_sharewithorganizationoncreate|
|RequiredLevel|None|
|Type|Boolean|

#### msdyn_ShareWithOrganizationOnCreate Choices/Options

|Value|Label|Description|
|-----|-----|--------|
|1|Yes||
|0|No||

**DefaultValue**: 0



### <a name="BKMK_msdyn_TemplateId"></a> msdyn_TemplateId

|Property|Value|
|--------|-----|
|Description|Unique identifier for AITemplate associated with AIModel.|
|DisplayName|Template|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|msdyn_templateid|
|RequiredLevel|SystemRequired|
|Targets|msdyn_aitemplate|
|Type|Lookup|


### <a name="BKMK_OverriddenCreatedOn"></a> OverriddenCreatedOn

|Property|Value|
|--------|-----|
|DateTimeBehavior|UserLocal|
|Description|Date and time that the record was migrated.|
|DisplayName|Record Created On|
|Format|DateOnly|
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|overriddencreatedon|
|RequiredLevel|None|
|Type|DateTime|


### <a name="BKMK_OwnerId"></a> OwnerId

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Owner Id|
|DisplayName|Owner|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|ownerid|
|RequiredLevel|SystemRequired|
|Targets|systemuser,team|
|Type|Owner|


### <a name="BKMK_OwnerIdType"></a> OwnerIdType

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Owner Id Type|
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owneridtype|
|RequiredLevel|SystemRequired|
|Type|EntityName|


### <a name="BKMK_statecode"></a> statecode

|Property|Value|
|--------|-----|
|Description|Status of the AIModel|
|DisplayName|Status|
|IsValidForCreate|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|statecode|
|RequiredLevel|SystemRequired|
|Type|State|

#### statecode Choices/Options

|Value|Label|DefaultStatus|InvariantName|
|-----|-----|-------------|-------------|
|0|Inactive|0|Inactive|
|1|Active|1|Active|



### <a name="BKMK_statuscode"></a> statuscode

|Property|Value|
|--------|-----|
|Description|Reason for the status of the AIModel|
|DisplayName|Status Reason|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|statuscode|
|RequiredLevel|None|
|Type|Status|

#### statuscode Choices/Options

|Value|Label|State|
|-----|-----|-----|
|0|Inactive|0|
|1|Active|1|



### <a name="BKMK_TimeZoneRuleVersionNumber"></a> TimeZoneRuleVersionNumber

|Property|Value|
|--------|-----|
|Description|For internal use only.|
|DisplayName|Time Zone Rule Version Number|
|Format|None|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|timezoneruleversionnumber|
|MaxValue|2147483647|
|MinValue|-1|
|RequiredLevel|None|
|Type|Integer|


### <a name="BKMK_UTCConversionTimeZoneCode"></a> UTCConversionTimeZoneCode

|Property|Value|
|--------|-----|
|Description|Time zone code that was in use when the record was created.|
|DisplayName|UTC Conversion Time Zone Code|
|Format|None|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|utcconversiontimezonecode|
|MaxValue|2147483647|
|MinValue|-1|
|RequiredLevel|None|
|Type|Integer|

<a name="read-only-attributes"></a>

## Read-only columns/attributes

These columns/attributes return false for both **IsValidForCreate** or **IsValidForUpdate**. Listed by **SchemaName**.

- [ComponentState](#BKMK_ComponentState)
- [CreatedBy](#BKMK_CreatedBy)
- [CreatedByName](#BKMK_CreatedByName)
- [CreatedByYomiName](#BKMK_CreatedByYomiName)
- [CreatedOn](#BKMK_CreatedOn)
- [CreatedOnBehalfBy](#BKMK_CreatedOnBehalfBy)
- [CreatedOnBehalfByName](#BKMK_CreatedOnBehalfByName)
- [CreatedOnBehalfByYomiName](#BKMK_CreatedOnBehalfByYomiName)
- [IsManaged](#BKMK_IsManaged)
- [ModifiedBy](#BKMK_ModifiedBy)
- [ModifiedByName](#BKMK_ModifiedByName)
- [ModifiedByYomiName](#BKMK_ModifiedByYomiName)
- [ModifiedOn](#BKMK_ModifiedOn)
- [ModifiedOnBehalfBy](#BKMK_ModifiedOnBehalfBy)
- [ModifiedOnBehalfByName](#BKMK_ModifiedOnBehalfByName)
- [ModifiedOnBehalfByYomiName](#BKMK_ModifiedOnBehalfByYomiName)
- [msdyn_AIModelIdUnique](#BKMK_msdyn_AIModelIdUnique)
- [msdyn_retrainworkflowidName](#BKMK_msdyn_retrainworkflowidName)
- [msdyn_scheduleinferenceworkflowidName](#BKMK_msdyn_scheduleinferenceworkflowidName)
- [msdyn_TemplateIdName](#BKMK_msdyn_TemplateIdName)
- [OverwriteTime](#BKMK_OverwriteTime)
- [OwnerIdName](#BKMK_OwnerIdName)
- [OwnerIdYomiName](#BKMK_OwnerIdYomiName)
- [OwningBusinessUnit](#BKMK_OwningBusinessUnit)
- [OwningBusinessUnitName](#BKMK_OwningBusinessUnitName)
- [OwningTeam](#BKMK_OwningTeam)
- [OwningUser](#BKMK_OwningUser)
- [SolutionId](#BKMK_SolutionId)
- [SupportingSolutionId](#BKMK_SupportingSolutionId)
- [VersionNumber](#BKMK_VersionNumber)


### <a name="BKMK_ComponentState"></a> ComponentState

|Property|Value|
|--------|-----|
|Description|For internal use only.|
|DisplayName|Component State|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|componentstate|
|RequiredLevel|SystemRequired|
|Type|Picklist|

#### ComponentState Choices/Options

|Value|Label|Description|
|-----|-----|--------|
|0|Published||
|1|Unpublished||
|2|Deleted||
|3|Deleted Unpublished||



### <a name="BKMK_CreatedBy"></a> CreatedBy

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Unique identifier of the user who created the record.|
|DisplayName|Created By|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|createdby|
|RequiredLevel|None|
|Targets|systemuser|
|Type|Lookup|


### <a name="BKMK_CreatedByName"></a> CreatedByName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|createdbyname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_CreatedByYomiName"></a> CreatedByYomiName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|createdbyyominame|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_CreatedOn"></a> CreatedOn

|Property|Value|
|--------|-----|
|DateTimeBehavior|UserLocal|
|Description|Date and time when the record was created.|
|DisplayName|Created On|
|Format|DateAndTime|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|createdon|
|RequiredLevel|None|
|Type|DateTime|


### <a name="BKMK_CreatedOnBehalfBy"></a> CreatedOnBehalfBy

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Unique identifier of the delegate user who created the record.|
|DisplayName|Created By (Delegate)|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|createdonbehalfby|
|RequiredLevel|None|
|Targets|systemuser|
|Type|Lookup|


### <a name="BKMK_CreatedOnBehalfByName"></a> CreatedOnBehalfByName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|createdonbehalfbyname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_CreatedOnBehalfByYomiName"></a> CreatedOnBehalfByYomiName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|createdonbehalfbyyominame|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_IsManaged"></a> IsManaged

|Property|Value|
|--------|-----|
|Description|Indicates whether the solution component is part of a managed solution.|
|DisplayName|Is Managed|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|ismanaged|
|RequiredLevel|SystemRequired|
|Type|Boolean|

#### IsManaged Choices/Options

|Value|Label|Description|
|-----|-----|--------|
|1|Managed||
|0|Unmanaged||

**DefaultValue**: 0



### <a name="BKMK_ModifiedBy"></a> ModifiedBy

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Unique identifier of the user who modified the record.|
|DisplayName|Modified By|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|modifiedby|
|RequiredLevel|None|
|Targets|systemuser|
|Type|Lookup|


### <a name="BKMK_ModifiedByName"></a> ModifiedByName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|modifiedbyname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_ModifiedByYomiName"></a> ModifiedByYomiName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|modifiedbyyominame|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_ModifiedOn"></a> ModifiedOn

|Property|Value|
|--------|-----|
|DateTimeBehavior|UserLocal|
|Description|Date and time when the record was modified.|
|DisplayName|Modified On|
|Format|DateAndTime|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|modifiedon|
|RequiredLevel|None|
|Type|DateTime|


### <a name="BKMK_ModifiedOnBehalfBy"></a> ModifiedOnBehalfBy

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Unique identifier of the delegate user who modified the record.|
|DisplayName|Modified By (Delegate)|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|modifiedonbehalfby|
|RequiredLevel|None|
|Targets|systemuser|
|Type|Lookup|


### <a name="BKMK_ModifiedOnBehalfByName"></a> ModifiedOnBehalfByName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|modifiedonbehalfbyname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_ModifiedOnBehalfByYomiName"></a> ModifiedOnBehalfByYomiName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|modifiedonbehalfbyyominame|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_msdyn_AIModelIdUnique"></a> msdyn_AIModelIdUnique

|Property|Value|
|--------|-----|
|Description|For internal use only.|
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|msdyn_aimodelidunique|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|


### <a name="BKMK_msdyn_retrainworkflowidName"></a> msdyn_retrainworkflowidName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|msdyn_retrainworkflowidname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_msdyn_scheduleinferenceworkflowidName"></a> msdyn_scheduleinferenceworkflowidName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|msdyn_scheduleinferenceworkflowidname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_msdyn_TemplateIdName"></a> msdyn_TemplateIdName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|msdyn_templateidname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_OverwriteTime"></a> OverwriteTime

|Property|Value|
|--------|-----|
|DateTimeBehavior|UserLocal|
|Description|For internal use only.|
|DisplayName|Record Overwrite Time|
|Format|DateOnly|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|overwritetime|
|RequiredLevel|SystemRequired|
|Type|DateTime|


### <a name="BKMK_OwnerIdName"></a> OwnerIdName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Name of the owner|
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owneridname|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_OwnerIdYomiName"></a> OwnerIdYomiName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Yomi name of the owner|
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owneridyominame|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_OwningBusinessUnit"></a> OwningBusinessUnit

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Unique identifier for the business unit that owns the record|
|DisplayName|Owning Business Unit|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|owningbusinessunit|
|RequiredLevel|None|
|Targets|businessunit|
|Type|Lookup|


### <a name="BKMK_OwningBusinessUnitName"></a> OwningBusinessUnitName

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owningbusinessunitname|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_OwningTeam"></a> OwningTeam

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Unique identifier for the team that owns the record.|
|DisplayName|Owning Team|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owningteam|
|RequiredLevel|None|
|Targets|team|
|Type|Lookup|


### <a name="BKMK_OwningUser"></a> OwningUser

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Unique identifier for the user that owns the record.|
|DisplayName|Owning User|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owninguser|
|RequiredLevel|None|
|Targets|systemuser|
|Type|Lookup|


### <a name="BKMK_SolutionId"></a> SolutionId

|Property|Value|
|--------|-----|
|Description|Unique identifier of the associated solution.|
|DisplayName|Solution|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|solutionid|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|


### <a name="BKMK_SupportingSolutionId"></a> SupportingSolutionId

|Property|Value|
|--------|-----|
|Description|For internal use only.|
|DisplayName|Solution|
|IsValidForForm|False|
|IsValidForRead|False|
|LogicalName|supportingsolutionid|
|RequiredLevel|None|
|Type|Uniqueidentifier|


### <a name="BKMK_VersionNumber"></a> VersionNumber

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Version Number|
|DisplayName|Version Number|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|versionnumber|
|MaxValue|9223372036854775807|
|MinValue|-9223372036854775808|
|RequiredLevel|None|
|Type|BigInt|

<a name="onetomany"></a>

## One-To-Many Relationships

Listed by **SchemaName**.

- [msdyn_aimodel_SyncErrors](#BKMK_msdyn_aimodel_SyncErrors)
- [msdyn_aimodel_AsyncOperations](#BKMK_msdyn_aimodel_AsyncOperations)
- [msdyn_aimodel_MailboxTrackingFolders](#BKMK_msdyn_aimodel_MailboxTrackingFolders)
- [msdyn_aimodel_ProcessSession](#BKMK_msdyn_aimodel_ProcessSession)
- [msdyn_aimodel_BulkDeleteFailures](#BKMK_msdyn_aimodel_BulkDeleteFailures)
- [msdyn_aimodel_PrincipalObjectAttributeAccesses](#BKMK_msdyn_aimodel_PrincipalObjectAttributeAccesses)
- [msdyn_aimodel_msdyn_aiconfiguration](#BKMK_msdyn_aimodel_msdyn_aiconfiguration)
- [msdyn_aimodel_Annotations](#BKMK_msdyn_aimodel_Annotations)
- [msdyn_AIBDatasetsContainer_msdyn_AIModelI](#BKMK_msdyn_AIBDatasetsContainer_msdyn_AIModelI)
- [msdyn_aimodel_msdyn_aievent](#BKMK_msdyn_aimodel_msdyn_aievent)
- [msdyn_AIBFeedbackLoop_msdyn_AIModel](#BKMK_msdyn_AIBFeedbackLoop_msdyn_AIModel)


### <a name="BKMK_msdyn_aimodel_SyncErrors"></a> msdyn_aimodel_SyncErrors

**Added by**: System Solution Solution

Same as the [msdyn_aimodel_SyncErrors](syncerror.md#BKMK_msdyn_aimodel_SyncErrors) many-to-one relationship for the [syncerror](syncerror.md) table/entity.

|Property|Value|
|--------|-----|
|ReferencingEntity|syncerror|
|ReferencingAttribute|regardingobjectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_aimodel_SyncErrors|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_msdyn_aimodel_AsyncOperations"></a> msdyn_aimodel_AsyncOperations

**Added by**: System Solution Solution

Same as the [msdyn_aimodel_AsyncOperations](asyncoperation.md#BKMK_msdyn_aimodel_AsyncOperations) many-to-one relationship for the [asyncoperation](asyncoperation.md) table/entity.

|Property|Value|
|--------|-----|
|ReferencingEntity|asyncoperation|
|ReferencingAttribute|regardingobjectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_aimodel_AsyncOperations|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: NoCascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_msdyn_aimodel_MailboxTrackingFolders"></a> msdyn_aimodel_MailboxTrackingFolders

**Added by**: System Solution Solution

Same as the [msdyn_aimodel_MailboxTrackingFolders](mailboxtrackingfolder.md#BKMK_msdyn_aimodel_MailboxTrackingFolders) many-to-one relationship for the [mailboxtrackingfolder](mailboxtrackingfolder.md) table/entity.

|Property|Value|
|--------|-----|
|ReferencingEntity|mailboxtrackingfolder|
|ReferencingAttribute|regardingobjectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_aimodel_MailboxTrackingFolders|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_msdyn_aimodel_ProcessSession"></a> msdyn_aimodel_ProcessSession

**Added by**: System Solution Solution

Same as the [msdyn_aimodel_ProcessSession](processsession.md#BKMK_msdyn_aimodel_ProcessSession) many-to-one relationship for the [processsession](processsession.md) table/entity.

|Property|Value|
|--------|-----|
|ReferencingEntity|processsession|
|ReferencingAttribute|regardingobjectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_aimodel_ProcessSession|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: NoCascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_msdyn_aimodel_BulkDeleteFailures"></a> msdyn_aimodel_BulkDeleteFailures

**Added by**: System Solution Solution

Same as the [msdyn_aimodel_BulkDeleteFailures](bulkdeletefailure.md#BKMK_msdyn_aimodel_BulkDeleteFailures) many-to-one relationship for the [bulkdeletefailure](bulkdeletefailure.md) table/entity.

|Property|Value|
|--------|-----|
|ReferencingEntity|bulkdeletefailure|
|ReferencingAttribute|regardingobjectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_aimodel_BulkDeleteFailures|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_msdyn_aimodel_PrincipalObjectAttributeAccesses"></a> msdyn_aimodel_PrincipalObjectAttributeAccesses

**Added by**: System Solution Solution

Same as the [msdyn_aimodel_PrincipalObjectAttributeAccesses](principalobjectattributeaccess.md#BKMK_msdyn_aimodel_PrincipalObjectAttributeAccesses) many-to-one relationship for the [principalobjectattributeaccess](principalobjectattributeaccess.md) table/entity.

|Property|Value|
|--------|-----|
|ReferencingEntity|principalobjectattributeaccess|
|ReferencingAttribute|objectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_aimodel_PrincipalObjectAttributeAccesses|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_msdyn_aimodel_msdyn_aiconfiguration"></a> msdyn_aimodel_msdyn_aiconfiguration

Same as the [msdyn_aimodel_msdyn_aiconfiguration](msdyn_aiconfiguration.md#BKMK_msdyn_aimodel_msdyn_aiconfiguration) many-to-one relationship for the [msdyn_aiconfiguration](msdyn_aiconfiguration.md) table/entity.

|Property|Value|
|--------|-----|
|ReferencingEntity|msdyn_aiconfiguration|
|ReferencingAttribute|msdyn_aimodelid|
|IsHierarchical|False|
|IsCustomizable|False|
|ReferencedEntityNavigationPropertyName|msdyn_aimodel_msdyn_aiconfiguration|
|AssociatedMenuConfiguration|Behavior: UseCollectionName<br />Group: Details<br />Label: <br />Order: 10000|
|CascadeConfiguration|Assign: Cascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: Cascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_msdyn_aimodel_Annotations"></a> msdyn_aimodel_Annotations

**Added by**: System Solution Solution

Same as the [msdyn_aimodel_Annotations](annotation.md#BKMK_msdyn_aimodel_Annotations) many-to-one relationship for the [annotation](annotation.md) table/entity.

|Property|Value|
|--------|-----|
|ReferencingEntity|annotation|
|ReferencingAttribute|objectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|msdyn_aimodel_Annotations|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: Cascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: Cascade<br />Share: Cascade<br />Unshare: Cascade|


### <a name="BKMK_msdyn_AIBDatasetsContainer_msdyn_AIModelI"></a> msdyn_AIBDatasetsContainer_msdyn_AIModelI

**Added by**: AI Solution default templates Solution

Same as the [msdyn_AIBDatasetsContainer_msdyn_AIModelI](msdyn_aibdatasetscontainer.md#BKMK_msdyn_AIBDatasetsContainer_msdyn_AIModelI) many-to-one relationship for the [msdyn_aibdatasetscontainer](msdyn_aibdatasetscontainer.md) table/entity.

|Property|Value|
|--------|-----|
|ReferencingEntity|msdyn_aibdatasetscontainer|
|ReferencingAttribute|msdyn_aimodelid|
|IsHierarchical|False|
|IsCustomizable|False|
|ReferencedEntityNavigationPropertyName|msdyn_AIBDatasetsContainer_msdyn_AIModelI|
|AssociatedMenuConfiguration|Behavior: UseCollectionName<br />Group: Details<br />Label: <br />Order: 10000|
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_msdyn_aimodel_msdyn_aievent"></a> msdyn_aimodel_msdyn_aievent

Same as the [msdyn_aimodel_msdyn_aievent](msdyn_aievent.md#BKMK_msdyn_aimodel_msdyn_aievent) many-to-one relationship for the [msdyn_aievent](msdyn_aievent.md) table/entity.

|Property|Value|
|--------|-----|
|ReferencingEntity|msdyn_aievent|
|ReferencingAttribute|msdyn_aimodelid|
|IsHierarchical|False|
|IsCustomizable|False|
|ReferencedEntityNavigationPropertyName|msdyn_aimodel_msdyn_aievent|
|AssociatedMenuConfiguration|Behavior: UseCollectionName<br />Group: Details<br />Label: <br />Order: 10000|
|CascadeConfiguration|Assign: NoCascade<br />Delete: RemoveLink<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_msdyn_AIBFeedbackLoop_msdyn_AIModel"></a> msdyn_AIBFeedbackLoop_msdyn_AIModel

**Added by**: AISolutionFullAdditions Solution

Same as the [msdyn_AIBFeedbackLoop_msdyn_AIModel](msdyn_aibfeedbackloop.md#BKMK_msdyn_AIBFeedbackLoop_msdyn_AIModel) many-to-one relationship for the [msdyn_aibfeedbackloop](msdyn_aibfeedbackloop.md) table/entity.

|Property|Value|
|--------|-----|
|ReferencingEntity|msdyn_aibfeedbackloop|
|ReferencingAttribute|msdyn_aimodelid|
|IsHierarchical|False|
|IsCustomizable|False|
|ReferencedEntityNavigationPropertyName|msdyn_AIBFeedbackLoop_msdyn_AIModel|
|AssociatedMenuConfiguration|Behavior: UseCollectionName<br />Group: Details<br />Label: <br />Order: 10000|
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|

<a name="manytoone"></a>

## Many-To-One Relationships

Each Many-To-One relationship is defined by a corresponding One-To-Many relationship with the related table. Listed by **SchemaName**.

- [lk_msdyn_aimodel_createdby](#BKMK_lk_msdyn_aimodel_createdby)
- [lk_msdyn_aimodel_createdonbehalfby](#BKMK_lk_msdyn_aimodel_createdonbehalfby)
- [lk_msdyn_aimodel_modifiedby](#BKMK_lk_msdyn_aimodel_modifiedby)
- [lk_msdyn_aimodel_modifiedonbehalfby](#BKMK_lk_msdyn_aimodel_modifiedonbehalfby)
- [user_msdyn_aimodel](#BKMK_user_msdyn_aimodel)
- [team_msdyn_aimodel](#BKMK_team_msdyn_aimodel)
- [business_unit_msdyn_aimodel](#BKMK_business_unit_msdyn_aimodel)
- [msdyn_retrainworkflow_msdyn_toaimodel](#BKMK_msdyn_retrainworkflow_msdyn_toaimodel)
- [msdyn_scheduleinferenceworkflow_msdyn_toaimodel](#BKMK_msdyn_scheduleinferenceworkflow_msdyn_toaimodel)
- [msdyn_aitemplate_msdyn_aimodel](#BKMK_msdyn_aitemplate_msdyn_aimodel)


### <a name="BKMK_lk_msdyn_aimodel_createdby"></a> lk_msdyn_aimodel_createdby

**Added by**: System Solution Solution

See the [lk_msdyn_aimodel_createdby](systemuser.md#BKMK_lk_msdyn_aimodel_createdby) one-to-many relationship for the [systemuser](systemuser.md) table/entity.

### <a name="BKMK_lk_msdyn_aimodel_createdonbehalfby"></a> lk_msdyn_aimodel_createdonbehalfby

**Added by**: System Solution Solution

See the [lk_msdyn_aimodel_createdonbehalfby](systemuser.md#BKMK_lk_msdyn_aimodel_createdonbehalfby) one-to-many relationship for the [systemuser](systemuser.md) table/entity.

### <a name="BKMK_lk_msdyn_aimodel_modifiedby"></a> lk_msdyn_aimodel_modifiedby

**Added by**: System Solution Solution

See the [lk_msdyn_aimodel_modifiedby](systemuser.md#BKMK_lk_msdyn_aimodel_modifiedby) one-to-many relationship for the [systemuser](systemuser.md) table/entity.

### <a name="BKMK_lk_msdyn_aimodel_modifiedonbehalfby"></a> lk_msdyn_aimodel_modifiedonbehalfby

**Added by**: System Solution Solution

See the [lk_msdyn_aimodel_modifiedonbehalfby](systemuser.md#BKMK_lk_msdyn_aimodel_modifiedonbehalfby) one-to-many relationship for the [systemuser](systemuser.md) table/entity.

### <a name="BKMK_user_msdyn_aimodel"></a> user_msdyn_aimodel

**Added by**: System Solution Solution

See the [user_msdyn_aimodel](systemuser.md#BKMK_user_msdyn_aimodel) one-to-many relationship for the [systemuser](systemuser.md) table/entity.

### <a name="BKMK_team_msdyn_aimodel"></a> team_msdyn_aimodel

**Added by**: System Solution Solution

See the [team_msdyn_aimodel](team.md#BKMK_team_msdyn_aimodel) one-to-many relationship for the [team](team.md) table/entity.

### <a name="BKMK_business_unit_msdyn_aimodel"></a> business_unit_msdyn_aimodel

**Added by**: System Solution Solution

See the [business_unit_msdyn_aimodel](businessunit.md#BKMK_business_unit_msdyn_aimodel) one-to-many relationship for the [businessunit](businessunit.md) table/entity.

### <a name="BKMK_msdyn_retrainworkflow_msdyn_toaimodel"></a> msdyn_retrainworkflow_msdyn_toaimodel

**Added by**: System Solution Solution

See the [msdyn_retrainworkflow_msdyn_toaimodel](workflow.md#BKMK_msdyn_retrainworkflow_msdyn_toaimodel) one-to-many relationship for the [workflow](workflow.md) table/entity.

### <a name="BKMK_msdyn_scheduleinferenceworkflow_msdyn_toaimodel"></a> msdyn_scheduleinferenceworkflow_msdyn_toaimodel

**Added by**: System Solution Solution

See the [msdyn_scheduleinferenceworkflow_msdyn_toaimodel](workflow.md#BKMK_msdyn_scheduleinferenceworkflow_msdyn_toaimodel) one-to-many relationship for the [workflow](workflow.md) table/entity.

### <a name="BKMK_msdyn_aitemplate_msdyn_aimodel"></a> msdyn_aitemplate_msdyn_aimodel

See the [msdyn_aitemplate_msdyn_aimodel](msdyn_aitemplate.md#BKMK_msdyn_aitemplate_msdyn_aimodel) one-to-many relationship for the [msdyn_aitemplate](msdyn_aitemplate.md) table/entity.

### See also

[Dataverse table/entity reference](../about-entity-reference.md)  
[Web API Reference](/dynamics365/customer-engagement/web-api/about)  
<xref href="Microsoft.Dynamics.CRM.msdyn_aimodel?text=msdyn_aimodel EntityType" />