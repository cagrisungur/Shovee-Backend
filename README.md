<h1 align="center">Shopee Clone RESTful API</h1>
<p align="center">
  <img width="150" src="https://user-images.githubusercontent.com/38139389/61145525-e3635900-a501-11e9-81a3-bcd9ab3e3b4d.png"/>
</p>
<p align="center">
  Built with Express.js and MongoDB.
</p>

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Usage](#usage-for-development)
- [End Point List](#end-points)
- [Related Project](#related-project)
- [Contributors](#contributors)

## Introduction
Shopee is the leading e-commerce platform in Southeast Asia and Taiwan. It is a platform tailored for the region, providing customers with an easy, secure and fast online shopping experience through strong payment and logistical support. 

Shopee aims to continually enhance its platform and become the region’s e-commerce destination of choice. Shopee has a wide selection of product categories ranging from consumer electronics to home & living, health & beauty, baby & toys, fashion and fitness equipment. 

## Features
* Register, Login with JWT, Forget Password, Change Password
* Get and update user details
* Add product with upload image for seller
* Buy product
* Get purchase histories
* Notification for buyer after checkout with Onesignal

## Requirements
* [`npm`](https://www.npmjs.com/get-npm)
* [`Postman`](https://www.getpostman.com/)

## Usage for development
* Open CMD or Terminal and enter to the app directory
* Type npm install
* Setup .env file
* Open Postman for testing API

## End Points
1. Products
  * get /products
  * get /products/:id
  * post /products
  * patch /products/:id
  * delete /products/:id
2. Checkouts
  * get /checkout
  * post /checkout
3. Wishlist
  * get /wishlist
  * delete /wishlist/:id
4. Categories
  * get /categories
  * get /categories/:id
  * post /categories
  * patch /categories/:id
  * delete /categories/:id

## Related Project
* [Shopee Clone Frontend](https://github.com/mhdrare/Shovee-Frontend.git)

## Contributors
<center>
  <table>
    <tr>
      <td align="center">
        <a href="https://github.com/andreferi3">
          <img width="100" src="https://avatars0.githubusercontent.com/u/44439185?s=400&v=4" alt="Andre Feri Saputra"><br/>
          <sub><b>Andre Feri Saputra</b></sub>
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/dymzfp">
          <img width="100" src="https://avatars3.githubusercontent.com/u/35985089?s=400&v=4" alt="Dimas Febri Prasetyo"><br/>
          <sub><b>Dimas Febri Prasetyo</b></sub>
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/kevinmartinda">
          <img width="100" src="https://avatars1.githubusercontent.com/u/43369306?s=400&v=4" alt="Kevin Martinda Sodikin"><br/>
          <sub><b>Kevin Martinda Sodikin</b></sub>
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/mhdrare">
          <img width="100" src="https://avatars3.githubusercontent.com/u/38139389?s=400&u=39c6791d7f990cf4f7fca960b3fe040b961895c6&v=4" alt="M Faisal Akbar"><br/>
          <sub><b>M Faisal Akbar</b></sub>
        </a>
      </td>
    </tr>
  </table>
</center>
