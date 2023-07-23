# Hyprland

![2023-07-21_22-53-17](https://github.com/Aylur/dotfiles/assets/104676705/ffccc68c-9306-4204-a8fd-60c50525558b)

![2023-07-21_22-49-44](https://github.com/Aylur/dotfiles/assets/104676705/bb787657-f86a-4fa9-9d23-4962e8e8530d)

![2023-07-21_22-50-57](https://github.com/Aylur/dotfiles/assets/104676705/9b7a2185-3650-4e55-90ba-ed0fac5dce2c)

# Dependencies
- [ags](https://github.com/Aylur/ags/wiki/installation)
- sassc
- swww
- nerdfonts
- brightnessctl
## optional
- asusctl
- supergfxctl
- hyprpicker
- slurp
- wf-recorder
- watershot
- imagemagick
- wl-gammactl
- pavucontrol

```bash
git clone https://github.com/Aylur/dotfiles.git
cd dotfiles
cp -r .config/ags $HOME/.config/ags
cp -r .config/hypr $HOME/.config/hypr

# you might want to remove asusctl toggle if you are not on an asus laptop
# around line 370
$EDITOR $HOME/.config/ags/layouts/widgets/quicksettings.js

# then run
ags
```
