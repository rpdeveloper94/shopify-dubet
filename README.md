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

3)after added product to assign products categories and save Products

4)create new file on sections dir.
***like this one***
a)related-products.liquid {view for related products}
b)recommended-products.liquid {view for recommanded products}

5)now go to my sample code of related-products.liquid or recommended-products.liquid and copy the code and move to paste from your file.

6)Goto product.liquid file and included both of section file as your choice.

***note:*** 
	**we can handle to products as per requirement.***
	***like size of products, view of products in row (add limit), add filters (vandor,variant objects) etc...***
	https://help.shopify.com/en/themes/liquid/objects/product
