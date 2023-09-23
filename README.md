# .ydf-packages

<img width=95%  src=".media/ydf-packages.png" alt="ydf-packages">

## About

My YDF Packages Directory

## Requirements

You need a `ydf packages` `interpreter`, you can get it from:
<https://github.com/yunielrc/ydf>

## Install

Clone the repository

```sh
cd && git clone https://github.com/yunielrc/.ydf-packages
```

## Configure

Open the repository in your preferred code editor

```sh
code ~/.ydf-packages
```

Copy the `envsubst.env` from the sample and edit it if you need

```sh
cp envsubst.env.sample envsubst.env
```

Modify the the `packages` to fit your needs

Create your `packages selection` files

```sh
touch ~/.ydf-packages/manjaro-work-pc.pkgs
touch ~/.ydf-packages/ubuntu-gaming-pc.pkgs
```

Add packages to your `packages selection` files, one per line,
you can add comments using `#` at the beginning of the line.

Save the `packages directory` on your own git repository

## Usage

Install one package

```sh
ydf package install <package-name>
```

Install all packages from a `packages selection` file

```sh
ydf package install <selection>.pkgs
```
