# Glace
**One Library to Rule Them All ⚡**

> [!NOTE]
> The library is under active development and the API is a subject to change.

Glace is a GObject library to manage Wayland clients and retrieve information about them, it also simplifies the setup of docks and desktop widgets!

---
## Requirements
Below is a list of dependencies needed to build and install Glace:

```
gtk+-3.0
gobject-2.0
gdk-wayland-3.0
wayland-client
```
Additionally, you will need a Wayland compositor that supports the `zwlr-foreign-toplevel-management` protocol. Compositors based on wlroots already support this protocol.

---
### Arch Linux 

From the AUR using your favorite AUR helper

```
yay -S glace-git
```

Or alternatively you can manually build Gray and install it

To build and install Glace, run the following command after cloning the repository:

```
meson setup build -Dbuildtype=release --wipe && sudo ninja -C build install
```

---
After installing Glace, you can head over to examples located in the `/examples` directory and try them out.
