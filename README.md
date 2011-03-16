List of Country Names and Associated Locales
====

Provides various JSON files with links determining what language is spoken in what country based on data from Wikipedia.

Output
----
You can find this data in the output folder.

	{"United Kingdom":
		{
			"languages":["English"]
		}
	},
	{"United States":
		{
			"languages":["English","Spanish","Navajo","Carolinian","Chamorro","French","Hawaiian","Samoan"]
		}
	}


It supports ISO country codes and language codes:

	{"FR":
		{
			"languages":["fr","co","br"],
			"name":"France"
		}
	},
	{"GA":
		{
			"languages":["fr"],"name":"Gabon"
		}
	}

It also provides a JSON made for Facebook integration based on the countries and locales supported by Facebook.

Input
----

Find in the input folder various data that you can update if you want to add/remove a locale or country.

It includes a list of country codes:

	{"id":"US","value":"United States"},
	{"id":"CA","value":"Canada"},
	{"id":"GB","value":"United Kingdom"},
	{"id":"AR","value":"Argentina"}

a list if language codes :

	"ak" : {
        "name" : "Akan ",
        "nativeName" : "Akan "
    },
    "sq" : {
        "name" : "Albanian ",
        "nativeName" : "Shqip "
    }

and various other usefull data from Facebook and Wikipedia.