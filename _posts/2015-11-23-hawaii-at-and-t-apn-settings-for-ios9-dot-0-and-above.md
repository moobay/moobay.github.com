---
layout: post
title: "Hawaii AT&amp;T APN settings for iOS9.0 and above"
date: 2015-11-23 17:15:56 +0800
categories: 
---

<a href='/assets/code/AT%26T.mobileconfig'>Hawaii AT&T</a>
<!--more-->

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>ConsentText</key>
	<dict/>
	<key>PayloadContent</key>
	<array>
		<dict>
			<key>AttachAPN</key>
			<dict>
				<key>AuthenticationType</key>
				<string>CHAP</string>
				<key>Name</key>
				<string>phone</string>
			</dict>
			<key>PayloadDescription</key>
			<string>Configures a custom APN.</string>
			<key>PayloadDisplayName</key>
			<string>Cellular</string>
			<key>PayloadIdentifier</key>
			<string>com.apple.cellular.4F7961F1-FF50-492E-B9FE-202D40EEF4A7</string>
			<key>PayloadType</key>
			<string>com.apple.cellular</string>
			<key>PayloadUUID</key>
			<string>4F7961F1-FF50-492E-B9FE-202D40EEF4A7</string>
			<key>PayloadVersion</key>
			<real>1</real>
		</dict>
	</array>
	<key>PayloadDescription</key>
	<string>由于iOS9.0以上版本操作系统不支持淘宝提供APN配置，已升级新系统的手机请安装此APN配置 BY:LARRYHOU

CHAP vs PAP
http://www.tldp.org/LDP/nag/node120.html</string>
	<key>PayloadDisplayName</key>
	<string>Hawaii AT&amp;T</string>
	<key>PayloadIdentifier</key>
	<string>larryhou-rmbp.local.AB6EADAA-144C-467E-A032-98560538DA78</string>
	<key>PayloadOrganization</key>
	<string>larryhou</string>
	<key>PayloadRemovalDisallowed</key>
	<false/>
	<key>PayloadType</key>
	<string>Configuration</string>
	<key>PayloadUUID</key>
	<string>D5FDEFC4-CC28-478E-A40F-EC0E89C28091</string>
	<key>PayloadVersion</key>
	<integer>1</integer>
</dict>
</plist>

```

<a href='/assets/code/AT%26T-2.mobileconfig'>Hawaii AT&T v2</a>