# Function: <code>cgroup_file_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_file_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579973536,
      "name": "cgroup_file_name",
      "external": false,
      "loc": "kernel/cgroup.c:1247",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup.c:cgroup_addrm_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579973536,
      "name": "cgroup_file_name.isra.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
char * cgroup_file_name(struct cgroup * cgrp, const struct cftype * cft, char * buf)
```

```json
{
  "name": "cgroup_file_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579998400,
      "name": "cgroup_file_name",
      "external": false,
      "loc": "kernel/cgroup.c:1321",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup.c:cgroup_addrm_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579998400,
      "name": "cgroup_file_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
char * cgroup_file_name(struct cgroup * cgrp, const struct cftype * cft, char * buf)
```

```json
{
  "name": "cgroup_file_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580029856,
      "name": "cgroup_file_name",
      "external": false,
      "loc": "kernel/cgroup.c:1326",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup.c:cgroup_addrm_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580029856,
      "name": "cgroup_file_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
char * cgroup_file_name(struct cgroup * cgrp, const struct cftype * cft, char * buf)
```

```json
{
  "name": "cgroup_file_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580031648,
      "name": "cgroup_file_name",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1218",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580031648,
      "name": "cgroup_file_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
char * cgroup_file_name(struct cgroup * cgrp, const struct cftype * cft, char * buf)
```

```json
{
  "name": "cgroup_file_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580078736,
      "name": "cgroup_file_name",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1389",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580078736,
      "name": "cgroup_file_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
char * cgroup_file_name(struct cgroup * cgrp, const struct cftype * cft, char * buf)
```

```json
{
  "name": "cgroup_file_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580139280,
      "name": "cgroup_file_name",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1392",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580139280,
      "name": "cgroup_file_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
char * cgroup_file_name(struct cgroup * cgrp, const struct cftype * cft, char * buf)
```

```json
{
  "name": "cgroup_file_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580186512,
      "name": "cgroup_file_name",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1427",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580186512,
      "name": "cgroup_file_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
char * cgroup_file_name(struct cgroup * cgrp, const struct cftype * cft, char * buf)
```

```json
{
  "name": "cgroup_file_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580232208,
      "name": "cgroup_file_name",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1468",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580232208,
      "name": "cgroup_file_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
char * cgroup_file_name(struct cgroup * cgrp, const struct cftype * cft, char * buf)
```

```json
{
  "name": "cgroup_file_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580280416,
      "name": "cgroup_file_name",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1468",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580280416,
      "name": "cgroup_file_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
char * cgroup_file_name(struct cgroup * cgrp, const struct cftype * cft, char * buf)
```

```json
{
  "name": "cgroup_file_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580346880,
      "name": "cgroup_file_name",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1458",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_add_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580346880,
      "name": "cgroup_file_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
char * cgroup_file_name(struct cgroup * cgrp, const struct cftype * cft, char * buf)
```

```json
{
  "name": "cgroup_file_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_file_name",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1455",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_add_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580333056,
      "name": "cgroup_file_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    },
    {
      "addr": 18446744071591315122,
      "name": "cgroup_file_name.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
char * cgroup_file_name(struct cgroup * cgrp, const struct cftype * cft, char * buf)
```

```json
{
  "name": "cgroup_file_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_file_name",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1456",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580336000,
      "name": "cgroup_file_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    },
    {
      "addr": 18446744071591257299,
      "name": "cgroup_file_name.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
char * cgroup_file_name(struct cgroup * cgrp, const struct cftype * cft, char * buf)
```

```json
{
  "name": "cgroup_file_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_file_name",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1487",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580490656,
      "name": "cgroup_file_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    },
    {
      "addr": 18446744071592160704,
      "name": "cgroup_file_name.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
char * cgroup_file_name(struct cgroup * cgrp, const struct cftype * cft, char * buf)
```

```json
{
  "name": "cgroup_file_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_file_name",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1490",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580685648,
      "name": "cgroup_file_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    },
    {
      "addr": 18446744071593933765,
      "name": "cgroup_file_name.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
char * cgroup_file_name(struct cgroup * cgrp, const struct cftype * cft, char * buf)
```

```json
{
  "name": "cgroup_file_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580957456,
      "name": "cgroup_file_name",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1524",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580957456,
      "name": "cgroup_file_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
char * cgroup_file_name(struct cgroup * cgrp, const struct cftype * cft, char * buf)
```

```json
{
  "name": "cgroup_file_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581044848,
      "name": "cgroup_file_name",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1518",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581044848,
      "name": "cgroup_file_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
char * cgroup_file_name(struct cgroup * cgrp, const struct cftype * cft, char * buf)
```

```json
{
  "name": "cgroup_file_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581142064,
      "name": "cgroup_file_name",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1513",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581142064,
      "name": "cgroup_file_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
char * cgroup_file_name(struct cgroup * cgrp, const struct cftype * cft, char * buf)
```

```json
{
  "name": "cgroup_file_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491527920,
      "name": "cgroup_file_name",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1468",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491527920,
      "name": "cgroup_file_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
char * cgroup_file_name(struct cgroup * cgrp, const struct cftype * cft, char * buf)
```

```json
{
  "name": "cgroup_file_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225494392,
      "name": "cgroup_file_name",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1468",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225494392,
      "name": "cgroup_file_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
char * cgroup_file_name(struct cgroup * cgrp, const struct cftype * cft, char * buf)
```

```json
{
  "name": "cgroup_file_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284494240,
      "name": "cgroup_file_name",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1468",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284494240,
      "name": "cgroup_file_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
char * cgroup_file_name(struct cgroup * cgrp, const struct cftype * cft, char * buf)
```

```json
{
  "name": "cgroup_file_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271947462,
      "name": "cgroup_file_name",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1468",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271947462,
      "name": "cgroup_file_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
char * cgroup_file_name(struct cgroup * cgrp, const struct cftype * cft, char * buf)
```

```json
{
  "name": "cgroup_file_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580249216,
      "name": "cgroup_file_name",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1468",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580249216,
      "name": "cgroup_file_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
char * cgroup_file_name(struct cgroup * cgrp, const struct cftype * cft, char * buf)
```

```json
{
  "name": "cgroup_file_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580196768,
      "name": "cgroup_file_name",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1468",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580196768,
      "name": "cgroup_file_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
char * cgroup_file_name(struct cgroup * cgrp, const struct cftype * cft, char * buf)
```

```json
{
  "name": "cgroup_file_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580240464,
      "name": "cgroup_file_name",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1468",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580240464,
      "name": "cgroup_file_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
char * cgroup_file_name(struct cgroup * cgrp, const struct cftype * cft, char * buf)
```

```json
{
  "name": "cgroup_file_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580293456,
      "name": "cgroup_file_name",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1468",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580293456,
      "name": "cgroup_file_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
char * cgroup_file_name(struct cgroup * cgrp, const struct cftype * cft, char * buf)
```
</details>
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
