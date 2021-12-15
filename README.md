# DATABASE-MODEL
its a mysql database model

//procedure to create

//1
create database dbmodel;
//2
use dbmodel;
//3
CREATE TABLE ZEN_CLASS( DAY INTEGER, TOPIC TEXT, TASK TEXT,MENTOR TEXT);
//4
INSERT INTO CLASS (DAY,CLASS_TOPIC,TASK,MENTOR) VALUES
(1,"Introduction to Browser & web","Read About Introduction to Browser & web","Ragav kumar"),
 (2,"Request & Response cycle","Read about Request & Response cycle","Ragav kumar"), 
 (3,"JS array & objects","Practice Looping Of Arrays & Objects","Ragav kumar"),
  (4,"What is XMLHTTP Request? & scope","Practice XMLHTTP Request and scope","Ragav kumar"),
   (5,"Functions","Practice IIFE & Annoymous Function","Ragav kumar"),
    (6,"Functions recap","Practice Functions","Ragav kumar"),
     (7,"ES5 vs ES6","Practice the Es5 and Es6 concepts","Ragav kumar"),
      (8,"OOP","Practice OOP","Ragav kumar"), 
      (9,"MRF Array Method","MRF Method","Ragav kumar"), 
(10,"Complete Recap","Recap every topic covered","Ragav kumar");
