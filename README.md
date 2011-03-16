List of Country Names and Associated Locales
====

Provides various JSON files with links determining what language is spoken in what country based on data from Wikipedia.

Example:

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
