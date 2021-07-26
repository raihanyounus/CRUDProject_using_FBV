# CRUDProject_using_FBV
#  Complete Update - Required All Data from Front End/Client 
#  Partial Update - All Data not required
and partial should be True
and for complete update no need of partial field
#serializer = StudentSerializer(stu, data=pythondata, partial=True)
                                                      
# json_data = JSONRenderer().render(res)
# return HttpResponse(json_data, content_type='application/json')
For above two lines we can write below code by importing JsonResponse
 #return JsonResponse(res, safe=False)
