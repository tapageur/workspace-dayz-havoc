* Update key binding summary

* Add daily reboot over night

* How to change max deposit money
  * MaxDepositMoney
  * MaxPartyDepositMoney
  * See: https://github.com/salutesh/DayZ-Expansion-Scripts/wiki/%5BServer-Hosting%5D-General-Market-Settings

* How to add items to the traders
  * BuildingSupplies.json
    * Blueprint book
    * Plank?
    * Wooden Log?
    * Cement?
    * Mortar?
  * Components.json
    * Code lock (1250)
  * Vehicles
    * Trolley (Electric) Spur_Trolley_E_Kart
    * Trolley (Gaz) Spur_TrolleyKart
  * Vehicle_Parts.json
    * Airdrop Flares (10000)
    * Trolley (1250) Spur_WonkyTrolley
    * Trolley Seat (250) Spur_Kart_Seat
    * Trolley Front Wheel (200) Spur_Kart_Wheel
    * Trolley Rear Wheel (300) Spur_Kart_WheelRear
  * See: https://github.com/salutesh/DayZ-Expansion-Scripts/wiki/%5BServer-Hosting%5D-Adding-a-new-Item-to-the-market

Added to ExpansionMod/Market/Cars.json
        {
            "ClassName": "Spur_Trolley_E_Kart",
            "MaxPriceThreshold": 6750,
            "MinPriceThreshold": 3250,
            "SellPricePercent": -1.0,
            "MaxStockThreshold": 20,
            "MinStockThreshold": 10,
            "QuantityPercent": -1,
            "SpawnAttachments": [
                "Spur_Kart_Wheel",
                "Spur_Kart_Wheel",
                "Spur_Kart_WheelRear",
                "Spur_Kart_WheelRear",
                "truckbattery",
                "headlighth7",
                "headlighth7"
            ],
            "Variants": []
        }  
        
Added to ExpansionMod/Market/Vehicle_Parts.json
        {
            "ClassName": "Spur_WonkyTrolley",
            "MaxPriceThreshold": 2000,
            "MinPriceThreshold": 1000,
            "SellPricePercent": -1.0,
            "MaxStockThreshold": 100,
            "MinStockThreshold": 1,
            "QuantityPercent": -1,
            "SpawnAttachments": [],
            "Variants": []
        },
        {
            "ClassName": "Spur_Kart_Seat",
            "MaxPriceThreshold": 750,
            "MinPriceThreshold": 375,
            "SellPricePercent": -1.0,
            "MaxStockThreshold": 100,
            "MinStockThreshold": 1,
            "QuantityPercent": -1,
            "SpawnAttachments": [],
            "Variants": []
        },
        {
            "ClassName": "Spur_Kart_Wheel",
            "MaxPriceThreshold": 250,
            "MinPriceThreshold": 150,
            "SellPricePercent": -1.0,
            "MaxStockThreshold": 100,
            "MinStockThreshold": 1,
            "QuantityPercent": -1,
            "SpawnAttachments": [],
            "Variants": []
        },
        {
            "ClassName": "Spur_Kart_WheelRear",
            "MaxPriceThreshold": 350,
            "MinPriceThreshold": 225,
            "SellPricePercent": -1.0,
            "MaxStockThreshold": 100,
            "MinStockThreshold": 1,
            "QuantityPercent": -1,
            "SpawnAttachments": [],
            "Variants": []
        }
