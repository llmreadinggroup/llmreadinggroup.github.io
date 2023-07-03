# LLM Reading Group Notes

Setup:
- Install [Hugo](https://gohugo.io/) a Go-based static site generator.

Building the site:
- `cd site`
- `hugo server --buildDrafts --disableFastRender`
- Go to the port where it is served

Deploying the site:
- Type `hugo` to build the site to serve.
- Run `./deploy.sh` to copy the static site to `./docs/` which is the root of the public version.
- Commit and push to main.
- Deployments can be monitored [here](https://github.com/llmreadinggroup/llmreadinggroup.github.io/actions).
