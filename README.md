# auth-accord-bank
req
http://localhost:8080/token/generate-token

resp
{"status":200,"message":"success","result":{"token":"eyJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJuYXRhIiwic2NvcGVzIjpbeyJhdXRob3JpdHkiOiJBQ0NPUkQifV0sImlzcyI6Imh0dHA6Ly9sb2NhbGhvc3Q6MzAwMCIsImlhdCI6MTYxOTAxMjczNCwiZXhwIjoxNjE5MDMwNzM0fQ.P7BIDVx76kI_ITsnN68esCt3Klbw-U_RqvbJN6pA-2U","username":"nata"}}

***********************************************

http://localhost:8080/users

resp
{"status":200,"message":"User list fetched successfully.","result":[{"userId":129,"active":1,"email":"test@gmail.com","lastName":"test","name":"test"},{"userId":151,"active":1,"email":"sasha","lastName":"Заграевская","name":"sasha"},{"userId":172,"active":1,"email":"nnzagraevskaya@gmail.com","lastName":"nata","name":"nata"},{"userId":181,"active":1,"email":"345","lastName":"Заграевская","name":"test345"},{"userId":182,"active":2,"email":"222","lastName":"111","name":"sasha"}]}


**********************************
http://localhost:8080/roles

resp
{"status":200,"message":"User list fetched successfully.","result":[{"roleId":3,"role":"ACCORD"},{"roleId":4,"role":"ACCORD_MOB"},{"roleId":5,"role":"IBANK"}]}
****************************************************

http://localhost:8080/departments

resp
{"status":200,"message":"User list fetched successfully.","result":[{"id":33644,"nameDepartment":"Відділення №1 04070, м.Київ, вул.Борисоглібська, 3    \n","codeIspro":"03","orderCode":1000,"branchId":2},{"id":43064,"nameDepartment":"Відділення №2 29013, м. Хмельницький, вул. Соборна, 69","codeIspro":"04","orderCode":2000,"branchId":2},{"id":43065,"nameDepartment":"Відділення №3 79010, м.Львів, вулЛичаківська,34  ","codeIspro":"05","orderCode":3000,"branchId":2},{"id":33665,"nameDepartment":"Відділення №4 054056, м. Миколаїв, проспект Миру, 56 а/1","codeIspro":"06","orderCode":4000,"branchId":2},{"id":33611,"nameDepartment":"Відділення №5  02093, м.Київ, вул.Бориспільська, 11-а ","codeIspro":"07","orderCode":5000,"branchId":2},{"id":43123,"nameDepartment":"Відділення №6 46025, м.Тернопіль, вул.Замкова,16, приміщ.49","codeIspro":"08","orderCode":6000,"branchId":2},{"id":33601,"nameDepartment":"Відділення №7 49128,м.Дніпро, вул.Братів Трофімових, 40 прим.382","codeIspro":"09","orderCode":7000,"branchId":2},{"id":33645,"nameDepartment":"Відділення №8 49055, м.Дніпро, вул.Титова, 9 прим.18.\n","codeIspro":"10","orderCode":8000,"branchId":2},{"id":33624,"nameDepartment":"Відділення №9 65113, м.Одеса, вул.Академіка  Корольова, 33\n","codeIspro":"11","orderCode":9000,"branchId":2},{"id":33625,"nameDepartment":"Відділення №10 79013, м.Львів, вул.Степана Бандери, 19 ","codeIspro":"12","orderCode":10000,"branchId":2},{"id":33612,"nameDepartment":"Відділення №11 50071, м.Кривий Ріг, вул.Мелешкина 22, прим.65","codeIspro":"13","orderCode":11000,"branchId":2},{"id":33658,"nameDepartment":"Відділення №12 65012, м.Одеса,по вул.  Катерининська, 76","codeIspro":"14","orderCode":12000,"branchId":2},{"id":43164,"nameDepartment":"Відділення №13 м.Чернівці, вул. Героїв Майдану, буд. 200 А","codeIspro":"15","orderCode":13000,"branchId":2},{"id":33636,"nameDepartment":"Відділення №14 03127, м.Київ, пр-т 40-річчя Жовтн

...
