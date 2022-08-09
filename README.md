# codewars-I-am-all-alone-poor-me-

## 5 kyu

## I am all alone (poor me)


## Story
POTUS thinks he is all alone in the White House on Christmas Eve.

But is he?

The White House has a wall-penetrating radar security system that sees everything.

## Kata Task
Process the radar image.

Return true if POTUS really is home alone.

```
Legend
# walls
X POTUS
o elves
```

Notes
- The house corners are square only
- The radar can also see into nearby buildings

## Examples

```
   o                o        #######
 ###############             #     #
 #             #        o    #     #
 #  X          ###############     #
 #                                 #
 ###################################
```
All alone --> true

```
#################
#     o         #   o
#          ######        o
####       #                
   #       ###################
   #                         #
   #                  X      #
   ###########################
```
All alone --> false
