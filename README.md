# manifests
Assemble manifests for blendOS (from non-arch distro)

## [Very WIP] Instructions:

  ```
  repo init -u https://github.com/electrikjesus/blendos_manifests.git -b main --git-lfs
  repo sync -c --force-sync 
  python3 -m venv venv
  pip install psutil click
  source venv/bin/activate
  ./assemble init 'https://github.com/electrikjesus/blendos_manifests' 'main'
  ./assemble sync
  source build/envsetup.sh
  breakfast
  brunch
```
## Sources:

https://docs.blendos.co/docs/build-blend/build_environment/
https://docs.blendos.co/docs/build-blend/building_blendos/
