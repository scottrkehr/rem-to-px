####There are three basic parts to this.


###There is a mixin for every property that uses rems

Feel free to add to my list
I currently support the following:
*height
*min-height
*max-height
*width
*min-width
*max-width
*font
*font-size
*line-height
*border
*border-width
*outline
*outline-width
*padding
*padding-top
*padding-bottom
*padding-left
*padding-right
*margin
*margin-top
*margin-bottom
*margin-left
*margin-right
*background
*background-position


###rem-to-px(prop, args)

Each mixin calls the rem-to-px function
This prints out a pixel version, followed by a rem version of the property
prop: the property name
args: the set of arguments being passed to the property


##get-px(args)

This function is called by the rem-to-px function and returns a pixel version of the property if needed, otherwise it returns false.
args: property arguments
