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

#License

This project is under MIT License, copyright (c) 2010-2014 Marc G Gauthier

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
