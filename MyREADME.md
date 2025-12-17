## Configuration

Branch `main` is configured for ahubers.github.io and localhost. Branch `uiowa` is configured for pushes to UI homepage. 


## To run locally
Checkout `main` and:

```
dc up
```

## To push to UI

Checkout `uiowa` and run `dc up`. Push to branch `uiowa`. Then go to https://fastx.divms.uiowa.edu:3443/auth/ssh/, login, and run:

```
cd ../../homepage/ahubers/
bash update.sh
```


## Code 

`_site` is generated. The stuff you edit is in `_pages`. The templates used by `_pages` are in `_layouts`.
