Niivue documents were generated using https://github.com/pwighton/openneuro-crawl

```
mkdir .openneuro-crawl-cache
openneuro-nvd \
  ds002785 \
  --template /home/paul/lcn/git/openneuro-crawl/templates/freesurfer.json \
  --output . \
  --skip-missing \
  --cache-dir ./.openneuro-crawl-cache \
  --verbose \
  --parallel 4
```

Open these NiiVue documents in FreeBrowse:

- [sub-0089.nvd](https://freesurfer.github.io/freebrowse/?nvd=https://raw.githubusercontent.com/pwighton/freebrowse-test-data/refs/heads/main/openneuro/ds002785/sub-0089.nvd)


