## SWRT Changelog

============================

#### 5.2.8
* DDNS adds CloudFlare IPv6 support.
* curl enable proxy support.
#### swrt mod:
* RT-AX89X merged with 388.33744.
#### swrt：
* Fixed a memory leak on the SBRAC3200P.
* libletsencrypt add CloudFlare support.

#### 5.2.7
* Update softcenter to latest.
#### swrt mod:
* Add support for tuf-be6500.
* Add support for rt-be86u/rt-be96u/rt-be88u/gt-be98_pro.
#### swrt：
* Backport new features and fixes from 102.54701.
* Fix some bugs.
* Add support for 360T7.
* Fix the problem that abnormal shutdown causes emmc to fail to mount.

#### 5.2.6
#### swrt mod:
* Add support for rt-ax3000n.
* gt-ac5300 merged with 386_51529.
* Fix fix some little bugs.
* Brcm ax models merged with 388_24353.
* Brcm ac models merged with 386_51997.
#### swrt:
* Fix the compatibility issue of old ipq40xx firmware.
* Fix some bugs.

#### 5.2.5

* Update smartdns to latest.
#### swrt mod:
* rt-ax89x/rax120 merged with 388.32407.
* Add support for rax80.
#### swrt:
* Fix qos and firewall errors.
* Fix some mt7621 devices crash issues.
* Backport new features and fixes from 102.22108.
* Add wisp mode support for mtk/qca.
* Add vlan support for mt798x.

#### 5.2.4

* Fix entware installation failure on some devices.
#### swrt mod:
* rt-ax89x/rax120 merged with 386.47468.
* Update 5G phy of rax120.
* Add support for rax120v2.
* Fix fix some little bugs.
#### swrt:
* Fix changing username/password failed.
* Fix httpd crash.
* Add support for sbrac3200p.
* Add support for r7000p.
* Update QSDK12.
* Add support for ipq807x.
* Add support for mt7981.
* Add overclocking/downclocking support for bcm470x.
* Fix mtk firmware upgrade failure when nmbm is disabled.

#### 5.2.3

* Use haveged instead of jitterentropy-rngd.  
#### swrt mod:
* Brcm ax models merged with 388_22525.
* Add support for rt-ax88u_pro.
* Add support for tuf-ax3000_v2.
* Add support for tuf-ax5400_v2.
* Add support for gt6.
* Fix failed to format jffs for HND 5.04 models.
* Fix the network will be disconnected when rebooting aimesh node(The ip of the node is the same as the ip of the gateway).
#### swrt:
* Fix missing samba for rt-acrh17.
* Update mt7915/mt798x driver to latest.
* Add 169-177 channel support for mt7915/mt798x(not all regions).

### 5.2.2
* Fix softcenter cgi.
* Fix entware install script.
* Update softcenter to the lastest version.

### 5.2.1
* Fix the problem that usb enclosures cannot be mounted.
* Add lua.
* Add entware mirror server for chinese.
#### swrt mod:
* Backport httpd ipv6 support for qca models.  
#### swrt:
* Backport 388.31345.
* Optimize usb read and write performance.
* Fix rt-ac85p switch light.
* Add support for bcm470x.

### 5.2.0
* Update softcenter to the lastest version.
#### swrt mod:
* Brcm ac models merged with 386.49xxx.
* Brcm ax models merged with 388_21224.
* Add support for wireguard.
* Fix PPPoE on ipq8074 is not accelerated by hardware NAT.
#### swrt:
* Add mtk bsd.
* Add support for ipq40xx.
* Add support for mt7986.
* Update kernel4.4 for qca.
* Add support for wireguard.
* Fix mt7621 kernel/uboot bad block compatibility.
* Fix rt-ac85p uboot compatible stock firmware.
* Add support for rm-ax6000.

### 5.1.9
* Update softcenter to the lastest version.
#### swrt mod:
* Fix 5g Ethernet port speed setting for rax120.
* Fix bad block problem of rax120.
* Fix softcenter bug for bcm470x models.
* Add port aggregation support for rt-ac86u.
* Porting broadcom fullcone for qca/lantiq.
#### swrt:
* Adjust fonts for Chinese.
* Fix 7615/7915 kvr roaming issues.
* Porting broadcom fullcone.
* Fix guest wifi.

### 5.1.8
* Softcenter support swrt mod and swrt.
#### swrt mod:
* Add Kimetsu no Yaiba skin for rtax82u/rtax86u.
* rtac68u/sbrac1900p/ea6700/r6300v2/dir868l merged with 386.46065.
* rtac3100/rtac5300/rtac88u merged with 386.46065.
* rtac86u/gtac2900 merged with 386.46065.
* rtax56u/rtax58u/rtax82u/rtax68u/rtax86u/rtax88u merged with 386.46065.
* gtax11000/gtaxe11000 merged with 386.46065.
* zenwifi-xt8/tufax5400 merged with 386.46065.
* rtax89x merged with 386.47027.
#### swrt:
* rtac85p/r6800/rmac2100 swrt.
* Update mtk kernel to 4.4.
* Update mt76x3/mt7615/mt7915 drivers.
* Update kvr for mtk.
* Fix softcenter api bug.
* Port ntfs3/apfs drivers.

### 5.1.7

* Add 802.11k/v/r for mt7615.
* Add repeater mode for mtk/ipq4019 series.
* Update smartdns to f50e4dd.
* Improve usb performance.
* Add support of rax70.
* Add support for rt-ax86u(not rt-ax86s), backport 2 broadcom phy drivers and 2 non-broadcom phy drivers.
* rtac85p/r6800/rmac2100 merged with 382.52516.


### 5.1.6

* Add entware and ui for all chip series.
* All Broadcom series support custom txpower.
* Update smartdns to support secondary dns configuration.
* Add support of RAX120/AX89X.
* Add support of R6700v2/R6800/R6900v2.
* Add SX1503 driver.
* All IPQ401x series support overclocking.
* Add fullcone for lantiq/mtk/qca/bcm.
* Fix r7000p wl driver bug.
* ACRH17/AC2200 merged 382.52517.
* SBRAC3200P/AC3200 merged 382.52545.
* BLUECAVE/K3C merged 384.46630.
* RAX120/AX89X merged 386.23012.

### 5.1.5

* Add support of AX82U/R6300V2.
* Unlock the Gundam skin for all AX82U.
* Fix softcenter cgi.
* Add tuxera driver for ac85p.
* Fix hnd series nf_conntrack expectation table full.


