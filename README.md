## **KNINE Coffee**

#### By Tanner Damron
###### Initiated May 5th, 2019.
###### Website launched Aug 10th, 2019.

## Live Website Link
### https://www.kninecs.com
----------
## Project Proposal
* Name of Student: Tanner Damron.

* Name of Project: KNINE Coffee.

* Project’s Purpose or Goal: A website where users can browse products and information about KNINE Coffee as well as order KNINE Coffee products.

* List the absolute minimum features the project requires to meet this purpose or goal:
* > Routing to different pages (Home, Products, Strength, Core Values, Contact)
* > Users Email and Password saved in a database
* > Secure credit/debit card checkout page

* What tools, frameworks, libraries, APIs, modules and/or other resources (whatever is specific to your track, and your language) will you use to create this MVP? List them all here. Be specific.
* > Windows 10.1
* > Visual Studio Code (Text Editor)
* > Shopify's **.liquid** language
* > Some built in Shopify features and apps

* If you finish developing the minimum viable product (MVP) with time to spare, what will you work on next? Describe these features here: Be specific.
* > Instagram API to pull in recipe images and posts from themacrobarista

What additional tools, frameworks, libraries, APIs, or other resources will these additional features require?
* > Instagram API

## Description
This web application was built with Shopify and custom Shopify code, and will allow the user to create an account and password for KNINE Coffee, browse, search, and order KNINE Coffee products, and sign up for a mailing list.

## Blueprints
![](src/assets/blueprints/KNINE-Coffee-Blueprints-Home.png?raw=true)

## Known Bugs

* No known bugs

## Specifications

<details>
<summary>User stories and specifications</summary>

<table>
  <tr>
    <th> Scenario 01 </th><th></th>
  </tr>
  <tr>
    <td> Behavior </td>
    <td>As a user, I want to be able to create an account with KNINE Coffee.</td>
  </tr>
  <tr>
    <td> Input </td>
    <td>User enters an email and password to sign up</td>
  </tr>
  <tr>
    <td> Output </td>
    <td>User's information is saved in a database and will allow user to sign back in with the same credentials.</td>
  </tr>
  <tr>
    <td> Notes </td>
    <td> </td>
  </tr>
  <tr>
    <td> Completion </td>
    <td> True </td>
  </tr>
</table>

<table>
  <tr>
    <th> Scenario 02 </th><th></th>
  </tr>
  <tr>
    <td> Behavior </td>
     <td>As a user, I want to be able to browse this website for products</td>
  </tr>
  <tr>
    <td> Input </td>
    <td>User clicks "Products".</td>
  </tr>
  <tr>
    <td> Output </td>
    <td>User can view all KNINE Coffee products available.</td>
  </tr>
  <tr>
    <td> Notes </td>
    <td> </td>
  </tr>
  <tr>
    <td> Completion </td>
    <td> True </td>
  </tr>
</table>

<table>
  <tr>
    <th> Scenario 03 </th><th></th>
  </tr>
  <tr>
    <td> Behavior </td>
    <td>As a user, I want to be able to search for any specific product.</td>
  </tr>
  <tr>
    <td> Input </td>
    <td>User types in "Shirt" in search bar</td>
  </tr>
  <tr>
    <td> Output </td>
    <td>All products with "Shirt" in the name or description will be shown.</td>
  </tr>
  <tr>
    <td> Notes </td>
    <td> </td>
  </tr>
  <tr>
    <td> Completion </td>
    <td> True </td>
  </tr>
</table>

<table>
  <tr>
    <th> Scenario 04 </th><th></th>
  </tr>
  <tr>
    <td> Behavior </td>
    <td>As a user, I want to be able to add products to a shopping cart.</td>
  </tr>
  <tr>
    <td> Input </td>
    <td>User clicks "add product" button.</td>
  </tr>
  <tr>
    <td> Output </td>
    <td>The product that was added will be in a user's shopping cart.</td>
  </tr>
  <tr>
    <td> Notes </td>
    <td> </td>
  </tr>
  <tr>
    <td> Completion </td>
    <td> True </td>
  </tr>
</table>

