# This is my example for product card

### My name is Kirill

![my photo]()


**I'am javascript developer.**
*There is example of my code:*
```javascript
class productCard{
    imgLink;
    productName; 
    productPrice; 
    constructor(link,name,price)
    {
        this.imgLink = link;
        this.productName = name;
        this.productPrice = price;

      

        const product = document.createElement("div");
        product.innerHTML = 
        `
        <img src="${this.imgLink}">
            <h5>Name:${this.productName}</h5>
            <h5>Price:${this.productPrice}</h5>  
            <button>Buy</button>
        `
        document.body.append(product);

    }

  
}

for(let i = 0; i < 100;i++){
    new productCard ('https://evolution.by/wp-content/uploads/2023/03/I-3042T-1-min.png', 'ytug', 33);
}
```

*The product card is designed using a class,
a picture of the product, its price and a buy button are displayed*
