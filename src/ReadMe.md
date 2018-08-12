
*Notes about the mock API*

This mock API allows you to test various order statuses
and scenarios.

Typically we use it when running acceptance tests. 
That is, the app uses this endpoint when tests are running against it.

orders/BT0000001 - This little order is pending
orders/BT0000002 - This order is accepted
orders/BT0000002 - This order is delayed
orders/BT0000002 - This order is cancelled
orders/BT0000003 - This order has one product
orders/BT0000004 - This order has many products
orders/BT0000004 - This order has an estimated completion date
orders/BT0000004 - This order is completed

Group Order
orders/GandT0000001
orders/GandT0000002
orders/GandT0000003


It is built with JSON Server:
https://github.com/typicode/json-server



/*
	‘Pending’ : <AlertCircle fill=“#ffffff” />,
	‘Open’ : <AlertCircle fill=“#ffffff” />,
	‘In Progress’ : <AlertCircle fill=“#ffffff” />,
	‘Cancelled’ : <AlertCircle fill=“#ffffff” />,
	‘Delayed’ : <AlertCircle fill=“#ffffff” />,
	‘Completed’ : <CheckCircle fill=“#ffffff” />
*/
