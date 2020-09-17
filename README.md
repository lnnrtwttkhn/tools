# Tools

This repo contains my commonly used tools, i.e., containers, code snippets etc.

## Dataset structure

- All inputs (i.e. building blocks from other sources) are located in
  `inputs/`.
- All custom code is located in `code/`.

## Usage

If not stated otherwise, all Singularity containers were created using:

```bash
singularity pull docker://<path_to_docker_container>
```

for example:

```bash
`singularity pull docker://poldracklab/pydeface:37-2e0c2d
```

## Maintainer

- [Lennart Wittkuhn](mailto:wittkuhn@mpib-berlin.mpg.de)
