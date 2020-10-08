# Knölig val

<img src="./knv.png" alt="" width="200"/>

```
Knölig Val (knv)

Build and run a docker image built from the
Dockerfile existing in the current directory.

Available commands
  help                      Display this message
  build | build <filename>  Build a Dockerfile. Defaults to "Dockerfile"
                            if no filename is specified
  run                       Run the image built on the Dockerfile in
                            "this" directory
  (no command)              Run both build and run
```

Command line script to easily build and run docker images in your current directory.

## Basic Usage

Navigate to a directory that contains a `Dockerfile`. Run `knv` and an image with the same name as the directory will be built and run.

Build the image called "project_name":

```bash
# in/some/dir/to/project_name
knv build
```

Run the image called "project_name":

```bash
# in/some/dir/to/project_name
knv run
```

Do both of the above.

```bash
# in/some/dir/to/project_name
knv
```

Get help!

```bash
# in/some/dir/to/project_name
knv help
```

## Super Advanced Usage

Build some dockerfile that is not called `Dockerfile`:

```bash
# in/some/dir/to/project_name
knv build knöligt-dockerfile-name
```

## Installation

[`climate`](https://github.com/fippli/climate) is recommended to use to install the script. Install `climate` and run

```
climate install https://github.com/fippli/knv.git
```
