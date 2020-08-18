# resume-template
A template to generate your Resume using json and a go template

## Setup
* Fill out your `resume.json`
* Edit `hack/resume.html.tmpl`
* `go run hack/template.go`

## Releasing your resume
* `git tag my-resume-version`
* `git push origin --tags`
* Resume HTML and PDF will be on the releases page

## Badge
[![create-release](https://github.com/kasuboski/resume-template/workflows/create-release/badge.svg)](https://github.com/kasuboski/resume-template/actions?query=workflow%3Acreate-release)

Change the badge links to be your repo

You can see a working version at [kasuboski/resume](https://github.com/kasuboski/resume). That repo also updates a hugo site with the generated files.