# This is a repository which will be used in [`cppkg`](https://github.com/zhanghaoxvan/cppkg) Project

You can create a new Pull Request to add a package in [`cppkg`](https://github.com/zhanghaoxvan/cppkg)

# How to create a package

1. Make a new directory. It will be your main directory.
2. Create a new file `info.json` and write these text:

```json
{
    "name": "Your Package's Name",
    "version": "Your Package's Version",
    "author": "Your Name",
    "description": "Your Description",
    "license": "Your Licence"
}
```

You can modify this JSON text and apply it to your package.

3. Write Code.

> [!IMPORTANT]
> If you wish your package's headers will be used, PUT IT TO YOUR `/path/to/your/package/include` DIRECTORY.
>
> And if you compile a executable in your package, PUT IT TO YOUR `/path/to/your/package/bin` DIRECTORY.

# How to Add a package with create a new Pull Request

1. Clone this repository.
```bash
git clone https://github.com/zhanghaoxvan/cppkg-packages
```
2. Copy your Package to the root directory of `cppkg-packages` and add your Package's name to `cppkg-packages/lists`
```bash
cp -r /path/to/your/package /path/to/cppkg-packages
echo "Your Package Name" >> /path/to/cppkg-packages/lists
```
3. Add a new Pull Request.
