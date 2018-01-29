# Inspiration

As a lazy eater, it pains me to prepare food and although switching to Soylent seemed nice, I wasn't sure of getting all that I needed - especially when doing sports. So, I found myself wishing for a program that could take one look at my fridge and tell me what to mix in order to get my daily recommended doses.

# Possible implementation

## Simpler: barcode scanning

Barcodes are everywhere and on most items from the supermarket. Naturally, they are indexed [openfood.org](https://www.foodrepo.org)with an [API](https://www.foodrepo.org/api-docs/swaggers/v3). 

Once items of the fridge are scanned in, they could be mixed with an opensource recipe API \(if there are any\), to find recipes that contain a certain amount of the daily recommended doses.

## Advanced: machine learning

Item scanning using machine learning to recognize items without barcodes and guess their nutritional values. Additionally, recommendations could start being made depending on what the user has most commonly mixed or new recipes could be created from that as well.

