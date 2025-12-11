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
