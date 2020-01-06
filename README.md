# aws-apigateway

Api gateway is used for accessing, managing, monitoring, APIs, it also provide feature like authorization of users, throttling of API, WAF implementations. 

API gateway is much complex in design, it is not easy to work over API gateway. Main problems we face while work with API gateway -
1. It has complex structure
2. You can not copy configuration or any data to create another API gateway.
3. CORS issue is not easy to maintain. 

So if you are working with API gateway then you can understand the pain of managing it. It would be lot better if there is anything we can automate the whole API gateway configuration, deployment, staging. 

In this Repo I am presenting Terraform code of whole API gateway configuration which includes authorization, deployment, staging, implentation etc. 
