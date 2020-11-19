# UnitySteer 3.1

<p align="center">
	<img alt="GitHub package.json version" src ="https://img.shields.io/github/package-json/v/Thundernerd/UnitySteer/upm" />
	<a href="https://github.com/Thundernerd/UnitySteer/issues">
		<img alt="GitHub issues" src ="https://img.shields.io/github/issues/Thundernerd/UnitySteer" />
	</a>
	<a href="https://github.com/Thundernerd/UnitySteer/pulls">
		<img alt="GitHub pull requests" src ="https://img.shields.io/github/issues-pr/Thundernerd/UnitySteer" />
	</a>
	<a href="https://github.com/Thundernerd/UnitySteer/blob/upm/LICENSE.md">
		<img alt="GitHub license" src ="https://img.shields.io/github/license/Thundernerd/UnitySteer" />
	</a>
	<img alt="GitHub last commit" src ="https://img.shields.io/github/last-commit/Thundernerd/UnitySteer/upm" />
</p>

## Installation
1. The package is available on the [openupm registry](https://openupm.com). You can install it via [openupm-cli](https://github.com/openupm/openupm-cli).
```
openupm add net.tnrd.unitysteer
```
2. Installing through a [Unity Package](http://package-installer.glitch.me/v1/installer/package.openupm.com/net.tnrd.unitysteer?registry=https://package.openupm.com) created by the [Package Installer Creator](https://package-installer.glitch.me) from [Needle](https://needle.tools)

[<img src="https://img.icons8.com/ios/50/000000/download--v2.png"/>](http://package-installer.glitch.me/v1/installer/package.openupm.com/net.tnrd.unitysteer?registry=https://package.openupm.com)

3. You can also install via git url by adding these entries in your **manifest.json**
```json
"net.tnrd.unitysteer": "https://github.com/Thundernerd/UnitySteer#upm.git"
```

## General notes

UnitySteer is a toolkit to help build steering behaviors for autonomous agents in Unity.  Initially based on OpenSteer, UnitySteer has been significantly reworked since it was first translated - the concepts and some of the code remain the same, but it follows a more Unity-like component-oriented philosophy. 

Please read License.txt before using in your projects.  It's short, sweet and to the point.


## Main repository

If you have obtained this library from a third party, [you can always find the latest version on Github](https://github.com/ricardojmendez/UnitySteer).

## Tutorials and examples

Looking for a UnitySteer tutorial?  The [UnitySteer Examples](https://github.com/ricardojmendez/UnitySteerExamples) repository contains a series of examples and experimentation notes for you to teach yourself the library basics and how to compose your own agents.

## Dependencies

UnitySteer uses [TickedPriorityQueue](https://github.com/Garufortho/TickedPriorityQueue). The latest library is now included on this repository.

UnitySteer 3.1 requires Unity 5.x for 2D support. The last version to support Unity 4.x was [UnitySteer 3.0](https://github.com/ricardojmendez/UnitySteer/tree/v3.0.0).

## Stable and beta versions

The current stable release is UnitySteer 3.0 RC2.  It contains a significant number of improvements and fixes over 2.7, but it also introduced several breaking changes, so make sure you catch up with [the latest UnitySteer blogposts](http://arges-systems.com/blog/category/unitysteer/), as well as reading the [changelog](CHANGELOG.md).

I develop UnitySteer following git-flow, so if you're looking for a specific version, you can look at the project tags:

* [UnitySteer 3.0](https://github.com/ricardojmendez/UnitySteer/tree/v3.0.0)
* [UnitySteer 2.7](https://github.com/ricardojmendez/UnitySteer/tree/v2.7)


## UnitySteer and iOS

If you are using UnitySteer on iOS, bear in mind that you may need to search for and change any LINQ calls, since Unity has a penchant for not AOT'ing them properly.

## Support
**Unity Steer** is originally made by [Ricardo J. Méndez](https://github.com/ricardojmendez) and can be found [here](https://github.com/ricardojmendez/UnitySteer)  

If you're feeling generous and you like my version then you can support **me** here

[![ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/J3J11GEYY)

## Contributing
Pull requests are welcomed. Please feel free to fix any issues you find, or add new features.
