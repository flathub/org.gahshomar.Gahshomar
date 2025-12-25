# Gahshomar

___A Persian/Jalali/Farsi calendar___

Gahshomar makes it easy for you to keep track of two different calendars. 

---

## Manual Install and Run

Make sure you follow the [setup guide for your Linux distribution](https://flathub.org/en/setup) before installing.

```
flatpak install flathub org.gahshomar.Gahshomar
flatpak run org.gahshomar.Gahshomar
```

## Building

```
git clone git@github.com:flathub/org.gahshomar.Gahshomar.git
flatpak run org.flatpak.Builder build-dir --user --ccache --force-clean --install org.gahshomar.Gahshomar.json
```

---

**Technologies**: GNOME, GTK3, Python
