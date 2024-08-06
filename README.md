# libboost.a
iOS build for [libboost](https://www.boost.org/)

## Dependencies

    * xcode
    * brew install git


## Build

    ./build-all.sh release

    ./build.sh build release arm64-apple-ios14.0


## Reference in Swift Module

``` swift

    .binaryTarget(
        name: "libboost.a",
        url: "https://github.com/Sitelink-Spatial/libboost.a/releases/download/r3/libboost.a.xcframework.zip",
        checksum: "63671edaa83359490bce2b5580d51631d9cab61a34e6b2ebb2b281f2ead46de6"
    )

```

## References

    * https://www.boost.org/