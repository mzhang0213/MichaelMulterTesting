# MichaelMulterTesting

Working multer setup rn; tweak shiz and use fields and stuff to test :)

Note: input type="hidden" or type="text" are text fields (ie they aren't files) and will AUTOMATICALLY populate req.body AFTER uploads._() has been called<br>
  -see test file for what this looks like<br>
  -do not need to specify the input's 'name'<br>
  -can only access text from a form in the callback ie NOT IN THE MULTER STORAGE CONFIG SECTION
