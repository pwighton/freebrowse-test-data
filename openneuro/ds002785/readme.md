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

[Bookmarklet Test](javascript:(()=>{for(const l of document.links){const h=l.href;if(h.endsWith('.nii.gz')||h.endsWith('.nii')||h.endsWith('.mgz')){l.style.color='#5599dd';l.href='https://freesurfer.github.io/freebrowse/?vol='+encodeURIComponent(h);}else if(h.endsWith('.nvd')){l.style.color='#5599dd';l.href='https://freesurfer.github.io/freebrowse/?nvd='+encodeURIComponent(h);}}})();)


