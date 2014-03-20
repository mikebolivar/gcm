Just you need add/link the google play services library to your project.

This code work with Android Google Apis 17


To send some notification you must send via post (you can test this with POSTMAN)

Content-Type: application/json
Authorization: key=YOUR_API_KEY
Cache-Control: no-cache

{ "collapse_key": "my_current_collapse_key", 
  "time_to_live": 108, 
  "delay_while_idle": true, 
  "data": { 
      "data1": "something", 
      "data2": "some important" 
  }, 
  
  "registration_ids":[YOUR_ID_REGISTER] 
}
