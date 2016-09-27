# Cài đặt Django trên hệ điều hành Ubuntu

Thực hiện: Thi Minh Nhựt - Email: thiminhnhut@gmail.com

Thời gian: Ngày 27 tháng 09 năm 2016

## Tài liệu tham khảo

1. [Django Web Development with Python Introduction](https://pythonprogramming.net/django-web-development-with-python-intro/)

2. [How to get Django](https://www.djangoproject.com/download/)

## Cài đặt Django trên hệ điều hành Ubuntu

* Cài đặt `python-pip` (nếu chưa cài đặt):

		sudo apt-get install python-pip
		
* Cài đặt `Django` phiên bản mới nhất bằng `python-pip`: truy cập vào địa chỉ [How to get Django](https://www.djangoproject.com/download/), 
di chuyển đến mục `Option 1: Get the latest official version`, thực hiện lệnh theo hướng dẫn cài đặt phiên bản `Django` mới nhất, ví dụ:

		sudo pip install Django==1.10.1
		
* Kiểm tra quá trình cài đặt thành công hay chưa:

	+ Viết script `django-version.py` với nội dung như sau:
	
			import django
			
			print "Django version: " + django.__version__
			
		Nếu cài đặt phiên theo lệnh bên trên, thì kết quả trả về là:
		
				Django version: 1.10.1

	+ Tải script [django-version.py](https://github.com/h3int2um/django/blob/master/django-tutorials/code-django-tutorials/django-version.py)
	
* Nếu kết quả chưa đúng phiên bản cài đặt, kiểm tra và thực hiện kỹ lại các bước trên.
