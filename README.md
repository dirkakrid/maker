maker
=====

Build objects out of amorphous blobs

__NOTE__: this is a fork of [maker-py](https://github.com/objectlabs/maker-py)
          that separates out the maker module and removes pymongo dependencies

example
-------

    from maker import o
    ####################################
    class Person(object):
        first_name = None
        last_name = None
    ####################################


    obj =  o({"_type":"maker_examples.Person",
                       "first_name" : "Abdul",
                       "last_name": "",
                       "kosss": 1})

    print obj

