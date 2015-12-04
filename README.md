cp welcome app1 -rf

# 20151204
cd /usr/local/web2py/application/app1/controllers

   vim test.py

   def hello():
      return "hello"

   # http://127.0.0.1:8000/app1/test/hello

   def helloworld():
      return "<html><body><h1>Hello World</h1><body></html>"

   # http://127.0.0.1:8000/app1/test/helloworld
   
   
  * hello world 파일을 만들고 web2py로 실행시 invalid function이 뜰 경우 app1 폴더 삭제하고 다시 만들기
