Ozon Plymouth
=========
The Official Plymouth theme for OzonOS.

![initial version screenshot](https://github.com/ozonos/ozon-plymouth/blob/master/preview.png)

### See it in action!
**YouTube** video is available [here](www.github.com).

### Installation

- **Move** 'ozonos-plymouth-theme' to `/lib/plymouth/themes`.

- Open a terminal and **paste**:
```
sudo update-alternatives --install /lib/plymouth/themes/default.plymouth default.plymouth /lib/plymouth/themes/ozonos-plymouth-theme/ozonos-plymouth-theme.plymouth 100
```

- Then **run**:
 
`sudo update-alternatives --config default.plymouth`

And **select OzonOS**.

- Finally **paste**:

`sudo update-initramfs -u`

### License

This project is licensed with GPL version 3 and later. See LICENSE for more details.
