![](.guides/img/22connectactivity.png)
**1) The user chooses a type of beer from the spinner.**
The user clicks on the button to find matching beers.

**2) The layout specifies which method to call in the activity when the button is clicked.**

**3) The method in the activity retrieves the value of the selected beer in the spinner and passes it to the getBrands() method in a Java custom class called BeerExpert.**

**4) BeerExpert’s getBrands() method finds matching brands for the type of beer and returns them to the activity as an ArrayList of Strings.**

**5) The activity gets a reference to the layout text view and sets its text value to the list of matching beers.**
This is displayed on the device.
