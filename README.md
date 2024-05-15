
![330363534-5c6e2fa4-efff-4e8d-9915-acc271ab3a2c](https://github.com/magmodules/magento2-distance-based-shipping-hyva/assets/24823946/1c443125-7ba2-4cc0-9bd5-23044402a0dd)



# Shipping Costs Based on Distance Hyvä Compatibility plugin


Calculate the exact shipping costs based on the distance to the delivery address using the Google Maps API.

- [Magento 2.4.+](https://github.com/magento/magento2)
- [Hyvä](https://github.com/hyva-themes)
- [Magmodules Distance Shipping](https://www.magmodules.eu/magento2-shipping-costs-based-on-distance.html)    



## About the Shipping Costs Based on Distance Plugin

Introducing our Magento 2 extension for automated shipping cost calculation based on distance. Utilizing the Google Maps API, it calculates actual transport route distances, ensuring accurate shipping costs. Easily configurable, set your per kilometer rate and display costs on the checkout page. 

Enhance customer convenience with a shipping cost calculator on the product page. Requires an active Google API Key. Ideal for both in-house and external courier deliveries, it provides full control over shipping cost settings. Flexible options allow customization to your preferences, including address entry, distance units, calculation methods, and error handling. Global coverage with country-specific settings available. Experience unmatched flexibility with tailored shipping rates based on distance and order values.

Overall, the Shipping Costs Based on Distance plugin for Magento, with its seamless compatibility with the Magento Hyva theme, provides an excellent solution for integrating the Shipping Costs Based on Distance shipping method into your Magento store. 
## Installation

1. Install the module using composer: 

```bash
composer require magmodules/magento2-distanceshipping-hyva
```

2. Enable the module:

```bash
bin/magento module:enable Magmodules_HyvaDistanceBasedShipping
```

3. Upgrade the database:

```bash
bin/magento setup:upgrade
```

4. Let Hyvä know about the new module:

```bash
php bin/magento hyva:config:generate
```

5. Generate the CSS files:

```bash
npm --prefix vendor/hyva-themes/magento2-default-theme/web/tailwind/ run ci
npm --prefix vendor/hyva-themes/magento2-default-theme/web/tailwind/ run build-prod
```

Or from your theme:

```bash
npm --prefix app/design/frontend/<Vendor>/<Theme>/web/tailwind run ci
npm --prefix app/design/frontend/<Vendor>/<Theme>/web/tailwind run build-prod
```

## Shipping Costs Based on Distance Magento plugin features

- Customize your store/warehouse location
- Select distances in kilometers or miles according to your preference
- Personalize your calculation methods
- Blend per kilometer pricing with fixed rates
- Define maximum delivery ranges
- Automated address verification with error alerts for unrecognized addresses
  
## Magento Support

If you have any questions, please fill out our secure contact form by clicking [here](https://www.magmodules.eu/support-form.html).

## Magmodules & Hyva

Magmodules and Hyva have established a strong partnership, working closely together to provide enhanced e-commerce solutions. As an official Hyva partner, we specializes in developing integrations for various platforms and services. 

We have created integrations for well-known providers such as Mollie, Sooqr, Paazl, and many more. This collaboration ensures seamless compatibility and optimized performance for online stores utilizing the Hyva theme. Through our partnership, Magmodules and Hyva strive to deliver comprehensive and tailored solutions to meet the diverse needs of e-commerce businesses.



## Check out our other Hyva Plugins!

[Magento 2 Hyvä Google Reviews](https://github.com/magmodules/magento2-googlereviews-hyva) 

[Magento 2 Hyvä Shopreview](https://github.com/magmodules/magento2-shopreview-hyva) 
 
[Magento 2 Hyvä Product Review Reminder](https://github.com/magmodules/magento2-reviewreminder-hyva) 

[Magento 2 Hyvä eKomi Reviews](https://github.com/magmodules/magento2-ekomi-hyva) 

[Magento 2 Hyvä FeedbackCompany Reviews](https://github.com/magmodules/magento2-feedbackcompany-hyva) 

[Magento 2 Hyvä Mollie](https://github.com/mollie/magento2-hyva-checkout) 

[Magento 2 Hyvä Paazl](https://github.com/Paazl/magento2-hyva-react-checkout) 