<table>
  <tr>
    <th> Scenario 05 </th><th></th>
  </tr>
  <tr>
    <td> Behavior </td>
    <td>As a user, I want to be able to check out and purchase all products in my shopping cart.</td>
  </tr>
  <tr>
    <td> Input </td>
    <td>User clicks "Check Out" on the shopping cart page and is sent to a secure credit/debit card purchasing page.</td>
  </tr>
  <tr>
    <td> Output </td>
    <td>Display public profile</td>
  </tr>
  <tr>
    <td> Notes </td>
    <td> </td>
  </tr>
  <tr>
    <td> Completion </td>
    <td> True </td>
  </tr>
</table>

<table>
  <tr>
    <th> Scenario 06 </th><th></th>
  </tr>
  <tr>
    <td> Behavior </td>
    <td>As a user, I want to be able to enter my credit/debit card information to make a purchase.</td>
  </tr>
  <tr>
    <td> Input </td>
    <td>User enters credit/debit card info and clicks "Submit Purchase".</td>
  </tr>
  <tr>
    <td> Output </td>
    <td>User gets a confirmation (model & email) that the purchase was successful or denied</td>
  </tr>
  <tr>
    <td> Notes </td>
    <td> </td>
  </tr>
  <tr>
    <td> Completion </td>
    <td> True </td>
  </tr>
</table>

<table>
  <tr>
    <th> Scenario 07 </th><th></th>
  </tr>
  <tr>
    <td> Behavior </td>
    <td>As a user, I want to be able to add my email to the newsletter mailing list</td>
  </tr>
  <tr>
    <td> Input </td>
    <td>User selects "Join Newsletter" and types in user's email.</td>
  </tr>
  <tr>
    <td> Output </td>
    <td>Confirmation that the user has been added to the mailing list pops up</td>
  </tr>
  <tr>
    <td> Notes </td>
    <td> </td>
  </tr>
  <tr>
    <td> Completion </td>
    <td> True </td>
  </tr>
</table>

<table>
  <tr>
    <th> Scenario 08 </th><th></th>
  </tr>
  <tr>
    <td> Behavior </td>
    <td>As a user, I want to be able to view the about us page</td>
  </tr>
  <tr>
    <td> Input </td>
    <td>User selects "Core Values" link.</td>
  </tr>
  <tr>
    <td> Output </td>
    <td>User is taken to the about us page with all information on KNINE Coffee</td>
  </tr>
  <tr>
    <td> Notes </td>
    <td> </td>
  </tr>
  <tr>
    <td> Completion </td>
    <td> True </td>
  </tr>
</table>

</details>


## Notes
* >

## Setup and Use

#### Prerequisites
* [Node.js](https://nodejs.org/en/)
* [Node.js Package Manager (npm)](https://www.npmjs.com/)

#### Download Repo
1. Download and install required software: Node.js, npm
2. Clone [this repository](https://github.com/tannerdamron/KNINE-Coffee.git): `$ git clone https://github.com/tannerdamron/KNINE-Coffee.git`

### View Code
1. Navigate to the application directory: `$ cd KNINE-Coffee`
2. Use preferred text editor or IDE to see all code used.

#### Open Locally
N/A

#### Edit
1. Navigate to the application directory: `$ cd KNINE-Coffee`
2. Use your preferred IDE or editor to edit the project


## Built With

* Windows 10.1
* Visual Studio Code (Text Editor)
* JavaScript
* CSS
* Shopify
* Shopify's **.liquid** language

## Contact

[tanner.mdamron@gmail.com](mailto:tanner.mdamron@gmail.com)

If you have any feedback or concerns, please contact any of the contributors.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). Copyright (C) 2019 Tanner Damron. All Rights Reserved.
```
MIT License

Copyright (c) 2019 Tanner Damron

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## Acknowledgments

#### [Epicodus](https://www.epicodus.com/)
>"A school for tech careers... to help people learn the skills they need to get great jobs."

#### [The Plato System](https://en.wikipedia.org/w/index.php?title=PLATO_system&redirect=yes)
>"PLATO had sprouted a variety of novel tools for online communication, including Personal Notes (email), Talkomatic (chat rooms), Term-Talk (instant messaging), monitor mode (remote screen sharing) and emoticons."

#### [The Internet](https://webfoundation.org/)
> "...the first thing that humanity has built that humanity doesn't understand..."
> - Eric Schmidt, Google (Alphabet Inc.)
