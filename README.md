# IDM VTON docker

Dockerization of the [Hugging Face Face IDM-VTON Space](https://huggingface.co/spaces/yisol/IDM-VTON)

 * Project page: [Improving Diffusion Models for Authentic Virtual Try-on in the Wild](https://idm-vton.github.io/)
 * Paper: [Improving Diffusion Models for Virtual Try-on](https://arxiv.org/abs/2403.05139)
 * Repository: [IDM-VTON](https://github.com/yisol/IDM-VTON)
 * Model card: [yisol/IDM-VTON](https://huggingface.co/yisol/IDM-VTON)
 * Space: [yisol/IDM-VTON](https://huggingface.co/spaces/yisol/IDM-VTON)

![Xavi barcelona](xavi_barcelona.jpg)
![Xavi real madrid](xavi_real_madrid.png)

## Requisites

[Docker](https://docs.docker.com/desktop/) and [nvidia container toolkit](https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/latest/install-guide.html) must be installed.

## Usage

### Download the image from the Docker Hub

You can download the image and run it

```bash
docker pull maximofn/idm_vton:latest
./run_app.sh
```

### Build the image

Or you can build the image and run it

```bash
./build_docker_image.sh
./run_app.sh
```