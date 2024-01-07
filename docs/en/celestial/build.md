# Building Celestial

## Preparation

You need to install the following software (if you just want to build):
- [git](https://git-scm.com)
- JDK 17

If you want to develop, you also need to install:
- [IntelliJ IDEA](https://www.jetbrains.com/idea)

## Getting Started

> Make sure to complete the [preparation](#preparation) first.

1. Open your shell
2. Clone the repository -> `git clone https://github.com/CubeWhyMC/celestial`
3. Change directory -> `cd celestial` (On Windows, you may need to add the /d parameter)
4. Build -> `gradlew clean build` (If you encounter network errors, please refer to [this](https://cn.bing.com/search?q=gradle%E8%AE%BE%E7%BD%AE%E5%8A%A0%E9%80%9F%E6%BA%90))

You can find the generated artifacts in the build/libs directory.