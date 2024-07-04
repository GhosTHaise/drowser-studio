<p align="center">
  <img
    src="drowser-studio.png"
    alt="Drowser Studio"
    style="width:100%;"
  />
</p>

<p align="center">
  <img
    src="demo.png"
    alt="Demo"
    style="width:100%;"
  />
</p>

![build](https://github.com/kinotio/drowser-studio/workflows/build/badge.svg)
![license](https://img.shields.io/github/license/kinotio/drowser-studio?color=success)
![tags](https://ghcr-badge.egpl.dev/kinotio/drowser-studio/tags?trim=major&color=chocolate)
![latest](https://ghcr-badge.egpl.dev/kinotio/drowser-studio/latest_tag?trim=major&label=latest&color=blueviolet)
![size](https://ghcr-badge.egpl.dev/kinotio/drowser-studio/size?color=blue)

Drowser Studio is a robust and intuitive app designed to help users track, visualize, and analyze the performance of various tests over time. 📈🚀

> This Drowser Studio depend from reports collected from the Drowser Deno Package who is available on Denoland 🦕

You can find the `Drowser` lib from Denoland [here](https://deno.land/x/drowser)

## Usage

Pull directly the Drowser image from the Github Container Registry:

```sh
docker pull ghcr.io/kinotio/drowser-studio:latest
```

And run it

```sh
docker run --name kinotio_drowser_studio -p 3000:3000 -d ghcr.io/kinotio/drowser-studio:latest
```

## Features

### Visualize

We're still working with this feature to get able to visualize the report data 👁️‍🗨️

### Drowser AI

We're still working with this feature to get able to ask the AI to get a prediction and analyse from the test data 🛠️🤖

### Playground

We're still working with this feature to get able to write directly from the platform app instead of using the [Drowser](https://deno.land/x/drowser) Deno lib 🛠️✍🏻

## Build from source

You can use Docker to use it as service inside a container or test it in your local machine
Clone the repository and change directory to be inside of the repository directory and run these commands

Build the Docker image with this command

```sh
docker build -t kinotio/drowser-studio .
```

And, run it with this

```sh
docker run --name kinotio_drowser_studio -p 3000:3000 -d kinotio/drowser-studio
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
