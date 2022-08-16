# Helm Repository

This is the helm repository hosted on GitHub created by hin22001

## Structure

- main branch
  
  All the helm chart source code will be commited to main branch (master branch), all the charts will be placed under `/charts` and each chart will be seperate with their own folder

- gh-pages 

  The `index.yaml` will be commited to this branch, which represent an accessible page. The helm repository required an `index.yaml` file to show its charts struture

## Pipeline

Github action is set to provide helm release automation when changes are commited to the main branch
