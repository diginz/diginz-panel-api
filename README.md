# diginz-panel-api
Diginz Panel API

Add Order
Parameters - Description
key	- Your API key
action - add
service - Service ID
link - Link to page
quantity - Needed quantity
runs (optional) - Runs to deliver
interval (optional) - Interval in minutes

<h1>Services List</h1>
<code>[
    {
        "service": 1,
        "name": "Followers",
        "type": "Default",
        "category": "First Category",
        "rate": "0.90",
        "min": "50",
        "max": "10000",
        "refill": true,
        "cancel": true
    },
    {
        "service": 2,
        "name": "Comments",
        "type": "Custom Comments",
        "category": "Second Category",
        "rate": "8",
        "min": "10",
        "max": "1500",
        "refill": false,
        "cancel": true
    }
]
</code>

