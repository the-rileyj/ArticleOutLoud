# Article Out Loud

## Directory Structure

### back-end/

The back-end infrastructure which powers the website. Consisting of the Go webserver, the static files for the SPA website, and the Postgres database.

### front-end/

The React website development in typescript

## How it Works

A customer buys a package that allows them to have their article read out loud.

Either they host the mp3 on their own or pay monthly to have it stored for them.

A html widget is authomatically generated so that they can embed the reader into their article, a new widget can be generated (for free) if they change the location of where their mp3 is hosted.

## Need

- Accounts

  Need accounts so that customers can buy things and have items related to their account

  - Customer can have items related to boughten items stored in account

    - the html widget which is generated from the hosted link)

      - Storing the currently hosting link so that the widget can be generated from it

- Payment Processing

  - So that customers can purchase products

- Product Options

  - Single time payment for only mp3 file

    - No hosting after 3 day grace period

  - Monthly subscriptions with a certain amount of article allotted per money

    - Like the competitor

    - Monthly subscription ensures MP3's are stored

      - Only stored if

      - a. The mp3 was boughten while the subscription was in place

      - b. the subscription was boughten and an existing mp3 which was purchased before the subscription was still in it's download grace period

- Text-To-Speech generators

  - Voices and languages to choose from

  - Output in MP3 format