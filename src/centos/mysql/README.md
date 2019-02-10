# centos-mysql

실행
* docker run -it jobjava00/mysql:latest /bin/bash
* mysql 실행
    * mysqld --skip-grant-tables --user=root &
        * --skip-grant-tables : 패스워드 확인 하지 않는 옵션
    * mysql -uroot -e "create database test;"
        * mysql 실행 시 test 데이터베이스 생성
