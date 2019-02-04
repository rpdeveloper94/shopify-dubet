# shopify-debut
this is a base theme of shopify called by debut theme..

I have represent 3 type's of product listing view solution on Product detail page

### Point of view
```bash
1)if you have no products so import to configured products and add manually as per choice,
or
install free app of [oberlo]
```
2)Goto oberalo deshboard and import Products as per your choice

3)after that assign selected products in categories (as your choice).

4)create new file from section directory.
***like this one***
a)related-products.liquid {view for related products}
b)recommended-products.liquid {view for recommanded products}

5)You must be check both files of My sample code from same directoy.

```bash
   shopify-debut/sections/related-products.liquid
   shopify-debut/sections/recommended-products.liquid
```

6)Goto product.liquid file and included both of section file as your choice.

***note:*** 
	**we can handle to products as per requirement.***
	***like size of products, view of products in row (add limit), add filters (vandor,variant objects) etc...***
	https://help.shopify.com/en/themes/liquid/objects/product
