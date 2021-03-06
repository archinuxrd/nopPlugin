# **nopPlugin**

# Requirements

**.Net core 2.0 and up [2.1, 2.2, 3.1, 5.0, 6.0, ...]**

**.Net core SDKs 2.1 and up [2.1.xxx, 2.2.xxx, 3.1.xxx, 5.0.xxx, 6.0.xxx, ...]**

**nopCommerce 4.10 and up [4.10, 4.20, 4.30, 4.40, 4.50, ...]**

# How to use the plugin sh file

To make an executable file in linux we run the following command:

`chmod +x filename`

in this case:

`chmod +x plugin`

If the sudo privilege is required, use it.

Located in the nopcommerce folder copy this file (plugin) and run it.

# Steps for create a Plugin

**Step one**
type the followin command for create a new plugin:

`./plugin Group Name 4.40  `

this is according to the nopCommerce version.

example: for nopCommerce 4.30 the dotnet SDK is 3.1 | 
for nopCommerce 4.40 the dotnet SDK is 5.1 and so on

it shows in the next picture

![image](https://user-images.githubusercontent.com/6993888/134070218-7bf85baa-eeb5-4583-80c6-663fdfc6aebe.png)

after runnig the command you will see something like this: 

Arch-Linux

![plugin](https://user-images.githubusercontent.com/6993888/134069458-16e98756-6827-44b7-9c3d-5f6b8f2c28e2.png)

MacOS 11.2.x

![telegram-cloud-photo-size-1-5066744808986487269-y](https://user-images.githubusercontent.com/6993888/134271885-862f86fa-ea17-430b-aae5-d712a07b4baa.jpg)


# Install to use command from anywhere

* Download the latest the latest release.
* Unzip it.
* Copy the file to the /bin/ folder.
* You can type the next command line:

`sudo cp plugin /bin/plugin`

Then you can run the command in terminal like this:

`plugin Group Name`

`plugin Group Name 4.30`

In the last release ver version the nopCommerce version is optional.

Easy way to create a nopCommerce plugin, tested on Arch Linux and Mac OS
