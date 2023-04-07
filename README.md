# HOSTGIER

When adding a new version to an existing image, such as `java v42`, you'd add it within a child folder of `java`, so
`java/42/Dockerfile` for example. Please also update the correct `.github/workflows` file to ensure that this new version
is tagged correctly.

## Available Images

* [`base oses`](https://github.com/HostGierPL/yolks/tree/master/oses)
  * [`alpine`](https://github.com/HostGierPL/yolks/tree/master/oses/alpine)
    * `ghcr.io/hostgierpl/yolks:alpine`
  * [`debian`](https://github.com/HostGierPL/yolks/tree/master/oses/debian)
    * `ghcr.io/hostgierpl/yolks:debian`
* [`games`](https://github.com/HostGierPL/yolks/tree/master/games)
  * [`rust`](https://github.com/HostGierPL/yolks/tree/master/games/rust)
    * `ghcr.io/hostgierpl/games:rust`
  * [`source`](https://github.com/HostGierPL/yolks/tree/master/games/source)
    * `ghcr.io/hostgierpl/games:source`
* [`golang`](https://github.com/HostGierPL/yolks/tree/master/go)
  * [`go1.14`](https://github.com/HostGierPL/yolks/tree/master/go/1.14)
    * `ghcr.io/hostgierpl/yolks:go_1.14`
  * [`go1.15`](https://github.com/HostGierPL/yolks/tree/master/go/1.15)
    * `ghcr.io/hostgierpl/yolks:go_1.15`
  * [`go1.16`](https://github.com/HostGierPL/yolks/tree/master/go/1.16)
    * `ghcr.io/hostgierpl/yolks:go_1.16`
  * [`go1.17`](https://github.com/HostGierPL/yolks/tree/master/go/1.17)
    * `ghcr.io/hostgierpl/yolks:go_1.17`
* [`java`](https://github.com/HostGierPL/yolks/tree/master/java)
  * [`java8`](https://github.com/HostGierPL/yolks/tree/master/java/8)
    * `ghcr.io/hostgierpl/yolks:java_8`
  * [`java8 - OpenJ9`](https://github.com/HostGierPL/yolks/tree/master/java/8j9)
    * `ghcr.io/hostgierpl/yolks:java_8j9`
  * [`java11`](https://github.com/HostGierPL/yolks/tree/master/java/11)
    * `ghcr.io/hostgierpl/yolks:java_11`
  * [`java11 - OpenJ9`](https://github.com/HostGierPL/yolks/tree/master/java/11j9)
    * `ghcr.io/hostgierpl/yolks:java_11j9`
  * [`java16`](https://github.com/HostGierPL/yolks/tree/master/java/16)
    * `ghcr.io/hostgierpl/yolks:java_16`
  * [`java16 - OpenJ9`](https://github.com/HostGierPL/yolks/tree/master/java/16j9)
    * `ghcr.io/hostgierpl/yolks:java_16j9`
  * [`java17`](https://github.com/HostGierPL/yolks/tree/master/java/17)
    * `ghcr.io/hostgierpl/yolks:java_17`
  * [`java17 - OpenJ9`](https://github.com/HostGierPL/yolks/tree/master/java/17j9)
    * `ghcr.io/hostgierpl/yolks:java_17j9`
  * [`java18`](https://github.com/HostGierPL/yolks/tree/master/java/18)
    * `ghcr.io/hostgierpl/yolks:java_18`
  * [`java18 - OpenJ9`](https://github.com/HostGierPL/yolks/tree/master/java/18j9)
    * `ghcr.io/hostgierpl/yolks:java_18j9`
* [`nodejs`](https://github.com/HostGierPL/yolks/tree/master/nodejs)
  * [`node12`](https://github.com/HostGierPL/yolks/tree/master/nodejs/12)
    * `ghcr.io/hostgierpl/yolks:nodejs_12`
  * [`node14`](https://github.com/HostGierPL/yolks/tree/master/nodejs/14)
    * `ghcr.io/hostgierpl/yolks:nodejs_14`
  * [`node15`](https://github.com/HostGierPL/yolks/tree/master/nodejs/15)
    * `ghcr.io/hostgierpl/yolks:nodejs_15`
  * [`node16`](https://github.com/HostGierPL/yolks/tree/master/nodejs/16)
    * `ghcr.io/hostgierpl/yolks:nodejs_16`
  * [`node17`](https://github.com/HostGierPL/yolks/tree/master/nodejs/17)
    * `ghcr.io/hostgierpl/yolks:nodejs_17`
  * [`node18`](https://github.com/HostGierPL/yolks/tree/master/nodejs/18)
    * `ghcr.io/hostgierpl/yolks:nodejs_18`
* [`python`](https://github.com/HostGierPL/yolks/tree/master/python)
  * [`python3.7`](https://github.com/HostGierPL/yolks/tree/master/python/3.7)
    * `ghcr.io/hostgierpl/yolks:python_3.7`
  * [`python3.8`](https://github.com/HostGierPL/yolks/tree/master/python/3.8)
    * `ghcr.io/hostgierpl/yolks:python_3.8`
  * [`python3.9`](https://github.com/HostGierPL/yolks/tree/master/python/3.9)
    * `ghcr.io/hostgierpl/yolks:python_3.9`
  * [`python3.10`](https://github.com/HostGierPL/yolks/tree/master/python/3.10)
    * `ghcr.io/hostgierpl/yolks:python_3.10`

### Installation Images

* [`alpine-install`](https://github.com/HostGierPL/yolks/tree/master/installers/alpine)
  * `ghcr.io/hostgierpl/installers:alpine`

* [`debian-install`](https://github.com/HostGierPL/yolks/tree/master/installers/debian)
  * `ghcr.io/hostgierpl/installers:debian`
