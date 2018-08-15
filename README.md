# Chilli-Bin
 
## Tasks Needed in General

- ~~Install React Native npms~~
- Begin formatting layout based on whiteboard Design
- Functionality will be based on Color Code Scheme
- Mock app to include sample menu
- Research swipe effect Reactjs

## User Flows

Referenced off of design from white board and sample videos.
 
### Landing Page

- User will see QR code, Logo, Menu button, Temperature, and Lock Status
- User will be able to scan QR Code
  - Couriers and Users can scan QR Code
- User will see Temperature of Chilli-Bin
  - Landing Page will display error message if temp is 41 degrees Fahrenheit or above
- User will see if Chilli-Bin is locked via font awesome icon
    - User will be able to unlock after confirming order
- User will be able to select Menu
 
### QR Code is scanned

- User will see media player while lock opens
- Chilli-Bin will validate payment 
- Chilli-Bin will send receipt to User
- Electromagnetic lock will read request
- Electromagnetic lock will release
- Chilli-Bin will register purchased items based on Product ID

### If User Selects 'Menu' (Menu Page)

- User can swipe between Entree, Drink, and Snacks
- User will see price of every item
- User can select Entree, Drink, or Snack with add button
    - User will select the amount of items purchased
    - User can cancel order
    - User can confirm items selected
- User can select 'Finish Order'
- User can go back home

### If User Selects 'Finish Order' (Order Page)

- User will see purchase order
    - Order will be a table listing items selected, price, quantities, and total price
    - The end of the table will calculate sum total and add state tax
- User can confirm order
- User will then be sent to transaction page

### Transaction Page

- User will see instruction to swipe card or scan Apple Pay
- If transaction is complete the Chilli-Bin will unlock and show media player (Unlock Page)
- If transaction is invalid, user can scan again or restart order

### Unlock Page

- Media player will show video of Chilli-Bin partners or stock video
- Chilli-Bin Electromagnetic lock will release
 
---

## Thanks to

The development team of Neighbor Nosh Inc.