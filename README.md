# fluxcd-example-2024-12-02

## Setup

```bash
export GITLAB_TOKEN=1oP9695k71pm6mg2MEyg

flux bootstrap gitlab \
  --deploy-token-auth \
  --owner=ondrejsika \
  --repository=fluxcd-example-2024-12-02 \
  --branch=master \
  --hostname=gitlab.sikademo.com \
  --path=clusters/us \
  --personal
```
