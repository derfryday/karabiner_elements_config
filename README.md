replace `~/.config/karabiner/karabiner.json` with symlink to the same file inside the project
replace `~/.config/karabiner/assets/complex_modifications` with with to the same directory inside the project

from within the project root:
```
rm -rf ~/.config/karabiner/karabiner.json && ln -s "$(pwd)/.config/karabiner/karabiner.json" "/Users/${USER}/.config/karabiner/karabiner.json"
```
```
rm -rf ~/.config/karabiner/assets/complex_modificatons && ln -s "$(pwd)/.config/karabiner/assets/complex_modifications" "/Users/${USER}/.config/karabiner/assets/complex_modifications"
```
