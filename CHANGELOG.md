Change log
-----------

* Include Xbox 360 gamepad driver kernel module [Laurence]

# v2.12.5+rev6
## (2018-04-09)

* Update the resin-yocto-scripts submodule to 6d6f7b29348323569f47c8acbf5963ff64d17647 (on master branch) [Florin]
* Fix boot partition number in the coffee file for skx2 [Florin]

# v2.12.5+rev5
## (2018-03-31)

* Various bug fixes introduced by recent refactoring [Theodor]

# v2.12.5+rev4
## (2018-03-31)

* Fix boot partition number [Theodor]

# v2.12.5+rev3
## (2018-03-30)

* Default root partition to the 12 [Theodor]
* Default enable of spi dev in userspace [Theodor]
* Upgrade to l4t 28.2.0 [Theodor]

# v2.12.5+rev2
## (2018-03-27)

* Update the resin-yocto-scripts submodule to 9cecb1ca4d9d4713dd337148b7d04a17afdba772 (on master branch) [Florin]

# v2.12.5+rev1
## (2018-03-22)

* Update the meta-resin submodule to version v2.12.5 [Florin]
* Update the resin-yocto-scripts submodule to 51b8849e2a02d0d4e729bff24909d9746e0bf4c3 (on master branch) [Florin]

# v2.12.3+rev1
## (2018-03-15)

* Update the meta-resin submodule to version v2.12.3 [Florin]
* Move to rocko [Theodor]

# v2.12.1+rev1
## (2018-03-12)

* Update the meta-resin submodule to version v2.12.1 [Andrei]

# v2.12.0+rev1
## (2018-03-08)

* Update the meta-resin submodule to version v2.12.0 [Theodor]

# v2.11.2+rev1
## (2018-03-08)

* Update the meta-resin submodule to version v2.11.2 [Andrei]

# v2.11.1+rev1
## (2018-03-08)

* Update the meta-resin submodule to version v2.11.1 [Andrei]

# v2.11.0+rev1
## (2018-03-08)

* Update the meta-resin submodule to version v2.11.0 [Theodor]

# v2.10.1+rev1
## (2018-03-01)

* Update the meta-resin submodule to version v2.10.1 [Florin]
* Remove obsolete submodule oe-meta-go [Florin]
* Update the resin-yocto-scripts submodule to dc9dfe466e48d934e55fb20a05156886873b1ab1 (on master branch) [Florin]
* Patch kernel to support Intel RealSense cameras [Theodor]

# v2.9.7+rev4
## 2018-02-21

* Rework the way we generate tegra binaries [Theodor]
* Generate boot0 image so we can correctly configure the partition table [Theodor]

# v2.9.7+rev3
## 2018-02-13

* Fix binary magic [Theodor]

# v2.9.7+rev2
## 2018-01-29

* Fix hostapps-update [Theodor]

# v2.9.7+rev1
## 2018-01-26

* Update rein-yocto-scripts to latest [Theodor]
* Update meta-resin submodule to v2.9.6 [Theodor]

# v2.8.1+rev2
## 2017-12-21

* Change display name Nvidia Jetson TX2 SK -> SKX2 [Theodor]
* Update meta-rust to pyro [Andrei]

# v2.8.1+rev1
## 2017-12-01

* Update meta-resin to include kernel header fix [Theodor]

# v2.7.4+rev2
## 2017-10-27

* Rename skx2 to Nvidia Jetson TX2 SK [Theodor]

# v2.7.4+rev1
## 2017-10-18

* Include cdc_amc and cdc_wdm module for the skx2 [Theodor]
* Various bug fixes [Theodor]

# v2.7.2+rev10 - 2017-10-18

* Fix root kernel parameter for resin-image-flasher [Theodor]
* Update meta-openembedded to latest pyro branch [Will]
* Update poky to latest pyro branch [Will]

# v2.7.2+rev9 - 2017-10-17

* Rename device-type to SKX2 [Theodor]

# v2.7.2+rev8 - 2017-10-17

* Fix name clash between device types [Theodor]

# v2.7.2+rev7 - 2017-10-16

* Add an icon to the SKX2 [Theodor]

# v2.7.2+rev6 - 2017-10-16

* Release SKX2 [Theodor]

# v2.7.2+rev5 - 2017-10-12

* Update resin-yocto-scripts to latest [Theodor]

# v2.7.2+rev4 - 2017-10-12

* Update resin-yocto-scripts to latest [Theodor]

# v2.7.2+rev3 - 2017-10-12

* Support new device type: SKX2 [Theodor]
* Integrate with resin u-boot [Theodor]

# v2.7.2+rev2 - 2017-10-05

* Fix boot partition index [Theodor]

# v2.7.2+rev1 - 2017-10-05

* Update meta-resin submodule to v2.7.2 [Andrei]
* Re-work Nvidia Jetson TX2 to update all internal partitions [Theodor]
* Include meta-rust layer [Will]
* Add meta-rust layer [Will]

# v2.3.0+rev1 - 2017-08-17

* Update the meta-resin submodule to version v2.3.0 [Florin]

# v2.2.0+rev1 - 2017-07-28

* Update the meta-resin submodule to version v2.2.0 [Florin]
* Update the resin-yocto-scripts submodule to HEAD of master [Florin]

# v2.1.0+rev2 - 2017-07-24

* Switch from aufs to overlayfs for the docker storage driver [Florin]

# v2.1.0+rev1 - 2017-07-21

* Update the meta-resin submodule to version v2.1.0 [Florin]
* Update the resin-yocto-scripts submodule to HEAD of master [Florin]
* Fix wireless chip  [Theodor]

# v2.0.8+rev1 - 2017-07-06

* Update the meta-resin submodule to version v2.0.8 [Florin]
* Update the resin-yocto-scripts submodule to HEAD of master [Florin]
* Provide initial support for the Nvidia Jetson TX2 [Theodor]
