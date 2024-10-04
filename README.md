# Audio Generation

## Setup

1. Create the conda environment

```bash
conda env create -f environment.yml
conda activate audiogen
```

2. Configure the development environment variables

- Copy `env.example` to `.env`

```bash
cp .env.example .env
```


- Edit `.env` to set the correct values for the environment variables.

Make sure you don't hardcode anything system-specific in your scripts and notebooks: read them from environment variables instead.


## Ideas

Wavenet paper: https://deepmind.google/discover/blog/wavenet-a-generative-model-for-raw-audio/
