List of Country Names and Associated Locales
====

Provides various JSON files with links determining what language is spoken in what country based on data from Wikipedia.

Run It
----
You can either use the data already generated (in the /output folder) or pull the repository and run it yourself.

In order to run it on your computer, you'll need Ruby installed. Once you have this, simply call:

	$ ruby parse_locales.rb

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

... a list if of language codes :

	"ak" : {
        "name" : "Akan ",
        "nativeName" : "Akan "
    },
    "sq" : {
        "name" : "Albanian ",
        "nativeName" : "Shqip "
    }

... and various other useful data from Facebook and Wikipedia.

Disclaimer & Contributing
----
Country names have not been written by myself and come - in most cases - from Wikipedia. They are not guaranteed to be 100% politically correct.
If you spot a problem, a typo or a missing country, feel free to open a ticket or do a pull request.
