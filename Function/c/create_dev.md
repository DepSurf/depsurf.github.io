# Function: <code>create_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int create_dev(char * name, dev_t dev)
```

```json
{
  "name": "create_dev",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594944334,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:16",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:mount_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578857069,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:16",
      "file": "init/do_mounts_rd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_rd.c:rd_load_disk",
        "init/do_mounts_rd.c:rd_load_disk"
      ]
    },
    {
      "addr": 18446744071594946585,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:16",
      "file": "init/do_mounts_initrd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_initrd.c:initrd_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594948248,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:16",
      "file": "init/do_mounts_md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_run_setup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578857069,
      "name": "create_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
int create_dev(char * name, dev_t dev)
```

```json
{
  "name": "create_dev",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578857187,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:16",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:mount_root"
      ]
    },
    {
      "addr": 18446744071578857251,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:16",
      "file": "init/do_mounts_rd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_rd.c:rd_load_disk",
        "init/do_mounts_rd.c:rd_load_disk"
      ]
    },
    {
      "addr": 18446744071595110339,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:16",
      "file": "init/do_mounts_initrd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_initrd.c:initrd_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595112919,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:16",
      "file": "init/do_mounts_md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578857187,
      "name": "create_dev.constprop.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071578857251,
      "name": "create_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_dev",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578857091,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:16",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:mount_root"
      ]
    },
    {
      "addr": 18446744071595354205,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:16",
      "file": "init/do_mounts_initrd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_initrd.c:initrd_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595356140,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:16",
      "file": "init/do_mounts_md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578857091,
      "name": "create_dev.constprop.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_dev",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578855328,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:16",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:mount_root"
      ]
    },
    {
      "addr": 18446744071596272025,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:16",
      "file": "init/do_mounts_initrd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_initrd.c:initrd_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596273950,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:16",
      "file": "init/do_mounts_md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578855328,
      "name": "create_dev.constprop.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_dev",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578855376,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:mount_root"
      ]
    },
    {
      "addr": 18446744071602588054,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts_initrd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_initrd.c:initrd_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602589979,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts_md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578855376,
      "name": "create_dev.constprop.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_dev",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578857210,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:mount_root"
      ]
    },
    {
      "addr": 18446744071602756256,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts_initrd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_initrd.c:initrd_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602758308,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts_md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578857210,
      "name": "create_dev.constprop.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_dev",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578857351,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:mount_root"
      ]
    },
    {
      "addr": 18446744071604550371,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts_initrd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_initrd.c:initrd_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604552423,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts_md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578857351,
      "name": "create_dev.constprop.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_dev",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578857652,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:mount_root"
      ]
    },
    {
      "addr": 18446744071604644624,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts_initrd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_initrd.c:initrd_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604646712,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts_md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578857652,
      "name": "create_dev.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_dev",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578857636,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:mount_root"
      ]
    },
    {
      "addr": 18446744071604656885,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts_initrd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_initrd.c:initrd_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604658973,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts_md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578857636,
      "name": "create_dev.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_dev",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578862201,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:mount_root"
      ]
    },
    {
      "addr": 18446744071609008325,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts_initrd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_initrd.c:initrd_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578862447,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts_md.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578862201,
      "name": "create_dev.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071578862447,
      "name": "create_dev.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_dev",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612071021,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:mount_root"
      ]
    },
    {
      "addr": 18446744071612072431,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts_initrd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_initrd.c:initrd_load"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612071021,
      "name": "create_dev.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_dev",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614209233,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:mount_root"
      ]
    },
    {
      "addr": 18446744071614210642,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts_initrd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_initrd.c:initrd_load"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614209233,
      "name": "create_dev.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_dev",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615127920,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:mount_root"
      ]
    },
    {
      "addr": 18446744071615129360,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts_initrd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_initrd.c:initrd_load"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615127920,
      "name": "create_dev.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_dev",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071616889490,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:mount_root"
      ]
    },
    {
      "addr": 18446744071616891424,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts_initrd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_initrd.c:initrd_load"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071616889490,
      "name": "create_dev.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_dev",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627482873,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:mount_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627483565,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts_initrd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_initrd.c:initrd_load"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_dev",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619226464,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:mount_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619227485,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts_initrd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_initrd.c:initrd_load"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_dev",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621516304,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:mount_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621517373,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts_initrd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_initrd.c:initrd_load"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "create_dev",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490178296,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:mount_root"
      ]
    },
    {
      "addr": 18446603336510807188,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts_initrd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_initrd.c:initrd_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510809276,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts_md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490178296,
      "name": "create_dev.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "create_dev",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224387244,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:mount_root"
      ]
    },
    {
      "addr": 3243252944,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts_initrd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_initrd.c:initrd_load"
      ],
      "caller_func": []
    },
    {
      "addr": 3243255068,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts_md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3224387244,
      "name": "create_dev.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "create_dev",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055282234180,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:mount_root"
      ]
    },
    {
      "addr": 13835058055302369744,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts_initrd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_initrd.c:initrd_load"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302372520,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts_md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282234180,
      "name": "create_dev.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "create_dev",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271338146,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:mount_root"
      ]
    },
    {
      "addr": 18446743936270604574,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts_initrd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_initrd.c:initrd_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270606476,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts_md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271338146,
      "name": "create_dev.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_dev",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578857636,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:mount_root"
      ]
    },
    {
      "addr": 18446744071604583157,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts_initrd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_initrd.c:initrd_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604585245,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts_md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578857636,
      "name": "create_dev.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_dev",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578850692,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:mount_root"
      ]
    },
    {
      "addr": 18446744071604574834,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts_initrd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_initrd.c:initrd_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604576922,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts_md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578850692,
      "name": "create_dev.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_dev",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578857636,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:mount_root"
      ]
    },
    {
      "addr": 18446744071604660981,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts_initrd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_initrd.c:initrd_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604663069,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts_md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578857636,
      "name": "create_dev.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_dev",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578857716,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "init/do_mounts.c:mount_root"
      ]
    },
    {
      "addr": 18446744071604660986,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts_initrd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_initrd.c:initrd_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604663074,
      "name": "create_dev",
      "external": false,
      "loc": "init/do_mounts.h:17",
      "file": "init/do_mounts_md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578857716,
      "name": "create_dev.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
int create_dev(char * name, dev_t dev)
```
</details>
</li>
</ul>
