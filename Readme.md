### JSON-SERVER

- Install 
```
npm install -g json-server
```

- Run Mock Service
```
json-server --watch customer.json
```

- get list cutomer 
```
method : get 
url : http://localhost:3000/customers/

response 
[
	{
		"id": 1,
		"username": "adi",
		"firstname": "adi",
		"lastname": "",
		"email": "adi@emeriocorp.com",
		"address": "alamat rumah adi",
		"dateofbirth": 1522901343123,
		"customerimage": null
	},
	{
		"id": 2,
		"username": "mufti",
		"firstname": "mufti",
		"lastname": "",
		"email": "mufti@emeriocorp.com",
		"address": "alamat rumah mufti",
		"dateofbirth": 1522901343184,
		"customerimage": null
	},
	{
		"id": 3,
		"username": "raka",
		"firstname": "raka",
		"lastname": "",
		"email": "raka@emeriocorp.com",
		"address": "alamat rumah raka",
		"dateofbirth": 1522901343186,
		"customerimage": null
	},
	{
		"id": 4,
		"username": "yuke",
		"firstname": "yuke",
		"lastname": "",
		"email": "yuke@emeriocorp.com",
		"address": "alamat rumah yuke",
		"dateofbirth": 1522901343188,
		"customerimage": null
	},
	{
		"id": 5,
		"username": "sam",
		"firstname": "sam",
		"lastname": "",
		"email": "sam@emeriocorp.com",
		"address": "alamat rumah sam",
		"dateofbirth": 1522901343191,
		"customerimage": null
	},
	{
		"id": 6,
		"username": "andre",
		"firstname": "andre",
		"lastname": "",
		"email": "andre@emeriocorp.com",
		"address": "alamat rumah andre",
		"dateofbirth": 1522901343193,
		"customerimage": null
	}
]
```

- get 1 customer 
```
method : get 
url : http://localhost:3000/customers/{id}

response 
{
	"id": 1,
	"username": "adi",
	"firstname": "adi",
	"lastname": "",
	"email": "adi@emeriocorp.com",
	"address": "alamat rumah adi",
	"dateofbirth": 1522901343123,
	"customerimage": null
}
```

- create new customer 
```
method : post 
url : http://localhost:3000/customers/
request body :
{
	"id": 7,
	"username": "budi",
	"firstname": "budi",
	"lastname": "",
	"email": "budi@emeriocorp.com",
	"address": "alamat rumah budi",
	"dateofbirth": 1522901343123,
	"customerimage": null
}
```

- update customer
```
method : put
url : http://localhost:3000/customers/{id}
request body :
{
	"id": 7,
	"username": "andi",
	"firstname": "andi",
	"lastname": "",
	"email": "andi@emeriocorp.com",
	"address": "alamat rumah andi",
	"dateofbirth": 1522901343123,
	"customerimage": null
}
```

- delete customer
```
method : delete
url : http://localhost:3000/customers/{id}
```