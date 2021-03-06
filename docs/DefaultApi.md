# \DefaultApi

All URIs are relative to *https://cvd.xiaoduoai.com/v1/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**MatchQuestion**](DefaultApi.md#MatchQuestion) | **Post** /match_question | 



## MatchQuestion

> MatchQuestionRsp MatchQuestion(ctx, unitId, channelId, salt, sign, userId, nick, question)



### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**unitId** | **int32**| 企业ID | 
**channelId** | **int32**| 渠道ID | 
**salt** | **string**| 签名加盐,生成方式如下 | 
**sign** | **string**| 签名,生成方式如下 | 
**userId** | **string**| 用户ID,要求全局唯一 | 
**nick** | **string**| 用户昵称 | 
**question** | **string**| 用户提问 | 

### Return type

[**MatchQuestionRsp**](MatchQuestionRsp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

