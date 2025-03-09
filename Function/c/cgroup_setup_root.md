# Function: <code>cgroup_setup_root</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int cgroup_setup_root(struct cgroup_root * root, long unsigned int ss_mask)
```

```json
{
  "name": "cgroup_setup_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579991040,
      "name": "cgroup_setup_root",
      "external": false,
      "loc": "kernel/cgroup.c:1959",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_mount",
        "kernel/cgroup.c:cgroup_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579991040,
      "name": "cgroup_setup_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 625
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
int cgroup_setup_root(struct cgroup_root * root, u16 ss_mask)
```

```json
{
  "name": "cgroup_setup_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580022176,
      "name": "cgroup_setup_root",
      "external": false,
      "loc": "kernel/cgroup.c:1982",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_init",
        "kernel/cgroup.c:cgroup_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580022176,
      "name": "cgroup_setup_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 642
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
int cgroup_setup_root(struct cgroup_root * root, u16 ss_mask)
```

```json
{
  "name": "cgroup_setup_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580055984,
      "name": "cgroup_setup_root",
      "external": false,
      "loc": "kernel/cgroup.c:1990",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_init",
        "kernel/cgroup.c:cgroup_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580055984,
      "name": "cgroup_setup_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 719
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
int cgroup_setup_root(struct cgroup_root * root, u16 ss_mask, int ref_flags)
```

```json
{
  "name": "cgroup_setup_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580051776,
      "name": "cgroup_setup_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1700",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup-v1.c:cgroup1_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580051776,
      "name": "cgroup_setup_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 753
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
int cgroup_setup_root(struct cgroup_root * root, u16 ss_mask, int ref_flags)
```

```json
{
  "name": "cgroup_setup_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580101696,
      "name": "cgroup_setup_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1874",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup-v1.c:cgroup1_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580101696,
      "name": "cgroup_setup_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 779
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
int cgroup_setup_root(struct cgroup_root * root, u16 ss_mask, int ref_flags)
```

```json
{
  "name": "cgroup_setup_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580160752,
      "name": "cgroup_setup_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1892",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup-v1.c:cgroup1_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580160752,
      "name": "cgroup_setup_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 763
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
int cgroup_setup_root(struct cgroup_root * root, u16 ss_mask, int ref_flags)
```

```json
{
  "name": "cgroup_setup_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580208544,
      "name": "cgroup_setup_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1930",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup-v1.c:cgroup1_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580208544,
      "name": "cgroup_setup_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 763
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
int cgroup_setup_root(struct cgroup_root * root, u16 ss_mask)
```

```json
{
  "name": "cgroup_setup_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580256672,
      "name": "cgroup_setup_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1990",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580256672,
      "name": "cgroup_setup_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 752
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
int cgroup_setup_root(struct cgroup_root * root, u16 ss_mask)
```

```json
{
  "name": "cgroup_setup_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580304896,
      "name": "cgroup_setup_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1990",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580304896,
      "name": "cgroup_setup_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 752
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
int cgroup_setup_root(struct cgroup_root * root, u16 ss_mask)
```

```json
{
  "name": "cgroup_setup_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580374592,
      "name": "cgroup_setup_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1927",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580374592,
      "name": "cgroup_setup_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 828
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
int cgroup_setup_root(struct cgroup_root * root, u16 ss_mask)
```

```json
{
  "name": "cgroup_setup_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580361456,
      "name": "cgroup_setup_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1924",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580361456,
      "name": "cgroup_setup_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 800
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
int cgroup_setup_root(struct cgroup_root * root, u16 ss_mask)
```

```json
{
  "name": "cgroup_setup_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580364336,
      "name": "cgroup_setup_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1931",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580364336,
      "name": "cgroup_setup_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 971
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
int cgroup_setup_root(struct cgroup_root * root, u16 ss_mask)
```

```json
{
  "name": "cgroup_setup_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580523696,
      "name": "cgroup_setup_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1985",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580523696,
      "name": "cgroup_setup_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1125
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
int cgroup_setup_root(struct cgroup_root * root, u16 ss_mask)
```

```json
{
  "name": "cgroup_setup_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580720720,
      "name": "cgroup_setup_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1989",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580720720,
      "name": "cgroup_setup_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 922
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
int cgroup_setup_root(struct cgroup_root * root, u16 ss_mask)
```

```json
{
  "name": "cgroup_setup_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580995568,
      "name": "cgroup_setup_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2046",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580995568,
      "name": "cgroup_setup_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 919
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
int cgroup_setup_root(struct cgroup_root * root, u16 ss_mask)
```

```json
{
  "name": "cgroup_setup_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581084128,
      "name": "cgroup_setup_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2054",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581084128,
      "name": "cgroup_setup_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 922
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
int cgroup_setup_root(struct cgroup_root * root, u16 ss_mask)
```

```json
{
  "name": "cgroup_setup_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581181648,
      "name": "cgroup_setup_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2063",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581181648,
      "name": "cgroup_setup_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 913
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
int cgroup_setup_root(struct cgroup_root * root, u16 ss_mask)
```

```json
{
  "name": "cgroup_setup_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491556640,
      "name": "cgroup_setup_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1990",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491556640,
      "name": "cgroup_setup_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 784
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
int cgroup_setup_root(struct cgroup_root * root, u16 ss_mask)
```

```json
{
  "name": "cgroup_setup_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225520928,
      "name": "cgroup_setup_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1990",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225520928,
      "name": "cgroup_setup_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 868
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
int cgroup_setup_root(struct cgroup_root * root, u16 ss_mask)
```

```json
{
  "name": "cgroup_setup_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284529552,
      "name": "cgroup_setup_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1990",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284529552,
      "name": "cgroup_setup_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1036
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
int cgroup_setup_root(struct cgroup_root * root, u16 ss_mask)
```

```json
{
  "name": "cgroup_setup_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271970708,
      "name": "cgroup_setup_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1990",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271970708,
      "name": "cgroup_setup_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 746
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
int cgroup_setup_root(struct cgroup_root * root, u16 ss_mask)
```

```json
{
  "name": "cgroup_setup_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580273696,
      "name": "cgroup_setup_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1990",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580273696,
      "name": "cgroup_setup_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 752
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
int cgroup_setup_root(struct cgroup_root * root, u16 ss_mask)
```

```json
{
  "name": "cgroup_setup_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580221200,
      "name": "cgroup_setup_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1990",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580221200,
      "name": "cgroup_setup_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 746
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
int cgroup_setup_root(struct cgroup_root * root, u16 ss_mask)
```

```json
{
  "name": "cgroup_setup_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580264944,
      "name": "cgroup_setup_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1990",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580264944,
      "name": "cgroup_setup_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 752
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
int cgroup_setup_root(struct cgroup_root * root, u16 ss_mask)
```

```json
{
  "name": "cgroup_setup_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580318288,
      "name": "cgroup_setup_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1990",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580318288,
      "name": "cgroup_setup_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 752
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long unsigned int ss_mask</code> ➡️ <code>u16 ss_mask</code>
</li>
</ul>
</details>
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
<code>int ref_flags</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int ref_flags</code>
</li>
</ul>
</details>
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
