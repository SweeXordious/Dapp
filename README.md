# Dapp

## How this is gonna be ?

### What?
Create a simple decentralized trading platform where people can buy something or sell it, working in the following way:
- Selling:
    - You put what u wanna sell
    - If someone also wants to buy that stuff
    - You receive ether 
    - If not, you gonna leave ur request until someone wants it
- Buying:
    - You check all the offers
    - If you like something
    - You buy it via sending money to that person
    - If you don’t and want something precise
    - You leave your request

### Version1:

Contract:
- Public List of Objects:
    - Each object:
        - Name
        - Description
        - Owner
        - Available : bool
        - ID
        - Price
- Objects count
- Buy_object function (Object ID) :
    - Verify object exist
    - Verify price and amount of money sent
    - Procede with the buying
    - Remove the object from the list  ? How ? 
        - Duplicate its entry by lekhwa ? Does js lets u go over that array and find objects ?
        - Or im gonna use indexes and when an object no longer exists :
            - Either output that its sold
            - Or just skip it
- Add_Object function:
    - Verify all fields are 3amren
    - Verify duplicate objects 
    - Add it to the list
    - Increment objects Count

UI:
- For starters:
    - Have the main page show a list of objects
    - Buy:
        - Have a button “buy”
    - Add:
        - Takes you to page with a form to fill to add the object

### Progress:
0% so far.
### Version2?
- Make it similar to EBay. Post what you want, people will bid on it and then you can sell after sometime.
