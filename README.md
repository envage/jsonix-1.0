## About version

The library is designed to work with documents in JSON format.
The library is distributed under the terms of the FreeWare license with additional restrictions:
- allowed to use in commercial and non-commercial software without any restrictions, but keeping all library files unchanged;
- it is not allowed to make any changes to the source files, static libraries and related files, copy and use the code of the library files;
- distribution of libraries and all public components by sale (partially and completely), as well as outside the distribution methods specified by the owner of the library (website, etc.) is not allowed.

Current library version is *1.0-stripped*.

##  Details

### Version restrictions

- Dynamic (Windows, 32 bit .dll) and shared (Mac/Unix/Linux, x86 .so) libraries only available;
- No source code access available;
- Only old library version available;
- Thread safety support;
- Only JSON decoding, getting the string value of the element and freeing the memory occupied by the document data is allowed;
- There is no support for UTF-16;
- Contains only critical updates;
- There is technical support and joint problem solving;
- Extended functionality excluded;
- No access to private repositories.

## Library Standard Functions 1.0+
- json_decode (char \* string, struct json_t \*\* json)
> *json string to object representation decode function*
- json_select (struct json_t \* json, char \* path, char \*\* output)
> *function to get the string value of a json document element*
- json_delete (struct json_t \*\* json, char \* path, bool cleanup)
> *function to free up memory occupied by json object*
