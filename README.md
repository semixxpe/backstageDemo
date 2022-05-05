# BACKSTAGE
Manage all your software, all in one place

## Installation
https://backstage.io/docs/getting-started/


## Helpful comands from the installation web
## install the app
npx @backstage/create-app
## cd prompted app name
## Install a Postgres Database and export credentials
export POSTGRES_USER="backstage"
export POSTGRES_PASSWORD="password"
## install dependencies
yarn
yarn install --frozen-lockfile
## tsc outputs type definitions to dist-types/ in the repo root, which are then consumed by the build
yarn tsc
## deploy the app in local
yarn dev

## extra commands
## Build all packages and in the end bundle them all up into the packages/backend/dist folder.
yarn build
## commands together
nvm use 16.13.0 && yarn install && yarn tsc && yarn build

## AWS VPN
https://confluence.alm.europe.cloudcenter.corp/display/SDDEVOPS/AWS+VPN+Client+Installation

## docs about proxy
https://github.com/gajus/global-agent
https://github.com/backstage/backstage/blob/master/contrib/docs/tutorials/help-im-behind-a-corporate-proxy.md

## Templates
### Overview
https://backstage.io/docs/features/software-templates/software-templates-index
### Writing Templates
https://backstage.io/docs/features/software-templates/writing-templates
### Custom fields
https://backstage.io/docs/features/software-templates/writing-custom-field-extensions