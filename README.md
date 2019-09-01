# fivem_flag_template
### This is for a copy-paste Template for flags, plus a little tutorial.

Here is a Flag Replacement Template Pack I got ready, with everyflag in including extracted .dds files ready for editing.

There are 2 things you need to edit flags

First is obviously an image editor of your choice capable of editing .dds files. 
  * If you have Photoshop here is a plugin from NVIDIA https://developer.nvidia.com/nvidia-texture-tools-adobe-photoshop
  * If you use GIMP here is there plugin https://code.google.com/archive/p/gimp-dds/
  * Here is another Toolset from NVIDIA https://developer.nvidia.com/legacy-texture-tools


Next you need Texture Toolkit. You can download that on GTA5-MODS https://www.gta5-mods.com/tools/texture-toolkit

Now that you have those downloaded we can begin.

First create a copy of the template and name it what you want. In my case I'll call it Flag_Tutorial

Now open the DDS file of the flag you want to edit in your image editor. I have included a black with the flagpole hooks still attached.

IMAGE HERE

Now create the flag you want using that size dimension, Im not going to do an image editing tutorial. Alternatively paste an image of an existing flag over it. 

IMAGE HERE

Now save it to the flag name that you want to replace AS A DDS. In my case im using prop_flag_us as the name as I am replacing the US flag.

Once saved Open up texture toolkit, load up a flag yft you are replacing (You could replace every flag if you want). There are usually multiple per flag. You do have to do this one at a time. 
For US flag replacement it includes: prop_flag_us prop_flag_us_s prop_flag_usboat prop_flagpole_2b

IMAGE HERE

Go to Edit - import - and choose your dds file you created

IMAGE HERE

Save that. Rinse and repeat till you have replaced all the flags you want.

Delete the flags you didnt replace.

IMAGE HERE

Now move that folder to your server resources, and add the start to your your server.cfg. In my case, start Flag_Tutorial

Start/Restart your server and the flag will be there.

IMAGE HERE

Enjoy! Ill be posting a few other flags today! So stay tuned. You can find me on discord at discord.glassrp.com
