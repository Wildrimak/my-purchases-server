# My Purchases Server

Backend project of a RESTful API using node js to manage purchases in a supermarket

## About this project

A project of a RESTful API using nodejs with the objective of creating a system to control the monthly purchases of an individual

## Why with user stories

* I AS user WANT to register a business TO know where my purchases were made
* I AS user WANT to register a product TO know what is important to buy
* I AS user WANT to register an item TO know the price and quantity at a certain time
* I AS user WANT to register a category TO classify an item as I need
* I AS user WANT to register a situation TO determine when certain items are really needed

## Observations

* business:
  * id
  * name
  * localization

* product:
  * id
  * name
  * photo
  * brand
  * average_duration
  * score

* item:
  * id
  * business_id
  * product_id
  * price
  * quantity
  * date

* category:
  * id
  * name
  * description

* situation:
  * id
  * category_id
  * item_id
  * name
  * cash_value
