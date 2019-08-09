![](https://www.holded.com/content/assets/media/integration/google-drive/google-drive-logo.png)

## About gdrivedl
An utility to download google drive files with wget from the terminal !

- Website : https://geekofia.in/gdrivedl
- Language : Shell

Coded with ❤ for developers, will help them downloading files uploaded to google drive. They can easily download from terminal in their cloud development server, where on GUI present. Normal linux desktop users may find this helpful !
 
## Installation

Download the latest debian package from this repo [releases](https://github.com/chankruze/gdrivedl/releases) section. Then install it as any normal dpkg installation.

Example:
```
$ sudo dpkg -i gdrivedl_1.0.4_all.deb 
Selecting previously unselected package gdrivedl.
(Reading database ... 246567 files and directories currently installed.)
Preparing to unpack gdrivedl_1.0.4_all.deb ...
Unpacking gdrivedl (1.0.4) ...
Setting up gdrivedl (1.0.4) ...
```

## Usage

- `gdrivedl [-i <FILE_ID>] [-s <FILE_NAME>]`
- Example: `gdrivedl 1xvhbFWetzTf9a1TueWJBcrzzVPycG1dg gdrivedl_demo.txt`

## Instructions
-The `FILE_NAME` argument is the name of the file you want to save as. It can also be a path. For example `/home/user/test/demo.zip`
- The `FILE_ID` argument is the google drive's unique ID for the particular file. This id is alpha numeric and can be found in described cases below:
     1. https://drive.google.com/uc?id=FILE_ID&export=download"
     2. https://drive.google.com/file/d/FILE_ID/view"
     3. https://drive.google.com/open?id=FILE_ID"
     4. https://doc-0o-68-docs.googleusercontent.com/docs/securesc/../../../FILE_ID?e=download"

Report bugs/issues [here](https://github.com/chankruze/gdrivedl/issues)

**screenshot**

![Screenshot](https://res.cloudinary.com/chankruze/image/upload/v1565325563/github/Screenshot_20190809_100733.png)
