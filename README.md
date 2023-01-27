# _Furniture-ecommerce_

 ### _Description_
 >This Project is framed within a practice guided by the FreeCodeCamp platform which provides excellent quality training courses.
  This Project is part of a Javascript guided practice by the FreeCodeCamp platform which provides excellent quality training courses.
  This ecommerce contains a series of products within the furniture sector, it presents functions that allow us to add products to the cart, add products individually,     delete products individually, add the total of the products and empty the cart.
  This project also contains a series of styles and effects to give the user a better experience.

## _View Deployment_
[Go to the Site](https://fernandomoyano.github.io/Furniture-ecommerce/)


## _Lenguages_
<link rel="stylesheet" href="devicon.min.css">

<div "style=inline_block"><br>

 <img width="50px" height="50px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original-wordmark.svg" />
 <img width="50px" height="50px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original-wordmark.svg" />
 <img width="50px" height="50px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" />
 </div>
 
 ## _Style Guides_
 
 ### _Colors_
 ``` css
  --primaryColor: #f09d51;
  --mainWhite: #fff;
  --mainBlack: #222;
  --mainGrey: #ececec;
  --mainSpacing: 0.1rem;
  --mainTransition: all 0.3s linear;
 ```
 
 ### _Tipography_
 ``` css
 @import url("https://fonts.googleapis.com/css?family=Lato:400,700");
 ```
 ### _Functions_
 ``` javascript
 getProducts();
 displayProducts();
 getBagButtons();
 setCartValues();
 addCartItem();
 showCart();
 populateCart();
 hideCart();
 clearCart();
 removeItem();
 ```
 ### _Products.json_
 ``` javascript
 {
  "items": [
    
    {
      "sys": {
        "id": "1"
      },
      "fields": {
        "title": "queen panel bed",
        "price": 10.99,
        "image": {
          "fields": {
            "file": {
              "url": "./images/product-1.jpeg"
            }
          }
        }
      }
    },


    {
      "sys": {
        "id": "2"
      },
      "fields": {
        "title": "king panel bed",
        "price": 12.99,
        "image": {
          "fields": {
            "file": {
              "url": "./images/product-2.jpeg"
            }
          }
        }
      }
    },


    {
      "sys": {
        "id": "3"
      },
      "fields": {
        "title": "single panel bed",
        "price": 12.99,
        "image": {
          "fields": {
            "file": {
              "url": "./images/product-3.jpeg"
            }
          }
        }
      }
    },


    {
      "sys": {
        "id": "4"
      },
      "fields": {
        "title": "twin panel bed",
        "price": 22.99,
        "image": {
          "fields": {
            "file": {
              "url": "./images/product-4.jpeg"
            }
          }
        }
      }
    },


    {
      "sys": {
        "id": "5"
      },
      "fields": {
        "title": "fridge",
        "price": 88.99,
        "image": {
          "fields": {
            "file": {
              "url": "./images/product-5.jpeg"
            }
          }
        }
      }
    },


    {
      "sys": {
        "id": "6"
      },
      "fields": {
        "title": "dresser",
        "price": 32.99,
        "image": {
          "fields": {
            "file": {
              "url": "./images/product-6.jpeg"
            }
          }
        }
      }
    },


    {
      "sys": {
        "id": "7"
      },
      "fields": {
        "title": "couch",
        "price": 45.99,
        "image": {
          "fields": {
            "file": {
              "url": "./images/product-7.jpeg"
            }
          }
        }
      }
    },


    {
      "sys": {
        "id": "8"
      },
      "fields": {
        "title": "table",
        "price": 33.99,
        "image": {
          "fields": {
            "file": {
              "url": "./images/product-8.jpeg"
            }
          }
        }
      }
    }
  ]
}
```
 

