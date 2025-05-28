# path to nowhere x with the y generator
randomly generate "when you gonna stop w with the x and y with the z?" sentences but for path to nowhere characters.

# basic info
the follow sections will discuss how you can add lines and images

## adding lines 
if you want to add new phrases to the database, add new members to the arrays in the `ptn.json` file.

to demonstrate, i will list the steps for adding the line, "study the humanities with someone who's lost her sanity" as a member to the `secondPart` array of the `ptn.json` file.


1. open the `ptn.json` file
2. locate the `secondPart` array
3. add the line to the `secondPart` array
    - lines use the `phrase` key
    - the line would appear as `{"phrase" : "study the humanities with someone who's lost her sanity"}`
4. add an associated character to the member (optional)
    - characters use the `char` key
    - with a character, the line would appear as `{"phrase" : "study the humanities with someone who's lost her sanity", "char" : "raven"}`
5. save the file
    - ensure that array members and key-value pairs are properly separated using commas

adding new lines to the `firstPart` array works in the same manner.

## adding images
this generator does not have images of all path to nowhere sinners. if you want to add a sinner's image to the generator who does not already have an image in the `img` folder, you will need to add an image yourself. however, adding images is a simple process.

the conditions for images are as follows:
- images must use `.png` extension
- image names must match `char` values

to demonstrate, i will list the steps for adding an image of raven given her `char` value of `raven`.

1. download the desired image as a `.png` file
2. name the image the `char` value
    - the names of the image *must* match the `char` value. if not, the image will not display
    - in this case, the file will appear as `raven.png`
3. move the image into the `img` folder
4. test the image
    - randomize the generator to test if the image appears properly 