# jmt_translation
## Translation of Javad Mobile Tools

Javad Mobile Tools uses standard Android text resources in UTF-8 encoding, so for translation you can use any kind of text editor (with UTF-8 support), including notepad.exe
Or use a special translation tool e.g. Android Localizer ( https://www.artfulbits.com/products/free/ailocalizer.aspx )
it is buggy/crashy enough but very simple to use.
 

To test translation - install Javad Mobile Tools to any Android device, navigate to **javad** catalog on the device and add **translation** subfolder. Then copy there the translated data.

The catalog structure will be as follows:

     |-- javad
          |-- translation
          |-- antenna
             |-- res
                |-- values
                |-- values-po
 
          |-- catalog
             |-- res
                |-- values
                |-- values-po

          |-- ...and so on

Next, run JMT and use Settings button on main home screen. There you will see **Language** item on drop-down list - choose it and select your language.