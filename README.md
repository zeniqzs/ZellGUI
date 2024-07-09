# ZellGUI Sell Plugin 💰

Welcome to the ZellGUI Sell Plugin, a powerful tool for selling items directly from your inventory in Minecraft!

## Features 🌟

- **Sell GUI:** Access an intuitive GUI to sell items with ease.
  
- **Dynamic Pricing:** Set prices for each item individually to control the economy on your server.
  
- **Customizable Layout:** Configure the GUI title and number of rows to suit your server's needs.
  
- **Feedback Messages and Sounds:** Informative messages and sounds for successful sales and item restrictions.
  
- **Sell Unlisted Items:** Option to sell items that are not predefined in the configuration.

## Configuration Example 📝

### GUI Configuration

```yaml
GUI:
  Title: "&7Sell GUI"
  Rows: 6

Items:
  NonSellItems: #Items that are not listed up here
    SellAble: true
    Price: 1
  STONE:
    SellAble: true
    Price: 10 #For Each Stone
  DIRT:
    SellAble: true
    Price: 2
  BEDROCK:
    SellAble: false
    Price: 0

  #Add more Items in here

Messages:
  Sold: "&7You sold #0076FF%items% &7Items for &a%amount%."
  Sold-Actionbar: "&a+%amount%"
  CantBeSold: "#FF0000This Item cant be sold!"
  CantBeSold-Actionbar: "#FF0000This Item cant be sold!"


Sounds:
  Sold: ENTITY.LEVELUP
  CantBeSold: VILLIGER.NO
```

# Usage Example

# Opening the Sell GUI:
- Access the Sell GUI by interacting with an NPC or using a specific command.
# Selling Items:
- Click on items in the GUI to sell them instantly at their predefined prices.
# Dynamic Pricing:
- Modify item prices in the configuration to adjust the economy based on server needs.
# Feedback and Notifications:
- Receive visual and auditory feedback for successful sales and attempts to sell restricted items.
