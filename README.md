# dotfiles

My dotfiles

## Quick start

Run the below command in the home directory:

```bash
d=$(mktemp -d) && git clone --depth 1 <REPO_URL> "$d" && rm -rf "$d"/.git "$d"/README* "$d"/LICENSE* && cp -a "$d"/. . && rm -rf "$d"
```

