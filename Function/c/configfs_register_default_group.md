# Function: <code>configfs_register_default_group</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct config_group * configfs_register_default_group(struct config_group * parent_group, const char * name, struct config_item_type * item_type)
```

```json
{
  "name": "configfs_register_default_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581861520,
      "name": "configfs_register_default_group",
      "external": true,
      "loc": "fs/configfs/dir.c:1811",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_add_epf_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581861520,
      "name": "configfs_register_default_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
struct config_group * configfs_register_default_group(struct config_group * parent_group, const char * name, const struct config_item_type * item_type)
```

```json
{
  "name": "configfs_register_default_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582011408,
      "name": "configfs_register_default_group",
      "external": true,
      "loc": "fs/configfs/dir.c:1811",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_add_epf_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582011408,
      "name": "configfs_register_default_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
struct config_group * configfs_register_default_group(struct config_group * parent_group, const char * name, const struct config_item_type * item_type)
```

```json
{
  "name": "configfs_register_default_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582200208,
      "name": "configfs_register_default_group",
      "external": true,
      "loc": "fs/configfs/dir.c:1822",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_add_epf_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582200208,
      "name": "configfs_register_default_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
struct config_group * configfs_register_default_group(struct config_group * parent_group, const char * name, const struct config_item_type * item_type)
```

```json
{
  "name": "configfs_register_default_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582295424,
      "name": "configfs_register_default_group",
      "external": true,
      "loc": "fs/configfs/dir.c:1822",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_add_epf_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582295424,
      "name": "configfs_register_default_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
struct config_group * configfs_register_default_group(struct config_group * parent_group, const char * name, const struct config_item_type * item_type)
```

```json
{
  "name": "configfs_register_default_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582461376,
      "name": "configfs_register_default_group",
      "external": true,
      "loc": "fs/configfs/dir.c:1874",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_add_epf_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582461376,
      "name": "configfs_register_default_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct config_group * configfs_register_default_group(struct config_group * parent_group, const char * name, const struct config_item_type * item_type)
```

```json
{
  "name": "configfs_register_default_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582560704,
      "name": "configfs_register_default_group",
      "external": true,
      "loc": "fs/configfs/dir.c:1831",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_add_epf_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582560704,
      "name": "configfs_register_default_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct config_group * configfs_register_default_group(struct config_group * parent_group, const char * name, const struct config_item_type * item_type)
```

```json
{
  "name": "configfs_register_default_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582869728,
      "name": "configfs_register_default_group",
      "external": true,
      "loc": "fs/configfs/dir.c:1832",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_add_epf_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582869728,
      "name": "configfs_register_default_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
struct config_group * configfs_register_default_group(struct config_group * parent_group, const char * name, const struct config_item_type * item_type)
```

```json
{
  "name": "configfs_register_default_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582942640,
      "name": "configfs_register_default_group",
      "external": true,
      "loc": "fs/configfs/dir.c:1833",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_add_epf_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582942640,
      "name": "configfs_register_default_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
struct config_group * configfs_register_default_group(struct config_group * parent_group, const char * name, const struct config_item_type * item_type)
```

```json
{
  "name": "configfs_register_default_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582970720,
      "name": "configfs_register_default_group",
      "external": true,
      "loc": "fs/configfs/dir.c:1832",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_add_epf_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582970720,
      "name": "configfs_register_default_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
struct config_group * configfs_register_default_group(struct config_group * parent_group, const char * name, const struct config_item_type * item_type)
```

```json
{
  "name": "configfs_register_default_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583306320,
      "name": "configfs_register_default_group",
      "external": true,
      "loc": "fs/configfs/dir.c:1815",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_add_epf_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583306320,
      "name": "configfs_register_default_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
struct config_group * configfs_register_default_group(struct config_group * parent_group, const char * name, const struct config_item_type * item_type)
```

```json
{
  "name": "configfs_register_default_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583813104,
      "name": "configfs_register_default_group",
      "external": true,
      "loc": "fs/configfs/dir.c:1815",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_add_epf_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583813104,
      "name": "configfs_register_default_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
struct config_group * configfs_register_default_group(struct config_group * parent_group, const char * name, const struct config_item_type * item_type)
```

```json
{
  "name": "configfs_register_default_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584434560,
      "name": "configfs_register_default_group",
      "external": true,
      "loc": "fs/configfs/dir.c:1817",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_add_epf_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584434560,
      "name": "configfs_register_default_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
struct config_group * configfs_register_default_group(struct config_group * parent_group, const char * name, const struct config_item_type * item_type)
```

```json
{
  "name": "configfs_register_default_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584663296,
      "name": "configfs_register_default_group",
      "external": true,
      "loc": "fs/configfs/dir.c:1812",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_add_epf_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584663296,
      "name": "configfs_register_default_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
struct config_group * configfs_register_default_group(struct config_group * parent_group, const char * name, const struct config_item_type * item_type)
```

```json
{
  "name": "configfs_register_default_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584895952,
      "name": "configfs_register_default_group",
      "external": true,
      "loc": "fs/configfs/dir.c:1812",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_add_epf_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584895952,
      "name": "configfs_register_default_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
struct config_group * configfs_register_default_group(struct config_group * parent_group, const char * name, const struct config_item_type * item_type)
```

```json
{
  "name": "configfs_register_default_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494203584,
      "name": "configfs_register_default_group",
      "external": true,
      "loc": "fs/configfs/dir.c:1831",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_add_epf_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494203584,
      "name": "configfs_register_default_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
struct config_group * configfs_register_default_group(struct config_group * parent_group, const char * name, const struct config_item_type * item_type)
```

```json
{
  "name": "configfs_register_default_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227636844,
      "name": "configfs_register_default_group",
      "external": true,
      "loc": "fs/configfs/dir.c:1831",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_add_epf_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227636844,
      "name": "configfs_register_default_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
struct config_group * configfs_register_default_group(struct config_group * parent_group, const char * name, const struct config_item_type * item_type)
```

```json
{
  "name": "configfs_register_default_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287896752,
      "name": "configfs_register_default_group",
      "external": true,
      "loc": "fs/configfs/dir.c:1831",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_add_epf_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287896752,
      "name": "configfs_register_default_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
struct config_group * configfs_register_default_group(struct config_group * parent_group, const char * name, const struct config_item_type * item_type)
```

```json
{
  "name": "configfs_register_default_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273663664,
      "name": "configfs_register_default_group",
      "external": true,
      "loc": "fs/configfs/dir.c:1831",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_add_epf_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273663664,
      "name": "configfs_register_default_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
struct config_group * configfs_register_default_group(struct config_group * parent_group, const char * name, const struct config_item_type * item_type)
```

```json
{
  "name": "configfs_register_default_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582529440,
      "name": "configfs_register_default_group",
      "external": true,
      "loc": "fs/configfs/dir.c:1831",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_add_epf_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582529440,
      "name": "configfs_register_default_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct config_group * configfs_register_default_group(struct config_group * parent_group, const char * name, const struct config_item_type * item_type)
```

```json
{
  "name": "configfs_register_default_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582466608,
      "name": "configfs_register_default_group",
      "external": true,
      "loc": "fs/configfs/dir.c:1831",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_add_epf_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582466608,
      "name": "configfs_register_default_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct config_group * configfs_register_default_group(struct config_group * parent_group, const char * name, const struct config_item_type * item_type)
```

```json
{
  "name": "configfs_register_default_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582519920,
      "name": "configfs_register_default_group",
      "external": true,
      "loc": "fs/configfs/dir.c:1831",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_add_epf_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582519920,
      "name": "configfs_register_default_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct config_group * configfs_register_default_group(struct config_group * parent_group, const char * name, const struct config_item_type * item_type)
```

```json
{
  "name": "configfs_register_default_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582600496,
      "name": "configfs_register_default_group",
      "external": true,
      "loc": "fs/configfs/dir.c:1831",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_add_epf_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582600496,
      "name": "configfs_register_default_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct config_group * configfs_register_default_group(struct config_group * parent_group, const char * name, struct config_item_type * item_type)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct config_item_type * item_type</code> ➡️ <code>const struct config_item_type * item_type</code>
</li>
</ul>
</details>
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
