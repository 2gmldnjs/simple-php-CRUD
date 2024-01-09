# simple-php-CRUD

 XAMPP사용   

기본페이지   
![image](https://github.com/2gmldnjs/simple-php-CRUD/assets/69203345/35413bdd-b71e-4b67-85ab-b88b6ebee48d)   

글읽기   
![image](https://github.com/2gmldnjs/simple-php-CRUD/assets/69203345/40df78ed-416e-495f-beb8-cc1cdc21a9a8)   

글수정   
![image](https://github.com/2gmldnjs/simple-php-CRUD/assets/69203345/01b51364-1802-4f95-aee4-96e75bc73e33)   
![image](https://github.com/2gmldnjs/simple-php-CRUD/assets/69203345/360b58c3-7088-4ac0-bbe4-f03fbcfaadeb)   
![image](https://github.com/2gmldnjs/simple-php-CRUD/assets/69203345/a0614b39-cfee-4653-8648-eacd7cb0fbe3)   

글삭제   
![image](https://github.com/2gmldnjs/simple-php-CRUD/assets/69203345/7740d3ee-8a74-4147-a471-b602b664c756)   
![image](https://github.com/2gmldnjs/simple-php-CRUD/assets/69203345/5f3fc4e5-0199-484f-a17e-a51a291290de)   

글쓰기   
![image](https://github.com/2gmldnjs/simple-php-CRUD/assets/69203345/e86896c5-d9ba-403f-83ae-5424fdbfdc6f)   
![image](https://github.com/2gmldnjs/simple-php-CRUD/assets/69203345/ed855c8c-97c1-4cc7-82f5-74a48797a6cc)   
![image](https://github.com/2gmldnjs/simple-php-CRUD/assets/69203345/48b27dea-ca7f-4aed-bc83-4c90ce7b111d)   



Board 테이블   

idx : 게시판 일련번호(auto_increment 설정, 기본 키)   
name : 회원의 아이디    
title : 게시글 제목   
content : 게시글 내용   
date : 게시글 작성 날짜    
hit : 게시글 조회수   

 DB   
 CREATE TABLE board (    
    idx INT NOT NULL AUTO_INCREMENT ,   
    name VARCHAR(100) NOT NULL ,   
    title VARCHAR(100) NOT NULL ,   
    content TEXT NOT NULL ,   
    date DATE NOT NULL ,   
    hit INT NOT NULL ,   
    PRIMARY KEY (`idx`)   
    );   

