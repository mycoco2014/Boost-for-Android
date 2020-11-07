#### 手动下载

```
wget https://dl.bintray.com/boostorg/release/1.74.0/source/boost_1_74_0.tar.gz
```

#### 设置参数

> 在当前目录下载1.74.0,且解压缩目录名为 boost_1_74_0_android

```
./build-android-v1.sh --arch=armeabi-v7a,arm64-v8a --boost=1.74.0 --with-boost-root=boost_1_74_0_android /Users/xxxxx/Library/Android/sdk/ndk/20.0.5594570
```

