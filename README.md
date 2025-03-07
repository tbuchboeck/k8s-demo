# Kubernetes Demo

Showcase project implementing Kubernetes development and deployment workflow and best practice.

## Releasing

    bumpversion major|minor|patch
    git push --push-option=ci.skip origin main
    git push origin $(git describe)

    # end
