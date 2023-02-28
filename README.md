# porfolio_wrapper

Wrapper repo for my personal resume and portfolio site paulfornia.com

WARNING: Updating this repo (portfolio_wrapper) will not automatically update paulfornia.com.

paulfornia.com is linked to https://github.com/pfornia/pfornia.github.io, which matches contents of the _site folder of this repo.

To update the actual site:

1) Compile changes into the _site folder by running (in R):
```rmarkdown::render_site()```

2) Copy (and replace) entire contents of _site/ folder into pfornia.github.io folder (which has origin of https://github.com/pfornia/pfornia.github.io)

3) Add, commit, and push that repo