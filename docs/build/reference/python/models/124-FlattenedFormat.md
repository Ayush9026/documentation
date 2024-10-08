---
title: FlattenedFormat | Python SDK
---

# FlattenedFormat

A representation of Data for a particular Form Factor of an Asset.[DAG Compatible - Directed Acyclic Graph Data Structure]  FlattenedFormats prevent Cycles in Reference because all outbound references are strings as opposed to crosspollinated objects.  i.e. FlattenedFormat.asset is Type String  fragment or file will always be defined. Even thought they are both optional.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**var_schema** | [**EmbeddedModelSchema**](EmbeddedModelSchema) |  | [optional] 
**id** | **str** |  | 
**creator** | **str** |  | 
**classification** | [**Classification**](Classification) |  | 
**icon** | **str** |  | [optional] 
**role** | [**Role**](Role) |  | 
**application** | [**Application**](Application) |  | 
**asset** | **str** | A uuid model. 36 Characters (4 Dashes, 32 Numbers/Letters)  | 
**bytes** | [**ByteDescriptor**](ByteDescriptor) |  | 
**created** | [**GroupedTimestamp**](GroupedTimestamp) |  | 
**updated** | [**GroupedTimestamp**](GroupedTimestamp) |  | 
**deleted** | [**GroupedTimestamp**](GroupedTimestamp) |  | [optional] 
**synced** | [**GroupedTimestamp**](GroupedTimestamp) |  | [optional] 
**cloud** | **str** | This is a path used to determine what path this format lives at within the cloud. | [optional] 
**fragment** | [**FragmentFormat**](FragmentFormat) |  | [optional] 
**file** | [**FileFormat**](FileFormat) |  | [optional] 
**analysis** | [**FlattenedAnalysis**](FlattenedAnalysis) |  | [optional] 
**relationship** | [**Relationship**](Relationship) |  | [optional] 
**activities** | [**FlattenedActivities**](FlattenedActivities) |  | [optional] 


