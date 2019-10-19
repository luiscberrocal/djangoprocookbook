# Chapter 4

```groovy
#$MODEL$ CRUD urls
path('$MODEL_LC$/list/', $MODEL_UNDER$_list_api_view, name='list-$MODEL_LC$'),
path('$MODEL_LC$/create/', $MODEL_UNDER$_create_api_view, name='create-$MODEL_LC$'),
path('$MODEL_LC$/update/<int:pk>/', $MODEL_UNDER$_detail_api_view, name='update-$MODEL_LC$'),
path('$MODEL_LC$/delete/<int:pk>/', $MODEL_UNDER$_detail_api_view, name='delete-$MODEL_LC$'),
path('$MODEL_LC$/<int:pk>/', $MODEL_UNDER$_detail_api_view, name='detail-$MODEL_LC$'),
```
