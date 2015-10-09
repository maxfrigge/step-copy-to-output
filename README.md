# copy-to-output

Used to filter specific files and directories that aren't needed in the deploy phase.

# Options

* `exclude` (required) Files or directories to exclude

# Example

Exclude git directory

```
- build:
    - steps:
        - copy-to-ouput:
            exclude: .git
```


# License

The MIT License (MIT)

# Changelog

## 0.0.5

- Use $PWD instead of $WERCKER_ROOT

## 0.0.4

- Initial release
