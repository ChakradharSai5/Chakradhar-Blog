Watch the acompanying [video](https://youtu.be/JC1E-jeiWhI) to understand how to use these scripts.

![image](https://i.ytimg.com/vi/JC1E-jeiWhI/maxresdefault.jpg)

Note that Obsidian Publish only supports the use of the `publish.js` script if you are publishing to a custom domain. However, this should not be an issue. You are able to secure a cheap domain name for as low as $1 per annum and make the necessary configurations for Obsdiian in Cloudflare for free.
- Here's the [link](https://help.obsidian.md/Obsidian+Publish/Set+up+a+custom+domain) to the Obsidian guide about setting up a custom domain - making the necessary configuration changes in Cloudflare
- I prefer [Namecheap](https://www.namecheap.com/) for purchasing domain names, but likely any other service provider will do just as well.

Step by step:
- Copy the `publish.js` and `publish.css` files to the root folder of your vault.
- In Excalidraw Plugin Settings set up "Auto-export SVG":
![image](https://user-images.githubusercontent.com/14358394/282298312-9cb2c327-91ff-4c49-a4ce-82cabe52bcbd.png)
![image](https://user-images.githubusercontent.com/14358394/282298341-962c92ab-705b-4e0e-8e0c-073662000da3.png)
- Optionally, after setting up Auto-Export you can also set up the "Type of file to insert into the document" to SVG. Note, SVG will only be avialable as an option, if you first enable Auto-export in the previous step.
![image](https://user-images.githubusercontent.com/14358394/282298500-eb5ea846-ed7a-49ac-a6df-165fecb6d313.png)
- When publishing your site you can use the `Excalidraw: Obsidian Publish: Find SVG and PNG exports that are out of date` Command Palette action to check that all your image exports are up to date. Images may get out of date if you've changed embedded content or links.

The `publish.js` and `publish.css` files are MVP solutions. I welcome responses to this Gist showcasing enhanced versions of these scripts.

Good Luck and Enjoy!