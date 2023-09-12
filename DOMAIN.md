1.
As a member of the public,
So I can order a bagel before work,
I'd like to add a specific type of bagel to my basket.

2.
As a member of the public,
So I can change my order,
I'd like to remove a bagel from my basket.

3.
As a member of the public,
So that I can not overfill my small bagel basket
I'd like to know when my basket is full when I try adding an item beyond my basket capacity.

4.
As a Bob's Bagels manager,
So that I can expand my business,
I�d like to change the capacity of baskets.

5.
As a member of the public
So that I can maintain my sanity
I'd like to know if I try to remove an item that doesn't exist in my basket.

Basket class and BasketTest class

| Classes     | Methods											  | Scenario                     | Outputs			 |
|-------------|---------------------------------------------------|------------------------------|-------------------|
| `Basket`    | `Add(List<String> basket, String bagel)`		  | The basket is not full       | add bagel type    |
|`_capacity=5`|												      | The basket is full           | dont add bagel    |
|			  | `Remove(List<String> basket, String bagel)`	      | If bagel is in basket        | remove            |
|		      |													  | If bagel is not in basket    | does not exist    |
|`_isManager` | `UpdateCapacity(List<String> basket, int newcap)` | If isManager change capacity | new capacity 	 |