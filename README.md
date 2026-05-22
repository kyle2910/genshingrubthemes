# Genshin Impact Grub Themes
A pack of GRUB2 themes for Genshin Impact

![banner](/assets/images/banner.jpeg?raw=true)


## Notes:

Hi, I'am Kyle, I found the original project here:  
[https://github.com/voidlhf/StarRailGrubThemes](https://github.com/voidlhf/StarRailGrubThemes)

Since there was no Genshin Impact version, I forked the repository and created this project:  
[https://github.com/kyle2910/GenshinGrubThemes](https://github.com/kyle2910/GenshinGrubThemes)

Please note that the design files are created by the original author, not by me.  
I only used her Figma design and existing theme structure as a base to create the Genshin Impact GRUB theme.

Thanks [voidlhf](https://github.com/voidlhf/)

## Design File & Image Resources
[Honkai: Star Rail Grub Theme Design File (Figma Design File)](https://www.figma.com/community/file/1354356022337074054/honkai-star-rail-grub-theme-design-file)

[StarRailRes (Image Resources)](https://github.com/Mar-7th/StarRailRes)


## Theme Description
> Please access and download the required theme files from the **'Release'** assets of this project.

## Installation
Using the `Kinich` theme as an example

1. Download & Unzip

2. Copy `Kinich` into grub themes directory
```shell
sudo cp -r Kinich /usr/share/grub/themes/
```

3. Edit `grub` file
```shell
sudo nano /etc/default/grub
```

4. Add the theme to the bottom of the text file
```shell
GRUB_THEME="/usr/share/grub/themes/Kinich/theme.txt"
```

5. Update grub
```shell
sudo grub-mkconfig -o /boot/grub/grub.cfg
```

6. Reboot the computer

---

The labels in the bottom right corner of the preview image will not be displayed in the theme file.
