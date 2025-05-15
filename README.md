#  Functional requirements

## Register books

We need to be able to put into a dictionary, somethin like this:

{


    Unique ID: n, 
    Title: Text, 
    Author: Text,
    Publication: An int between 1500 and today,
    Category: It's up to us,
    Status: Available or not available
}

## Book list

Wee need to show the dictionary elements so user can see what books are there and their status.

## Search books

User will type the title, author or category and see if the book exist or not and the status of it.

## Lend 

Here we need to change a book status based on:

Is it available?


The book exist and is not lended?


Register lender name and date using datetime


A book can only be lended 3 times by person

# Return a book

Label a book as returned if the status is "lended"

## Show lended books

We need to show the dictionary elements with status "Lended" showing who lended it and when

## Delete a book

Delete a dictionary element only if the status is "Available"

