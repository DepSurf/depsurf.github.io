# Function: <code>check_security_state</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int check_security_state(struct nvdimm * nvdimm)
```

```json
{
  "name": "check_security_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586584480,
      "name": "check_security_state",
      "external": false,
      "loc": "drivers/nvdimm/security.c:224",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586584480,
      "name": "check_security_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
int check_security_state(struct nvdimm * nvdimm)
```

```json
{
  "name": "check_security_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587370032,
      "name": "check_security_state",
      "external": false,
      "loc": "drivers/nvdimm/security.c:224",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:security_overwrite",
        "drivers/nvdimm/security.c:security_erase",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:security_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587370032,
      "name": "check_security_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
int check_security_state(struct nvdimm * nvdimm)
```

```json
{
  "name": "check_security_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587430720,
      "name": "check_security_state",
      "external": false,
      "loc": "drivers/nvdimm/security.c:224",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:security_overwrite",
        "drivers/nvdimm/security.c:security_erase",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:security_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587430720,
      "name": "check_security_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
int check_security_state(struct nvdimm * nvdimm)
```

```json
{
  "name": "check_security_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587312592,
      "name": "check_security_state",
      "external": false,
      "loc": "drivers/nvdimm/security.c:224",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:security_overwrite",
        "drivers/nvdimm/security.c:security_erase",
        "drivers/nvdimm/security.c:security_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587312592,
      "name": "check_security_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
int check_security_state(struct nvdimm * nvdimm)
```

```json
{
  "name": "check_security_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587879456,
      "name": "check_security_state",
      "external": false,
      "loc": "drivers/nvdimm/security.c:224",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:security_overwrite",
        "drivers/nvdimm/security.c:security_erase",
        "drivers/nvdimm/security.c:security_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587879456,
      "name": "check_security_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
int check_security_state(struct nvdimm * nvdimm)
```

```json
{
  "name": "check_security_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589229632,
      "name": "check_security_state",
      "external": false,
      "loc": "drivers/nvdimm/security.c:224",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:security_overwrite",
        "drivers/nvdimm/security.c:security_erase",
        "drivers/nvdimm/security.c:security_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589229632,
      "name": "check_security_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
int check_security_state(struct nvdimm * nvdimm)
```

```json
{
  "name": "check_security_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590786656,
      "name": "check_security_state",
      "external": false,
      "loc": "drivers/nvdimm/security.c:230",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:security_overwrite",
        "drivers/nvdimm/security.c:security_erase",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:security_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590786656,
      "name": "check_security_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
int check_security_state(struct nvdimm * nvdimm)
```

```json
{
  "name": "check_security_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591128160,
      "name": "check_security_state",
      "external": false,
      "loc": "drivers/nvdimm/security.c:230",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:security_overwrite",
        "drivers/nvdimm/security.c:security_erase",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:security_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591128160,
      "name": "check_security_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
int check_security_state(struct nvdimm * nvdimm)
```

```json
{
  "name": "check_security_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591473840,
      "name": "check_security_state",
      "external": false,
      "loc": "drivers/nvdimm/security.c:230",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:security_overwrite",
        "drivers/nvdimm/security.c:security_erase",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:security_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591473840,
      "name": "check_security_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
int check_security_state(struct nvdimm * nvdimm)
```

```json
{
  "name": "check_security_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499467936,
      "name": "check_security_state",
      "external": false,
      "loc": "drivers/nvdimm/security.c:224",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499467936,
      "name": "check_security_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int check_security_state(struct nvdimm * nvdimm)
```

```json
{
  "name": "check_security_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292744160,
      "name": "check_security_state",
      "external": false,
      "loc": "drivers/nvdimm/security.c:224",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292744160,
      "name": "check_security_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
int check_security_state(struct nvdimm * nvdimm)
```

```json
{
  "name": "check_security_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276688706,
      "name": "check_security_state",
      "external": false,
      "loc": "drivers/nvdimm/security.c:224",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276688706,
      "name": "check_security_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
int check_security_state(struct nvdimm * nvdimm)
```

```json
{
  "name": "check_security_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586274960,
      "name": "check_security_state",
      "external": false,
      "loc": "drivers/nvdimm/security.c:224",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586274960,
      "name": "check_security_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
int check_security_state(struct nvdimm * nvdimm)
```

```json
{
  "name": "check_security_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586093328,
      "name": "check_security_state",
      "external": false,
      "loc": "drivers/nvdimm/security.c:224",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586093328,
      "name": "check_security_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
int check_security_state(struct nvdimm * nvdimm)
```

```json
{
  "name": "check_security_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586532448,
      "name": "check_security_state",
      "external": false,
      "loc": "drivers/nvdimm/security.c:224",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586532448,
      "name": "check_security_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
int check_security_state(struct nvdimm * nvdimm)
```

```json
{
  "name": "check_security_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586644176,
      "name": "check_security_state",
      "external": false,
      "loc": "drivers/nvdimm/security.c:224",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586644176,
      "name": "check_security_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int check_security_state(struct nvdimm * nvdimm)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int check_security_state(struct nvdimm * nvdimm)
```
</details>
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
