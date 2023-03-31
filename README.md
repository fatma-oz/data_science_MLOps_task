### The works i have done

* To run the project with venv

    - cd Desktop/skenariolabs_task/ml-ops
    - python3 -m venv venv
    - source venv/bin/activate
    - pip install -r requirements.txt
    - python src/__main__.py

* Done some needed changes in requirement.txt (-->> add request version and some version changes)

* Created monitoring_testing.py file 

* Imported monitoring_testing to main.py file

* Arranged codes in main.py

* Changed "2" and "19720" -->> 2 and 19720 in the request_item file (because they are defined as integer)

* Runned ml-ops file on the terminal (HTTP 404,402,422 errors received , I tried to solve) 
error: {"detail":[{"loc":["body"],"msg":"field required","type":"value_error.missing"}]}


### Read me

To run the project
- Create a venv for the project and install the libraries in requirements.txt
- run in the project root
    
        python  src/__main__.py

Or equivalently
- install docker compose
- run in the project root
    
        docker compose up
  




