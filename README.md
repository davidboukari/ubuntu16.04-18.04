# ubuntu16.04-18.04

# Error 

```bash
dpkg -r  libc6-armel-cross
dpkg: un problème de dépendance empêche la suppression de libc6-armel-cross :
 libasan4-armel-cross dépend de libc6-armel-cross (>= 2.27).
 libstdc++6-armel-cross dépend de libc6-armel-cross (>= 2.27).
 libc6-dev-armel-cross dépend de libc6-armel-cross (= 2.23-0ubuntu3cross1).
 libcilkrts5-armel-cross dépend de libc6-armel-cross (>= 2.27).
 libubsan0-armel-cross dépend de libc6-armel-cross (>= 2.27).
 libgcc1-armel-cross dépend de libc6-armel-cross (>= 2.27).
 libgomp1-armel-cross dépend de libc6-armel-cross (>= 2.27).
 libatomic1-armel-cross dépend de libc6-armel-cross (>= 2.27).

dpkg -P --force-depends   libc6-armel-cross libstdc++6-armel-cross libc6-dev-armel-cross libcilkrts5-armel-cross libubsan0-armel-cross libgcc1-armel-cross libgomp1-armel-cross libatomic1-armel-cross
```
