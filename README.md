# shopping-cart-restock

### MY COMMENTS

- Noticed that there is no need to do a doFetch call, as it retrieves the information on declaration time on line ~94. It would only be necessary if you expect that the items at Strapi server will change during the course of program's execution. I included it just to confirm it does the HTTP GET request

- The data retrieved from Strapi has a different format than our products object, so there is need to reformat
