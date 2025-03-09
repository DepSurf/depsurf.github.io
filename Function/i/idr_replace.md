# Function: <code>idr_replace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * idr_replace(struct idr * idp, void * ptr, int id)
```

```json
{
  "name": "idr_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582949024,
      "name": "idr_replace",
      "external": true,
      "loc": "lib/idr.c:793",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_idr_replace",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582949024,
      "name": "idr_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void * idr_replace(struct idr * idp, void * ptr, int id)
```

```json
{
  "name": "idr_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583236736,
      "name": "idr_replace",
      "external": true,
      "loc": "lib/idr.c:793",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_idr_replace",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583236736,
      "name": "idr_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void * idr_replace(struct idr * idp, void * ptr, int id)
```

```json
{
  "name": "idr_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583351984,
      "name": "idr_replace",
      "external": true,
      "loc": "lib/idr.c:793",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_idr_replace",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583351984,
      "name": "idr_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void * idr_replace(struct idr * idr, void * ptr, int id)
```

```json
{
  "name": "idr_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588203408,
      "name": "idr_replace",
      "external": true,
      "loc": "lib/idr.c:151",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_idr_replace",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588203408,
      "name": "idr_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void * idr_replace(struct idr * idr, void * ptr, int id)
```

```json
{
  "name": "idr_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588752464,
      "name": "idr_replace",
      "external": true,
      "loc": "lib/idr.c:152",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/cgroup/cgroup.c:cgroup_idr_replace",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588752464,
      "name": "idr_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void * idr_replace(struct idr * idr, void * ptr, long unsigned int id)
```

```json
{
  "name": "idr_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589130640,
      "name": "idr_replace",
      "external": true,
      "loc": "lib/idr.c:292",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/cgroup/cgroup.c:cgroup_idr_replace",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "security/apparmor/secid.c:aa_secid_update",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_create",
        "net/sched/act_api.c:tcf_idr_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589130640,
      "name": "idr_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void * idr_replace(struct idr * idr, void * ptr, long unsigned int id)
```

```json
{
  "name": "idr_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589365248,
      "name": "idr_replace",
      "external": true,
      "loc": "lib/idr.c:288",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/cgroup/cgroup.c:cgroup_idr_replace",
        "mm/vmscan.c:register_shrinker_prepared",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_create",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "net/sched/act_api.c:tcf_idr_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589365248,
      "name": "idr_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void * idr_replace(struct idr * idr, void * ptr, long unsigned int id)
```

```json
{
  "name": "idr_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589822384,
      "name": "idr_replace",
      "external": true,
      "loc": "lib/idr.c:299",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/cgroup/cgroup.c:cgroup_idr_replace",
        "mm/vmscan.c:register_shrinker_prepared",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "ipc/util.c:ipc_addid",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:alloc_dev",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "net/sched/act_api.c:tcf_idr_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589822384,
      "name": "idr_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void * idr_replace(struct idr * idr, void * ptr, long unsigned int id)
```

```json
{
  "name": "idr_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590048640,
      "name": "idr_replace",
      "external": true,
      "loc": "lib/idr.c:290",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/cgroup/cgroup.c:cgroup_idr_replace",
        "mm/vmscan.c:register_shrinker_prepared",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "ipc/util.c:ipc_addid",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:alloc_dev",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "net/sched/act_api.c:tcf_idr_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590048640,
      "name": "idr_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void * idr_replace(struct idr * idr, void * ptr, long unsigned int id)
```

```json
{
  "name": "idr_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585042592,
      "name": "idr_replace",
      "external": true,
      "loc": "lib/idr.c:290",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/cgroup/cgroup.c:css_create",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "mm/vmscan.c:register_shrinker",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "ipc/util.c:ipc_addid",
        "security/apparmor/secid.c:aa_secid_update",
        "block/genhd.c:del_gendisk",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_add_char_device",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:alloc_dev",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "net/sched/act_api.c:tcf_idr_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585042592,
      "name": "idr_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void * idr_replace(struct idr * idr, void * ptr, long unsigned int id)
```

```json
{
  "name": "idr_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585194320,
      "name": "idr_replace",
      "external": true,
      "loc": "lib/idr.c:290",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/cgroup/cgroup.c:css_create",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "mm/vmscan.c:register_shrinker",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "ipc/util.c:ipc_addid",
        "security/apparmor/secid.c:aa_secid_update",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_add_char_device",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:alloc_dev",
        "net/sched/act_api.c:tcf_idr_insert_many",
        "net/sched/act_api.c:tcf_idr_check_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585194320,
      "name": "idr_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void * idr_replace(struct idr * idr, void * ptr, long unsigned int id)
```

```json
{
  "name": "idr_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585077408,
      "name": "idr_replace",
      "external": true,
      "loc": "lib/idr.c:290",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/cgroup/cgroup.c:css_create",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "ipc/util.c:ipc_addid",
        "security/apparmor/secid.c:aa_secid_update",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:alloc_dev",
        "net/sched/act_api.c:tcf_idr_insert_many",
        "net/sched/act_api.c:tcf_idr_check_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585077408,
      "name": "idr_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void * idr_replace(struct idr * idr, void * ptr, long unsigned int id)
```

```json
{
  "name": "idr_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585524240,
      "name": "idr_replace",
      "external": true,
      "loc": "lib/idr.c:290",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/cgroup/cgroup.c:css_create",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "security/apparmor/secid.c:aa_secid_update",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:alloc_dev",
        "net/sched/act_api.c:tcf_idr_insert_many",
        "net/sched/act_api.c:tcf_idr_check_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585524240,
      "name": "idr_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void * idr_replace(struct idr * idr, void * ptr, long unsigned int id)
```

```json
{
  "name": "idr_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586677424,
      "name": "idr_replace",
      "external": true,
      "loc": "lib/idr.c:290",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/cgroup/cgroup.c:css_create",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:alloc_dev",
        "net/sched/act_api.c:tcf_idr_insert_many",
        "net/sched/act_api.c:tcf_idr_check_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586677424,
      "name": "idr_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void * idr_replace(struct idr * idr, void * ptr, long unsigned int id)
```

```json
{
  "name": "idr_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595757616,
      "name": "idr_replace",
      "external": true,
      "loc": "lib/idr.c:290",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/cgroup/cgroup.c:css_create",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:alloc_dev",
        "net/sched/act_api.c:tcf_idr_insert_many",
        "net/sched/act_api.c:tcf_idr_check_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595757616,
      "name": "idr_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void * idr_replace(struct idr * idr, void * ptr, long unsigned int id)
```

```json
{
  "name": "idr_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596281936,
      "name": "idr_replace",
      "external": true,
      "loc": "lib/idr.c:290",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/cgroup/cgroup.c:css_create",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:alloc_dev",
        "net/sched/act_api.c:tcf_idr_insert_many",
        "net/sched/act_api.c:tcf_idr_check_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596281936,
      "name": "idr_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void * idr_replace(struct idr * idr, void * ptr, long unsigned int id)
```

```json
{
  "name": "idr_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597166640,
      "name": "idr_replace",
      "external": true,
      "loc": "lib/idr.c:290",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/cgroup/cgroup.c:css_create",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/gpu/drm/drm_auth.c:drm_authmagic",
        "drivers/gpu/drm/drm_drv.c:drm_minor_unregister",
        "drivers/gpu/drm/drm_drv.c:drm_minor_register",
        "drivers/gpu/drm/drm_gem.c:drm_gem_handle_delete",
        "drivers/gpu/drm/drm_mode_object.c:drm_mode_object_register",
        "drivers/accel/drm_accel.c:accel_minor_replace",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:alloc_dev",
        "net/sched/act_api.c:tcf_idr_insert_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597166640,
      "name": "idr_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void * idr_replace(struct idr * idr, void * ptr, long unsigned int id)
```

```json
{
  "name": "idr_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503823360,
      "name": "idr_replace",
      "external": true,
      "loc": "lib/idr.c:290",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/cgroup/cgroup.c:cgroup_idr_replace",
        "mm/vmscan.c:register_shrinker_prepared",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "ipc/util.c:ipc_addid",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:alloc_dev",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "net/sched/act_api.c:tcf_idr_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503823360,
      "name": "idr_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void * idr_replace(struct idr * idr, void * ptr, long unsigned int id)
```

```json
{
  "name": "idr_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236444956,
      "name": "idr_replace",
      "external": true,
      "loc": "lib/idr.c:290",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/cgroup/cgroup.c:cgroup_idr_replace",
        "mm/vmscan.c:register_shrinker_prepared",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "ipc/util.c:ipc_addid",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:alloc_dev",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "net/sched/act_api.c:tcf_idr_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236444956,
      "name": "idr_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void * idr_replace(struct idr * idr, void * ptr, long unsigned int id)
```

```json
{
  "name": "idr_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297668512,
      "name": "idr_replace",
      "external": true,
      "loc": "lib/idr.c:290",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/cgroup/cgroup.c:cgroup_idr_replace",
        "mm/vmscan.c:register_shrinker_prepared",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "ipc/util.c:ipc_addid",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:alloc_dev",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "net/sched/act_api.c:tcf_idr_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297668512,
      "name": "idr_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void * idr_replace(struct idr * idr, void * ptr, long unsigned int id)
```

```json
{
  "name": "idr_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279718552,
      "name": "idr_replace",
      "external": true,
      "loc": "lib/idr.c:290",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/cgroup/cgroup.c:cgroup_idr_replace",
        "mm/vmscan.c:register_shrinker_prepared",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "ipc/util.c:ipc_addid",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:alloc_dev",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "net/sched/act_api.c:tcf_idr_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279718552,
      "name": "idr_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void * idr_replace(struct idr * idr, void * ptr, long unsigned int id)
```

```json
{
  "name": "idr_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589650896,
      "name": "idr_replace",
      "external": true,
      "loc": "lib/idr.c:290",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/cgroup/cgroup.c:cgroup_idr_replace",
        "mm/vmscan.c:register_shrinker_prepared",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "ipc/util.c:ipc_addid",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:alloc_dev",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "net/sched/act_api.c:tcf_idr_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589650896,
      "name": "idr_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void * idr_replace(struct idr * idr, void * ptr, long unsigned int id)
```

```json
{
  "name": "idr_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589376704,
      "name": "idr_replace",
      "external": true,
      "loc": "lib/idr.c:290",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/cgroup/cgroup.c:cgroup_idr_replace",
        "mm/vmscan.c:register_shrinker_prepared",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "ipc/util.c:ipc_addid",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:alloc_dev",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "net/sched/act_api.c:tcf_idr_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589376704,
      "name": "idr_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void * idr_replace(struct idr * idr, void * ptr, long unsigned int id)
```

```json
{
  "name": "idr_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590094272,
      "name": "idr_replace",
      "external": true,
      "loc": "lib/idr.c:290",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/cgroup/cgroup.c:cgroup_idr_replace",
        "mm/vmscan.c:register_shrinker_prepared",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "ipc/util.c:ipc_addid",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:alloc_dev",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "net/sched/act_api.c:tcf_idr_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590094272,
      "name": "idr_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void * idr_replace(struct idr * idr, void * ptr, long unsigned int id)
```

```json
{
  "name": "idr_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590144528,
      "name": "idr_replace",
      "external": true,
      "loc": "lib/idr.c:290",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:alloc_pid",
        "kernel/cgroup/cgroup.c:cgroup_idr_replace",
        "mm/vmscan.c:register_shrinker_prepared",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "ipc/util.c:ipc_addid",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:alloc_dev",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "net/sched/act_api.c:tcf_idr_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590144528,
      "name": "idr_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct idr * idr</code>
</li>
<li>
<b>Param removed. </b>
<code>struct idr * idp</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int id</code> ➡️ <code>long unsigned int id</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
