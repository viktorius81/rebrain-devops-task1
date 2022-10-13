# ![Logo](reactstrap.png) Welcome to online grocery shop project                                                                                                          
**Version 3.0**

***Our project is created help people to find neccessary products they need using our plugin***

**Some information about previous product's versions**

| Version  | Description |
| ------------- | ------------- |
| 1.0  | Initial   |
| 2.0  | Added some functionallity |


## Brief instruction how to install our plugin into known CMS

1. Download plugin from our [website](http://plugin_for_grocerystore.com).
2. Install plugin using coorresponding CMS(for example Joomla).
3. Choose ***plugin section*** in order to set up our module.
4. Enjoy.

##### HERE IS SOME CODE EXAMPLE 
```
def find_duplicate(myList):
    occurrences = []
    for item in myList :
        count = 0
        for x in myList :
            if x == item :
                count += 1
        occurrences.append(count)
        print(occurrences)
    duplicates =[]
    index = 0
    while index < len(myList) :
        if occurrences[index] != 1:
            duplicates.append(myList[index])
        index += 1
    result_list = []
    for k in duplicates:
        if k not in result_list:
            result_list.append(k)
    return result_list
print(find_duplicate(myList))

```

You can donate us:
* BTC
* PayPal
* VISA
* MasterCard

KEEP IN TOUCH WITH US 
> - [Our Telegram Channel](http://t.me/grocery_plugin)
> - [Email](mailto:mail@plugin_for_grocerystore.com)
 
###### © 2022 All rights reserved

