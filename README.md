# VildiaievaFrontEndProHomework30
Дано три массива с объектами:

let kitchenProducts = [
	{
		type: 'grater',
		price: 10
	},
	{
		type: 'pastry-bag',
		price: 25
	},
	{
		type: 'scale',
		price: 5
	},
	{
		type: 'whisk',
		price: 15
	}
];

let devicesProducts = [
	{
		type: 'desktop',
		price: [100,1000]
	},
	{
		type: 'laptop',
		price: [50,1500]
	},
	{
		type: 'smartphone',
		price: [80,2000]
	},
	{
		type: 'tablet',
		price: [20,1300]
	}
];

let cosmeticsProducts = [
	{
		type: 'blush',
		price: 100
	},
	{
		type: 'eyeshadow',
		price: 50
	},
	{
		type: 'lipstick',
		price: 80
	},
	{
		type: 'nail-polish',
		price: 200
	},
	{
		type: 'perfume',
		price: 300,
	}
];
Task:

Create function-construction Product, which have this arguments:  category, type, price and assign it to the object fields with the relevant keys.

Each object, that had been created by function-constructor should be able function render, this function should return string like this:

`<tr>
	<td><img src="images/kitchen/grater.svg" alt="grater" width="50" height="50"></td>
	<td>grater</td>
	<td>10 USD</td>
</tr>`
All products should be created by function-constructor Product and for  and for all we call the method render().

As a result, it is necessary to render a table on the page with output of data  on all products.

Example of product render you can see on products.png

Initial images located in attached archive images.zip