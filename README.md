# 🚀 Backend-AgroMaket

Strapi comes with a full featured [Command Line Interface](https://docs.strapi.io/dev-docs/cli) (CLI) which lets you scaffold and manage your project in seconds.

### Endpoints

```
https://clever-beauty-47c85a7410.strapiapp.com/
```

### Get all Product


```
GET  /api/products?pagination[page]=1&pagination[pageSize]=34&populate=*
```
Example: https://clever-beauty-47c85a7410.strapiapp.com/api/products?pagination[page]=1&pagination[pageSize]=34&populate=*

### Get a Single Product


```
GET  /api/products?filters[productId][$in][0]=2&populate=*
```
Example: https://clever-beauty-47c85a7410.strapiapp.com/api/products?filters[productId][$in][0]=2&populate=*

### Filter Product by Category
```
GET  /api/products?filters[categroy][categoryId][$eq]=1&populate=*
```
Example: https://clever-beauty-47c85a7410.strapiapp.com/api/products?filters[categroy][categoryId][$eq]=1&populate=*
