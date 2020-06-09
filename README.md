# authenticationInterceptor
jwt token verification


## usage
from authenticationInterceptor import validate_token



## sample input (in json format)
j_token =  {'Authorization':'Bearer','token':'eyJ0eXAiOiJKV1QiLCJhbGciOiJSUzI1NiJ9.eyJ1c2VyX2lkIjoxMjN9.pfZpEdAMyKdosPfmA6kCE_jELu5QyzbvdnSwTCpaDhmszOReDUcnxuU4Ou94T0I6oK5omcS3xXJq5X-EGbYyvKLvHIA2gW1Hdj9jJE2bUPNS6VK71gfXm_NXJvdd46gj9to44iGta4y47xuq_xl4G0NEAX4kMdYVhBOPs2vLJ946n8T21P7SWTxVPs2sWDUI8JoJEkxnZ8o880n5rz2BGB8H9GgUdLASRR-VhOli-hSp-YFnz2Vm1M5FM8dnznArKAZhyzetruqoZgoZK2yXN7XMdLh88bmI9DcGPf2a7Ta7mLNutV0oGtKtVvcCNJLQ5982t-TvosbuUAxfpSGVpDjJNP4VWGC3qgg0OYsaayY9R2oDUvrA-WycOH-sjNPznXJuXRup602Aq0eOFtr0nXH1m-WZdnF_H1VufkIhH2xFizRSgIspuIWIgyJFOkqSnTHkBWI9qZJeLH_MRsqUO9vnswMguMTBAbWU0qp5BhSRtHow_AGUhruaxNliOTCPkKdxAHzFULvpxzq4EUnFCJJl6czn7S1ZY26v6TlBrv9mCAY3y-FUV2Rg7GLwmJUF3b9oBxdiGJFKN7Zeyi83d4OGBMEdA6P5sS-qRItWpRcc0Q2MPzjMRtIyFA0ND9EzssCR00qUGKq2C5-XfPSM54JN_mEnxWiiuJOx4FWZS0k'}
### optionally, incase j_token is a dictionary, do the following:
* import json
* j_token = json.dumps(j_token)


## call validate_token 
val = validate_token(j_token)


## output if token is authentic
Signature verification successful	



## output if token is not authentic
Signature verification failed



## data stored in val
print(val)


## NOTE:
create environment variables for bucket name and file name in your system as follows:
* variable name = bucketname
* variable name = file_to_read
Strictly stick to the above given names.
