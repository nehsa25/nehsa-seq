# Nehsa.net Container

This container runs the [Datalust Seq](https://datalust.co/seq) logging server for nehsa.net using the official `datalust/seq:latest` Docker image.

## Overview

This container image is based on the official Datalust Seq Docker image. Seq is a centralized logging server that makes it easy to collect, search, and analyze structured log events. By containerizing Seq, we can ensure consistent deployment and management within our infrastructure.

## Docker Image

The container utilizes the following base image: FROM datalust/seq:latest