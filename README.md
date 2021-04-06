

## INSTRUCTIONS:

https://stackoverflow.com/questions/25844602/gmp-library-for-ios/60068738#60068738

## LIBRARY:

https://gmplib.org/#DOWNLOAD

brew install lzip

tar -xf gmp-6.2.1.tar.lz

## VARS:

PREFIX:

```
/Users/.../Documents/Maker/Projects/Metal Generative Framework/CGAL/GMP iOS/my path
```

PLATFORM:

iphoneos, macosx, watchos, iphonesimulator, or appletvos

xcrun --sdk iphoneos --show-sdk-path

```
/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS14.4.sdk
```

ARCHITECTURE:

arm64e, arm64, armv7, armv7s, x86_64, i386

```
arm64
```



## CONFIG:

```
./configure CC="/Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -fembed-bitcode -arch arm64 --sysroot=/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS14.4.sdk" CPPFLAGS="-fembed-bitcode -arch arm64 --sysroot=/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS14.4.sdk" --disable-shared --enable-static --host=arm-apple-darwin --disable-assembly --prefix="/Users/.../Documents/Maker/Projects/Metal Generative Framework/CGAL/GMP iOS/my path/GMP_6_1_99/gmp-6.1.99-20200117/gmplib-iphoneos-arm64"

...

checking compiler /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -fembed-bitcode -arch arm64 --sysroot=/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS14.4.sdk -O2 -pedantic -fomit-frame-pointer -fembed-bitcode -arch arm64 --sysroot=/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS14.4.sdk... no
configure: error: could not find a working compiler, see config.log for details

```

