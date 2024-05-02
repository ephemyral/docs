## ephemyral refactor

Utilize an advanced LLM to refactor a give file or all files in a provided directory based on prompts, outputting, building and testing the improved code.

### Synopsis

This command refactors a given file or all files in a directory by sending a prompt to an LLM 
and applying the suggested changes, replacing the file content or creating new files in the specified directory.

```
ephemyral refactor [file path] [prompt] [new file path] [flags]
```

### Options

```
  -h, --help        help for refactor
      --retry int   Number of retries for refactoring files (default 3)
```

### Options inherited from parent commands

```
      --config string   config file (default is $HOME/.ephemyral.yaml)
```

### SEE ALSO

* [ephemyral](ephemyral.md)	 - Ephemyral is an AI-powered CLI application for managing coding tasks that leverage machine learning models.

###### Auto generated by spf13/cobra on 2-May-2024