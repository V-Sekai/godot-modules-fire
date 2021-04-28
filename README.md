# modules

```
git clone https://github.com/V-Sekai/godot-modules-groups.git --recurse-submodules
git clone https://github.com/V-Sekai/godot -b groups godot-v-sekai --single-branch
cd godot-v-sekai
scons p=windows custom_modules=../godot-modules-groups -j6

# Optional for llvm mingw
scons p=windows custom_modules=../godot-modules-groups -j36 use_llvm=yes use_mingw=yes
```
