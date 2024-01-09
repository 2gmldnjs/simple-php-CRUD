# simple-php-CRUD

 XAMPP사용   
 
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

