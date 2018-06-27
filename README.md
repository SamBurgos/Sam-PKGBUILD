# Sam-PKGBUILD
Collection of all PKGBUILD in Archlinux AUR maintained by myself, as of now the following PKGBUILD scripts are available:

| Package Name             	| Current version 	| Description                                                                                                    	| Check page for out-of-date                                                                                         	| Comments                                                                                                                                                                                             	|
|--------------------------	|-----------------	|----------------------------------------------------------------------------------------------------------------	|--------------------------------------------------------------------------------------------------------------------	|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------	|
| gnome-calendar-linuxmint 	| 3.28.2-2        	| Simple and beautiful calendar application designed to perfectly fit the GNOME desktop. With Linux Mint patches 	| https://www.archlinux.org/packages/extra/x86_64/gnome-calendar/                                                    	| Package gnome-calendar from GNOME upstream with the patches from Linux Mint                                                                                                                          	|
| lightdm-guest            	| 1:1.26.0-1      	| A lightweight display manager. With guest-session enabled                                                      	| https://github.com/CanonicalLtd/lightdm/releases                                                                   	| LightDM package with guest session enabled, as of this moment still researching how this works compared to Linux Mint 19. It also pulls liblightdm-qt5 and liblightdm-qt4 as additional dependencies 	|
| lightdm-settings         	| 1.2.2-1         	| A configuration tool for the LightDM display manager                                                           	| http://packages.linuxmint.com/pool/main/l/lightdm-settings/ https://github.com/linuxmint/lightdm-settings/releases 	| The tool let users configure lightdm-slick-greeter (mainly) but it can also configure certain aspects of LightDM itself                                                                              	|
| lightdm-slick-greeter    	| 1.2.2-1         	| A slick-looking cross-distribution LightDM greeter                                                             	| http://packages.linuxmint.com/pool/main/s/slick-greeter/ https://github.com/linuxmint/slick-greeter/releases       	| Guest session available from package lightdm-guest, which provides the main configuration.                                                                                                           	|
| mintlocale               	| 1.4.7-1         	| Language and locale selection tool                                                                             	| http://packages.linuxmint.com/pool/main/m/mintlocale/https://github.com/linuxmint/mintlocale/releases              	| Co-maintainer with user SunRed, mainly used for changing languages already defined since Locales on Arch are handled differently than Linux Mint                                                     	|
| mint-themes              	| 1.7.1-2         	| A collection of Mint themes. Includes GTK2, GTK3, Cinnamon and Xfce components.                                	| http://packages.linuxmint.com/pool/main/m/mint-themes/                                                             	| This new package merges previous Mint-X-Theme, Mint-Y-Theme and Mint-Cinnamon-Themes                                                                                                                 	|
| mint-x-icons             	| 1.5.0-2         	| A mint/metal theme based on mintified versions of Clearlooks Revamp, Elementary and Faenza                     	| http://packages.linuxmint.com/pool/main/m/mint-x-icons                                                             	|                                                                                                                                                                                                      	|
| mint-y-icons             	| 1.3.0-2         	| A flat, colorful, and modern theme based on Paper and Moka                                                     	| http://packages.linuxmint.com/pool/main/m/mint-y-icons/                                                            	|                                                                                                                                                                                                      	|
| pia-manager              	| 1.0.6-1         	| Easily configure your Private Internet Access VPN                                                              	| http://packages.linuxmint.com/pool/main/p/pia-manager/ https://github.com/linuxmint/pia-manager/releases           	| New updates or features depends on upstream collaboration with PIA                                                                                                                                   	|

## TO-DO
* Documentation inside of the scripts to explain how they work in case I may not want/be able to maintain?
