# Tips-Tricks
This repository is talks about few issues that I've faced while developing projects and solutions for them
If you get site can't be reached when running angular project using ng serve, use ng serve --host 0.0.0.0


Module not found: Error: Can't resolve 'stream' in 'C:\softies\1MES\routemanagement-app\node_modules\jszip\lib'
Add "paths": {
      "jszip": [
        "node_modules/jszip/dist/jszip.min.js"
      ]
    } 
    
 in tsconfig.json
