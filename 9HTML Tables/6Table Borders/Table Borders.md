So far, the tables you've created have been a little difficult to read because they have no borders.

In older versions of HTML, a border could be added to a table using the border attribute and setting it equal to an integer. This integer would represent the thickness of the border.

<table border="1">
  <tr>
    <td>73</td>
    <td>81</td>
  </tr>
</table>
The code in the example above is following is deprecated, so please don't use it. It's meant to illustrate older conventions you may come across when reading other developers' code.

The browser will likely still interpret your code correct if you use the border attribute, but that doesn't mean the attribute should be used. Instead, you can achieve the same effect using CSS.

table, td {
  border: 1px solid black;
}
The code in the example above uses CSS instead of HTML to show table borders.

Instructions:

We're going to need some more data in the table. Add the following data to the table. Make sure to place it after the second table row.

<tr>
  <td>Davie's Burgers</td>
  <td>2</td>
  <td>Send Invoice</td>
</tr>
<tr>
  <td>Baker's Bike Shop</td>
  <td>3</td>
  <td>Send Invoice</td>
</tr>
<tr>
  <td>Miss Sally's Southern</td>
  <td>4</td>
  <td>Ship</td>
</tr>
<tr>
  <td>Summit Resort Rentals</td>
  <td>4</td>
  <td>Ship</td>
</tr>
<tr>
  <td>Strike Fitness</td>
  <td>1</td>
  <td>Enter Order</td>
</tr>
