# store_management_system
Designing a Management System from Scratch with SQL Alchemy

I build this project following the brilliant instructions by Josh Wenner in his new [Project X #7](https://open.substack.com/pub/thenerdnook/p/project-x-7?r=4b01bc&utm_campaign=post&utm_medium=email). 

You can find this on his website [The Nerd Nook](https://thenerdnook.substack.com)

## Project Overview

This project is a Grocery Store Management System built with Python and SQLAlchemy to handle customers, products, and orders in a database. It’s divided into four main parts, each adding to the previous one to create a solid command-line tool.

## Part 1: Setting Up the Database

First, we set up an SQLite database using SQLAlchemy. We connect to the database and use SQLAlchemy’s ORM (Object Relational Mapper) to work with the data through Python objects instead of writing SQL queries. We also create a session handler to keep everything running smoothly when dealing with the data.

## Part 2: Defining Models

Next, we set up the main tables: Customer, Product, Order, and OrderItem. Each table is represented as a Python class, with the columns acting as attributes. These models create relationships between customers, their orders, and the products they buy, connecting records between tables. This part builds the structure for managing data in the app.

## Part 3: CRUD Operations

Here, we add the functions to Create, Read, Update, and Delete (CRUD) data in the database. We write functions to add new customers, products, and orders, as well as to update or remove existing records. For example, adding a new customer or product is done with just Python functions, and orders are created by linking customers to products and quantities. This part also includes functions to display all stored records.

## Part 4: User Interaction

As the cherry on top, we pull everything together with a simple command-line interface (CLI) that lets users interact with the database. The CLI provides options for adding customers, products, and orders, as well as viewing or editing the stored data. Users can easily manage inventory, customers, and orders through a menu, wrapping the CRUD functions into an easy-to-use format.

