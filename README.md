## Agreement

The library is designed to work with documents in JSON format.
The library is distributed under the terms of the FreeWare license with additional restrictions:
- allowed to use in commercial and non-commercial software without any restrictions, but keeping all library files unchanged;
- it is not allowed to make any changes to the source files, static libraries and related files, copy and use the code of the library files;
- distribution of libraries and all public components by sale (partially and completely), as well as outside the distribution methods specified by the owner of the library (website, etc.) is not allowed.

Current library version is *1.0-stripped*.

## Version restrictions

- Dynamic (Windows, 32 bit .dll) and shared (Mac/Unix/Linux, x86 .so) libraries only available;
- No source code access available;
- Only old library version available;
- No thread safety support;
- Only JSON decoding, getting the string value of the element and freeing the memory occupied by the document data is allowed;
- There is no support for UTF-16;
- Contains only critical updates;
- There is technical support and joint problem solving;
- Extended functionality excluded;
- No access to private repositories.

## Library Standard Functions 1.0+
								  
- [x] **json_decode**: *json string to object representation decode function*;
- [x] **json_select**: *function for getting the string value of an element at the specified multilevel path*;
- [x] **json_delete**: *function to free up memory occupied by json object*;
- [ ] **json_insert**: *function for creating a new element along the specified multilevel path*;
- [ ] **json_update**: *function of updating an element (value, type, etc.) along the specified multilevel path*;

The format is used to access the element: *\/\<object key name\>\/...\/\{\<array index\>\}\/...*

##  Access to private repository and source code

You can **access private project resources** provided:
- project support (ЕТН: 0xF864B8b8284CbaC48954781548A73F171bE15249);
- compliance with the agreement.
