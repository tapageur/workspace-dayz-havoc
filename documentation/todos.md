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
    * Trolley (Electric)
    * Trolley (Gaz)
  * Vehicle_Parts.json
    * Airdrop Flares (10000)
    * Trolley (1250)
    * Trolley Seat (250)
    * Trolley Front Wheel (200)
    * Trolley Rear Wheel (300)
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
