# Retail Store Billing System

A desktop application built with Python and Tkinter for managing retail store billing operations.

## Features

- **Product Categories Management**
  - Medical Products
  - Grocery Items
  - Cold Drinks

- **Billing Operations**
  - Generate unique bill numbers
  - Calculate product totals
  - Apply category-specific taxes
  - Save bills as text files
  - Search previous bills

- **Customer Management**
  - Store customer details
  - Track customer purchases
  - Generate customer-specific bills

## Prerequisites

- Python 3.x
- Tkinter (usually comes with Python)

## Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/billing-system.git
```

2. Navigate to project directory
```bash
cd billing-system
```

3. Run the application
```bash
python billing_system.py
```

## Usage

1. **Enter Customer Details**
   - Name
   - Phone Number
   - Bill Number (auto-generated)

2. **Add Products**
   - Select items from different categories
   - Enter quantities
   - Click "Total" to calculate

3. **Generate Bill**
   - Click "Generate Bill" to create bill
   - Bills are automatically saved in 'bills' folder
   - Clear form using "Clear" button

## Price List

### Medical Items
- Sanitizer: Rs. 2/unit
- Mask: Rs. 5/unit
- Hand Gloves: Rs. 12/unit
- Syrup: Rs. 30/unit
- Cream: Rs. 5/unit
- Thermal Gun: Rs. 15/unit

### Grocery Items
- Rice: Rs. 10/unit
- Food Oil: Rs. 10/unit
- Wheat: Rs. 10/unit
- Spices: Rs. 6/unit
- Flour: Rs. 8/unit
- Maggi: Rs. 5/unit

### Cold Drinks
- Sprite: Rs. 10/unit
- Mineral Water: Rs. 10/unit
- Juice: Rs. 10/unit
- Coke: Rs. 10/unit
- Lassi: Rs. 10/unit
- Mountain Duo: Rs. 10/unit

## Tax Rates
- Medical Items: 5%
- Grocery Items: 500%
- Cold Drinks: 10%

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)