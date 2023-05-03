# akr AUR Update Instructions

## akr
Update `_gittag` in PKGBUILD with latest tag on github  
Run `makepkg` to build - this will also update PKGBUILD with new version numbers  
Run `makepkg --printsrcinfo > .SRCINFO`

## akr-bin
Update `pkgver` in PKGBUILD  
Get latest package + SHA from: https://github.com/akamai/akr-pkg/tree/main/ubuntu  
Run `makepkg --printsrcinfo > .SRCINFO`

## akr-git
> not really required since package is always tracking upstream, but doing this will update version numbers to at least show newer git commit SHA in AUR)

Run `makepkg` to build - this will also update PKGBUILD with new version numbers  
Run `makepkg --printsrcinfo > .SRCINFO`
