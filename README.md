# cee

**cee** is a Convolutional Neural Network (CNN) for image recognition, written entirely from scratch in C99. 

Before building `cee` ensure you have the following installed on your system:

* `clang` or `gcc` compiler
* `make`
* `VULKAN_SDK` for visualisation 

# build

```bash
git clone https://github.com/superPuero/cee
cd cee
make -f cee/cee.mk release
```

# usage flags

```bash
-h (help)
-preload (load model.bin upfront) 
-lr 0.01 (specify learning rate)
```
