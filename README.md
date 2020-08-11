# Knölig val

<img src="./knv.png" alt="" style="width: 300px; margin: 0 auto" />

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

## Super Advanced Usage
Build some dockerfile that is not called `Dockerfile`:
```bash
# in/some/dir/to/project_name
knv build knöligt-dockerfile-name
```
