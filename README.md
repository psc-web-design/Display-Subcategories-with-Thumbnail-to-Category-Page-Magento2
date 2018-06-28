# Display-Subcategories-with-Thumbnail-to-Category-Page-Magento2
This will help you display subcategories with thumbnail on category page. Tested on Magento version 2.2

1. First you need to duplicate "SubcategoriesThumbnail.phtml" from repo in app/design/frontend/Theme/theme_name/Magento_Theme/templates/html/SubcategoriesThumbnail.phtml

2. Create a Block in Magento with the code from repo file "Magento2 Block"

3. Go to Category > Content > Add CMS Block and then Category > Display Settings > Display Mode > Static Block Only

4. Dont fogrget to add thumbnails images to subcategories before displaying them in category page

5. php bin/magento setup:upgrade && php bin/magento setup:static-content:deploy -f && php bin/magento cache:flush

For more informations about this please contact me and i will be back asap. Enjoy!
   
