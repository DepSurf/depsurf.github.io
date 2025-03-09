# Function: <code>name_to_dev_t</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
dev_t name_to_dev_t(const char * name)
```

```json
{
  "name": "name_to_dev_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578854064,
      "name": "name_to_dev_t",
      "external": true,
      "loc": "init/do_mounts.c:210",
      "file": "init/do_mounts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts_md.c:md_setup_drive",
        "kernel/power/hibernate.c:resume_store",
        "drivers/md/dm-table.c:dm_get_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578854064,
      "name": "name_to_dev_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1109
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
dev_t name_to_dev_t(const char * name)
```

```json
{
  "name": "name_to_dev_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578854160,
      "name": "name_to_dev_t",
      "external": true,
      "loc": "init/do_mounts.c:210",
      "file": "init/do_mounts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts_md.c:md_setup_drive",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578854160,
      "name": "name_to_dev_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1114
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
dev_t name_to_dev_t(const char * name)
```

```json
{
  "name": "name_to_dev_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578854192,
      "name": "name_to_dev_t",
      "external": true,
      "loc": "init/do_mounts.c:210",
      "file": "init/do_mounts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts_md.c:md_setup_drive",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578854192,
      "name": "name_to_dev_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
dev_t name_to_dev_t(const char * name)
```

```json
{
  "name": "name_to_dev_t",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578854240,
      "name": "name_to_dev_t",
      "external": true,
      "loc": "init/do_mounts.c:210",
      "file": "init/do_mounts.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts_md.c:md_setup_drive",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578854240,
      "name": "name_to_dev_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1088
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
dev_t name_to_dev_t(const char * name)
```

```json
{
  "name": "name_to_dev_t",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578854288,
      "name": "name_to_dev_t",
      "external": true,
      "loc": "init/do_mounts.c:210",
      "file": "init/do_mounts.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts_md.c:md_setup_drive",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578854288,
      "name": "name_to_dev_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1088
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
dev_t name_to_dev_t(const char * name)
```

```json
{
  "name": "name_to_dev_t",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "name_to_dev_t",
      "external": true,
      "loc": "init/do_mounts.c:210",
      "file": "init/do_mounts.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts_md.c:md_setup_drive",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578857159,
      "name": "name_to_dev_t.cold.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071578856096,
      "name": "name_to_dev_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1063
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
dev_t name_to_dev_t(const char * name)
```

```json
{
  "name": "name_to_dev_t",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578856274,
      "name": "name_to_dev_t",
      "external": true,
      "loc": "init/do_mounts.c:221",
      "file": "init/do_mounts.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts_md.c:md_setup_drive",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578857300,
      "name": "name_to_dev_t.cold.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071578856176,
      "name": "name_to_dev_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
dev_t name_to_dev_t(const char * name)
```

```json
{
  "name": "name_to_dev_t",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578856563,
      "name": "name_to_dev_t",
      "external": true,
      "loc": "init/do_mounts.c:222",
      "file": "init/do_mounts.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts_md.c:md_setup_drive",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578857601,
      "name": "name_to_dev_t.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071578856464,
      "name": "name_to_dev_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
dev_t name_to_dev_t(const char * name)
```

```json
{
  "name": "name_to_dev_t",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578856547,
      "name": "name_to_dev_t",
      "external": true,
      "loc": "init/do_mounts.c:222",
      "file": "init/do_mounts.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts_md.c:md_setup_drive",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578857585,
      "name": "name_to_dev_t.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071578856448,
      "name": "name_to_dev_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
dev_t name_to_dev_t(const char * name)
```

```json
{
  "name": "name_to_dev_t",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578861152,
      "name": "name_to_dev_t",
      "external": true,
      "loc": "init/do_mounts.c:223",
      "file": "init/do_mounts.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts_md.c:md_setup_drive",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "drivers/md/dm-table.c:dm_get_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578861152,
      "name": "name_to_dev_t.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 854
    },
    {
      "addr": 18446744071578862016,
      "name": "name_to_dev_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
dev_t name_to_dev_t(const char * name)
```

```json
{
  "name": "name_to_dev_t",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578861344,
      "name": "name_to_dev_t",
      "external": true,
      "loc": "init/do_mounts.c:284",
      "file": "init/do_mounts.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:prepare_namespace",
        "kernel/power/hibernate.c:resume_store",
        "drivers/md/md-autodetect.c:md_setup_drive",
        "drivers/md/dm-table.c:dm_get_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578861344,
      "name": "name_to_dev_t.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446744071578861536,
      "name": "name_to_dev_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
dev_t name_to_dev_t(const char * name)
```

```json
{
  "name": "name_to_dev_t",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578861088,
      "name": "name_to_dev_t",
      "external": true,
      "loc": "init/do_mounts.c:284",
      "file": "init/do_mounts.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:prepare_namespace",
        "kernel/power/hibernate.c:resume_store",
        "drivers/md/md-autodetect.c:md_setup_drive",
        "drivers/md/dm-table.c:dm_get_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578861088,
      "name": "name_to_dev_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 498
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
dev_t name_to_dev_t(const char * name)
```

```json
{
  "name": "name_to_dev_t",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578861168,
      "name": "name_to_dev_t",
      "external": true,
      "loc": "init/do_mounts.c:278",
      "file": "init/do_mounts.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:prepare_namespace",
        "kernel/power/hibernate.c:resume_store",
        "drivers/md/md-autodetect.c:md_setup_drive",
        "drivers/md/dm-table.c:dm_get_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578861168,
      "name": "name_to_dev_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 498
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
dev_t name_to_dev_t(const char * name)
```

```json
{
  "name": "name_to_dev_t",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578852176,
      "name": "name_to_dev_t",
      "external": true,
      "loc": "init/do_mounts.c:277",
      "file": "init/do_mounts.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:prepare_namespace",
        "kernel/power/hibernate.c:resume_store",
        "drivers/md/md-autodetect.c:md_setup_drive",
        "drivers/md/dm-table.c:dm_get_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578852176,
      "name": "name_to_dev_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 549
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
dev_t name_to_dev_t(const char * name)
```

```json
{
  "name": "name_to_dev_t",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578853936,
      "name": "name_to_dev_t",
      "external": true,
      "loc": "init/do_mounts.c:277",
      "file": "init/do_mounts.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:prepare_namespace",
        "kernel/power/hibernate.c:resume_store",
        "drivers/md/md-autodetect.c:md_setup_drive",
        "drivers/md/dm-table.c:dm_get_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578853936,
      "name": "name_to_dev_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 549
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
dev_t name_to_dev_t(const char * name)
```

```json
{
  "name": "name_to_dev_t",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490177280,
      "name": "name_to_dev_t",
      "external": true,
      "loc": "init/do_mounts.c:222",
      "file": "init/do_mounts.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts_md.c:md_setup_drive",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490177280,
      "name": "name_to_dev_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1016
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
dev_t name_to_dev_t(const char * name)
```

```json
{
  "name": "name_to_dev_t",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224386180,
      "name": "name_to_dev_t",
      "external": true,
      "loc": "init/do_mounts.c:222",
      "file": "init/do_mounts.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts_md.c:md_setup_drive",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224386180,
      "name": "name_to_dev_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1064
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
dev_t name_to_dev_t(const char * name)
```

```json
{
  "name": "name_to_dev_t",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055282231968,
      "name": "name_to_dev_t",
      "external": true,
      "loc": "init/do_mounts.c:222",
      "file": "init/do_mounts.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts_md.c:md_setup_drive",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282231968,
      "name": "name_to_dev_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
dev_t name_to_dev_t(const char * name)
```

```json
{
  "name": "name_to_dev_t",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271337168,
      "name": "name_to_dev_t",
      "external": true,
      "loc": "init/do_mounts.c:222",
      "file": "init/do_mounts.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts_md.c:md_setup_drive",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271337168,
      "name": "name_to_dev_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 978
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
dev_t name_to_dev_t(const char * name)
```

```json
{
  "name": "name_to_dev_t",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578856547,
      "name": "name_to_dev_t",
      "external": true,
      "loc": "init/do_mounts.c:222",
      "file": "init/do_mounts.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts_md.c:md_setup_drive",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578857585,
      "name": "name_to_dev_t.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071578856448,
      "name": "name_to_dev_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
dev_t name_to_dev_t(const char * name)
```

```json
{
  "name": "name_to_dev_t",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578849603,
      "name": "name_to_dev_t",
      "external": true,
      "loc": "init/do_mounts.c:222",
      "file": "init/do_mounts.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts_md.c:md_setup_drive",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578850641,
      "name": "name_to_dev_t.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071578849504,
      "name": "name_to_dev_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
dev_t name_to_dev_t(const char * name)
```

```json
{
  "name": "name_to_dev_t",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578856547,
      "name": "name_to_dev_t",
      "external": true,
      "loc": "init/do_mounts.c:222",
      "file": "init/do_mounts.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts_md.c:md_setup_drive",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578857585,
      "name": "name_to_dev_t.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071578856448,
      "name": "name_to_dev_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
dev_t name_to_dev_t(const char * name)
```

```json
{
  "name": "name_to_dev_t",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578856627,
      "name": "name_to_dev_t",
      "external": true,
      "loc": "init/do_mounts.c:222",
      "file": "init/do_mounts.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts_md.c:md_setup_drive",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578857665,
      "name": "name_to_dev_t.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071578856528,
      "name": "name_to_dev_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1137
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
dev_t name_to_dev_t(const char * name)
```
</details>
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
