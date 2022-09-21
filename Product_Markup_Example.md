[
    {
      "@context": "http://schema.org",
      "@type": "Product",
      "name": "ABC",
      "description": "ABC",
      "url": "https://www.example.com/example01",
      "sku": "123456",
      "offers": [
        {
          "@type": "Offer",
          "price": "10.99",
          "priceValidUntil": "2023-12-31",
          "priceSpecification": {
            "price": "10.99",
            "priceCurrency": "USD",
            "valueAddedTaxIncluded": "false"
          },
          "priceCurrency": "USD",
          "availability": "http://schema.org/InStock",
          "url": "https://www.example.com/example01",
          "seller": {
            "@type": "Organization",
            "name": "ABC.com",
            "url": "https://www.example.com/"
          }
        }
      ],
      "itemCondition": "https://schema.org/NewCondition",
      "material": "Plastic",
      "image": [
        "https://www.example.com/images/D/example01.jpg",
        "https://www.example.com/images/D/example02.JPG"
      ],
      "audience": {
        "audienceType": [
          "female"
        ],
        "@type": "PeopleAudience"
      },
      "brand": {
        "name": "example.com",
        "@type": "Brand"
      }
    }
  ]
