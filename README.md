# Memeplex LLM

![Flowise screenshot](/docs/img/flowise-screenshot.png)

## Introduction

This is the accompanying code for an upcoming paper that I'm writing. More information coming soon.

## Exemplary Flowise flows

I've included some exemplary Flowise flows in the `flows` folder. You can import them via the Flowise UI.

## Setup Chroma vector database

I followed [this tutorial](https://docs.flowiseai.com/vector-stores/chroma) 1:1. Be sure to have Docker installed. For Mac I highly recommend [OrbStack](https://orbstack.dev) as a Docker client.

## Quirks/bugs

I made everything work via Flowise version `1.3.2` and Node `18.17.1`. There seems to be a bug with the newest version and Node.js 18+, therefore sticking to 1.3.2 as it worked for me on my MacBook.
