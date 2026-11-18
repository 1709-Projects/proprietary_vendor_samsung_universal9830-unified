Unified proprietary vendor tree for Samsung Exynos 9830
=======================================================

Merged blobs from `TheMuppets/proprietary_vendor_samsung_{universal9830-common,x1s,y2s,z3s,r8s,c1s,c2s}`
(branch `lineage-24.0`).

* `proprietary/` - blobs shared by every variant (default copy)
* `devices/<codename>/proprietary/` - blobs whose path exists on several variants
  with different content; installed under `/vendor/universal9830/<codename>/`
  and bind-mounted over the default at boot by `universal9830-detect`
* `bind/<codename>.txt` - list of bind-mounted paths
