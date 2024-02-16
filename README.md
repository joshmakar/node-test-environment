You can use the package as a starting point for building another package or
as a testing environment for another package.

## Usage

Build your package locally and then use `npm link` from within the package
directory. Then use `npm link <package-name>` from within the directory of the
node test environment. Then import the package as you would normally.