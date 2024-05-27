# LeoMain-Documentation
Documentation for the LeoMain site on Shopify.

## Custom Components
Custom features on the home page:
- Box Calculator
- Image Slider
- Audio Comparison

Custom features on the main product page:
- Quantity / Price calculator *(which I assume to be depricated in the new theme)*

The HTML for these features is in the Shopify frontend editor as custom components. Change these by going into Shopify theme editor and click on the component.

Everything else regarding the components can be found here:
- Go to the admin panel
- Click "Online Store" in the left side navigator
- Click the three dots next to "Customize"
- Click "Edit Code"
- Find what you are looking for
  - Find "Advanced-Content.liquid" for Box Calculator, Audio Comparison, and Image Slider
  - Find "main-product.liquid" for custom quantity calculator on the main product page
  - Find "custom-item-functionality.css" for the component css for **all components**. Note, the old theme did not have a "custom css" area.
- Search the page for "LeoMain Custom Content"

## Disclaimer
I am not a Liquid developer. The changes I've made are surface level changes. They are not intended to update with theme changes from the Shopify editor.
If you have any questions, please email luke.leimbach@gmail.com and I will answer any questions regarding implementation.
