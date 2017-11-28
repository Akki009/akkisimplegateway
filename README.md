
## Usage
  
  
   ### HTTP POST REQUEST
  
  ```javascript   
     HttpRequest.sendPostRequest("url", null/*JSONObject*/, new ResponseHandler() {
            @Override
            public void getResponse(boolean isSuccess, String response) {
                if(isSuccess)
                {
                    System.out.println("response : "+response);
                }
                else{
                    System.err.println("error : "+response);
                }
            }
        });
        
        or 
         HttpRequest.sendPostRequestArray("url", null/*JSONArray*/, new ResponseHandler() {
            @Override
            public void getResponse(boolean isSuccess, String response) {
                if(isSuccess)
                {
                    System.out.println("response : "+response);
                }
                else{
                    System.err.println("error : "+response);
                }
            }
        });
```
   ### HTTP GET REQUEST
 ```javascript 
  
   HttpRequest.sendGetRequest("url", new ResponseHandler() {
            @Override
            public void getResponse(boolean isSuccess, String response) {
                if(isSuccess)
                {
                    System.out.println("response : "+response);
                }
                else{
                    System.err.println("error : "+response);
                }
            }
        });       
 ```
  
