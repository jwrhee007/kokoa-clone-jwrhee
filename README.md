# Kokoa Clone

This Github repository serves a purpose of learning HTML and CSS by cloning KokoaTalk, following the course of [Nomad Coders](https://nomadcoders.co/kokoa-clone). 

## Signup Screen part One

First, I will be cloning the signup screen of KokoaTalk, and since this will be the first screen we will be seeing, the file name should be `index.html`. 

On VSCode, you are not required to write all the format essential for HTML file. if you create an HTML file and type in `!`, it will show you an emmet abbrevation. Now press Enter, and it will present you a decent HTML format including head, body, and so on. 

Also, when you try to create class or ID but you are afraid that it may be generic, make it long by using underscore (`_`). For example, in this case, we used `status-bar__column` as class name which uses two underscore. This convention is called BEM (Block Element Modifier). 

## BEM

The purpose of BEM is to make people easier to read and understand HTML and CSS. Also, convention is to use `class` instead of `id`. 

## Font Awesome

We need to add icons for the signup screen. Three icons are needed: Wi-Fi, Battery, and Lightning. There are two options: 

- Find own icons directly or
- Use svg file

There are two websites that may be useful: [Heroicons](https://heroicons.com/) and [FontAwesome](https://fontawesome.com/).

From Heroicons, you search the image you want, copy it and paste it on your code. After that, change the style with CSS. From FontAwesome, you can start free, but unless you pay for it, the feature will be restricted. 

Hopefully code kit is provided by Nomad Coders, but since it did not work, I just created an account and used my source kit. 

Finally, remember, script always goes last. 
