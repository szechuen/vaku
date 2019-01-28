## vaku path delete

Delete a vault path

### Synopsis

Deletes a secret at a specified path. Note that for V2 mounts this only deletes the current version.
Functionally very similar to the 'vault delete' command, but works on v1 and v2 mounts.

Example:
  vaku path delete secret/foo

```
vaku path delete [path] [flags]
```

### Options

```
  -h, --help   help for delete
```

### Options inherited from parent commands

```
  -o, --format string   The output format to use. One of: "json", "text" (default "json")
```

### SEE ALSO

* [vaku path](vaku_path.md)	 - Contains all vaku path functions, does nothing on its own

###### Auto generated by spf13/cobra on 29-Oct-2018