
How is this package create:

```sh
# from: https://cjycode.com/flutter_rust_bridge/quickstart

# 1. Create a new flutter_rust_bridge project
flutter_rust_bridge_codegen create mylib

# 2. take rust_builder and rust, and put rust into same rust_builder

# 3. search ../rust in rust_builder, make sure path is ../rust, not ../../rust or other

# 4. delete other files, create example
```

Rename package name just search all `rust_lib_audio` in rust_builder and replace with `your_package_name`

For Android: Failed to load dynamic library 'librust_lib_my_app.so': dlopen failed: library "librust_lib_my_app.so"

fix: https://cjycode.com/flutter_rust_bridge/manual/troubleshooting

