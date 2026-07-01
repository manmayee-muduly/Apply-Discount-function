# Apply-Discount-function
the main goal is to built a discount function using the python basic  default functions and return the total price after the deduction of discounted price .
<br>
def apply_discount(price, discount):

    if not isinstance(price, (int, float)):
        return "The price should be a number"

    if not isinstance(discount, (int, float))
        return "The discount should be a number"

    # Price must be greater than 0
    if price <= 0:
        return "The price should be greater than 0"

    # Discount must be between 0 and 100
    if discount < 0 or discount > 100:
        return "The discount should be between 0 and 100"

    # Return discounted price
    return price - (price * discount / 100)    
    
