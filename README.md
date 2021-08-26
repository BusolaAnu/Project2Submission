> **Project Overview**
> This project Operationalizing machine learning entails creating an Automated Machine learning model, deploying the best model as a webservice using Azure Container Instance, which will be consumed via an API endpoint, creating and publishing a pipeline as a service with an endpoint so as to remotely trigger experiment runs and testing the pipeline with an API request through the API endpoint.

> 
> **Architectural Diagram**
> 
> ![image](https://user-images.githubusercontent.com/86358182/129568848-40023aab-faa5-428a-9878-da4debdf1d81.png)

**Project Improvement**

Performing feature transformation on the data set could help improve the model performance in future. This is a very important aspect of machine learning that can greatly affect the model performance.
> 
> The major steps taken in this project are as shown in screenshots below:
> 
> ![image](https://user-images.githubusercontent.com/86358182/129561473-29c606fb-c1ed-4410-b966-1238a929ba52.png)
> 
> _Image showing the bank marketing dataset registered on the azure platform._
> 
> 
> ![image](https://user-images.githubusercontent.com/86358182/129561623-c03c3ee2-9a4f-435c-bb9d-1428d3561653.png)
> 
> _Image showing completed Auto ML model, the best algorithm and the accuracy score._


> ![image](https://user-images.githubusercontent.com/86358182/129561868-485e55aa-45c0-4da3-ae25-4ead01dcaec1.png)
> ![image](https://user-images.githubusercontent.com/86358182/129561877-c02cfdfb-4b47-4f09-8cf8-71eff1afadbe.png)
> 
> _Images showing logs was enabled._


> ![image](https://user-images.githubusercontent.com/86358182/129562064-141d2bbe-2307-4e5e-85da-8d20682235ec.png)
> 
> _Application Insights enabled._
> 
> 
> ![image](https://user-images.githubusercontent.com/86358182/129562264-f6ca59e2-7a34-42b6-af87-4c81012524a8.png)
> ![image](https://user-images.githubusercontent.com/86358182/129562288-a1160ef8-27f5-4931-9e77-61d6c78bc5c5.png)
> 
> _Swagger Documentation_
> 
> 
> ![image](https://user-images.githubusercontent.com/86358182/129562347-584ad063-3390-4548-8ccd-e785074fb866.png)
> 
> _Image showing endpoint.py script runs against the API producing JSON output from the model_
> 
> 
> ![image](https://user-images.githubusercontent.com/86358182/129563182-33f47ec5-198a-403f-ac34-479344b7be0f.png)
> 
> _Image showing the pipeline was created and completed from pipeline section in Azure ML studio._
> 
> 
> ![image](https://user-images.githubusercontent.com/86358182/129563414-c51af483-83bf-45fd-b5fb-5a481042fb68.png)
> ![image](https://user-images.githubusercontent.com/86358182/129563241-6be2fce4-1c70-4633-9adb-c7b0e921ab4d.png)
> 
> _Images showing the pipeline endpoint, a rest endpoint and a status of Active._
> 
> 
> ![image](https://user-images.githubusercontent.com/86358182/129563490-a1bf62ca-104f-4b78-af12-95f6caa2ec80.png)
> 
> _Image showing that the "Use RunDetails widget" shows the step runs_

![image](https://user-images.githubusercontent.com/86358182/130884188-447157eb-5401-4e73-af5d-41d6adb2b8ec.png)
![image](https://user-images.githubusercontent.com/86358182/130884556-095b3b85-79f0-42d6-adcb-9ba0ddb27296.png)

Image showing the Published Pipeline overview showing a REST endpoint and a status of Active

![image](https://user-images.githubusercontent.com/86358182/130884598-01027c37-ab7c-4e2f-b735-85ea0433a978.png)

Image showing a sheduled run
> 
> 
> **Screen cast for this project is available** [here](https://youtu.be/w55XiaQWDUY)
