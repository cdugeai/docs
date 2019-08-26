# Exporting with Resolved References

![Export Modeling File](https://github.com/stoplightio/docs/blob/develop/assets/imagesv2/deref-export.png?raw=true)

## What

By default, Stoplight exports files with references unresolved. References within your spec will appear like this: ```"$ref": "#/foo/bar"```. To resolve these references follow the steps below. 

## How

1. Select the Modeling file you want to modify
2. Click the **right facing arrow** next to the file name to export the file 
   > A new window will appear with your exported file
3. Following the **exported files URL**, input one of the following: 

### Resolve Remote References

Sample URL Deref Remote: ```https://next-api.stoplight.io/files.export?projectId=5242&branch=version%2F1.2&path=PetStore.oas2.yml&deref=remote```

```&deref=remote```

### Resolve References within the File

Sample URL Deref Local: ```https://next-api.stoplight.io/files.export?projectId=5242&branch=version%2F1.2&path=PetStore.oas2.yml&deref=local```

```&deref=local```

### Resolve Both

Sample URL Deref All: ```https://next-api.stoplight.io/files.export?projectId=5242&branch=version%2F1.2&path=PetStore.oas2.yml&deref=all```

```&deref=all```

---
**Related Articles**
- [Read, Design, & Code View](/platform/editor-basics/read-design-code-view)
- [Working with Files](/platform/editor-basics/working-with-files)
- [Import Files](/platform/editor-basics/import-files)
- [Export Files](/platform/editor-basics/export-files)
- [Change History](/platform/editor-basics/change-history)
- [Editor Configuration](/platform/editor-basics/editor-configuration)
- [Environments](/platform/editor-basics/environments)
- [File Validation](/platform/editor-basics/file-validation)



