**Project Name : Sales Vision**


## Screenshots :


<img width="906" alt="image" src="https://github.com/vishw094/Sales-Vision/assets/123936869/456195a9-313e-47e7-b5f3-b93f32acc9d0">

<img width="959" alt="image" src="https://github.com/vishw094/Sales-Vision/assets/123936869/8a8e2687-e232-4d5c-b01f-1f1d8ac4f6c7">

<img width="602" alt="image" src="https://github.com/vishw094/Sales-Vision/assets/123936869/50b904ee-fd74-490d-a19b-912a3990ee44">

Installation Instructions  
--
(For python backend to run, download code runner and ensure you have these libraries installed. Run the python backend using coderunner)   
```pip install flask os pickle pymongo datetime pandas statsmodels flask_cors prophet```    

(For node backend, either setup a cloud mongodb and change URI accordingly or download mongodb community server as it currently runs on local community server)  
Install the following, `npm i bcrpytjs express cors body-parser mongoose nodemon`  
`nodemon index.js` or `node index.js` to run  

(For frontend)  
`npm i `  
`npm start  `

## Additional Info  
--
Dashboard will crash as there is no data initially, for that once logged in change URL to http://localhost:3000/graphsPanel  
and upload an excel file (as per the format one column, first row = category name, second row = region/continent name, all other rows = sales data)  

## READ (Known Issues)  

Do not upload the same file twice (same name)  
Do not click on file upload from Dashboard route, only upload files from "File Upload" that is /graphsPanel route  

