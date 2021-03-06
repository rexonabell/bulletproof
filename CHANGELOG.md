# CHANGELOG

### 3.0.0
 - revert back changes added by lordgiotto on v2.0.2 avoid complicating bulletproof
 - add improvements mentioned in issue #62
 - checking if exif_image exists is now done in the constructor instead of in upload() method
 - enable code coverage and quality inspection tool in scrutinizer
 - trying to upload .txt file would throw an error exposing directory path, now only error is displayed
 - code indetations and ps4 autoloader enabled

### 2.0.5
 - Add feature to get the mimetype before calling upload() method

### 2.0.4 
 - fix #60 (JSON throws error due to a forwardslash in error messages)

### 2.0.3
 - git went haywire, 2.0.3 had to be born

### 2.0.2
 - enabled checking for 'exif_imagetype' function.
 - added configurable array messages thanks to github.com/lordgiotto

### 2.0.1
- Removed method `remove()`

### 2.0.0
- Removed watermark, resize, crop functionality
- renamed moaar and added getters and setters
- changed license to MIT 
- added `getJson()` to get image info in json format
- enabled passing of the `$_FILES` array through the class constructor.
- wrote more unit tests
- class uses `\ArrayAccess` for intuitive file submit detection

