# WebDesignAssignemnt5

2 page website to for perfumes
1. Home/About me page has a grid layout. 3 children nodes-1 for header, 1 box sidebar and 1 box content. Box content also contains education table and contact me form. 
2. When ‘My Perfume Site’ is clicked, we go to ‘The Perfumery’ page.
3. Men’s perfume has another grid with 6 grid items. Each grid item utilises a flexbox layout  in the description which has a description title and description content.
4. Women’s perfume also has a grid with 6 grid items. Each grid item utilises a flexbox layout  in the description which has a description title(perfume name) and description content(description of the perfume).
5. There’s a flexbox layout employed in the nav bar.
6. common.scss contains variables($font, $fontSizeRegular, $marginTop, etc), mixin, interpolation within the mixin(heading-styles, h1-style, etc), function( invert) and placeholder selectors which will be common to both the pages 
7. rootStyles.scss uses @import to import the common.scss and set properties like box-sizing, font family for both the pages. 
8. index.scss uses nesting to implement css in body (table, section, form). It also uses '&' to nest selectors. It is used to set the styles for the index/about me page
9. perfumery.scss is used to set the styles for the perfumery page. It loads the styles from rootStyles.scss and imports the style from common.scss. It contains 2 grids for the men’s and women’s perfume, and also contains flexbox in the description of grid items. 

