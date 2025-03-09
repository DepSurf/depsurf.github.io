# Function: <code>nvdimm_request_key</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct key * nvdimm_request_key(struct nvdimm * nvdimm)
```

```json
{
  "name": "nvdimm_request_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586200880,
      "name": "nvdimm_request_key",
      "external": false,
      "loc": "drivers/nvdimm/security.c:48",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_unlock",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586200880,
      "name": "nvdimm_request_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
struct key * nvdimm_request_key(struct nvdimm * nvdimm)
```

```json
{
  "name": "nvdimm_request_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586437536,
      "name": "nvdimm_request_key",
      "external": false,
      "loc": "drivers/nvdimm/security.c:50",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_unlock",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586437536,
      "name": "nvdimm_request_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
struct key * nvdimm_request_key(struct nvdimm * nvdimm)
```

```json
{
  "name": "nvdimm_request_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586584608,
      "name": "nvdimm_request_key",
      "external": false,
      "loc": "drivers/nvdimm/security.c:50",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_unlock",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586584608,
      "name": "nvdimm_request_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
struct key * nvdimm_request_key(struct nvdimm * nvdimm)
```

```json
{
  "name": "nvdimm_request_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587370160,
      "name": "nvdimm_request_key",
      "external": false,
      "loc": "drivers/nvdimm/security.c:50",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:__nvdimm_security_unlock",
        "drivers/nvdimm/security.c:nvdimm_key_revalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587370160,
      "name": "nvdimm_request_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
struct key * nvdimm_request_key(struct nvdimm * nvdimm)
```

```json
{
  "name": "nvdimm_request_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587430848,
      "name": "nvdimm_request_key",
      "external": false,
      "loc": "drivers/nvdimm/security.c:50",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:__nvdimm_security_unlock",
        "drivers/nvdimm/security.c:nvdimm_key_revalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587430848,
      "name": "nvdimm_request_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
struct key * nvdimm_request_key(struct nvdimm * nvdimm)
```

```json
{
  "name": "nvdimm_request_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587312720,
      "name": "nvdimm_request_key",
      "external": false,
      "loc": "drivers/nvdimm/security.c:50",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:__nvdimm_security_unlock",
        "drivers/nvdimm/security.c:__nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587312720,
      "name": "nvdimm_request_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
struct key * nvdimm_request_key(struct nvdimm * nvdimm)
```

```json
{
  "name": "nvdimm_request_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587879568,
      "name": "nvdimm_request_key",
      "external": false,
      "loc": "drivers/nvdimm/security.c:50",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:__nvdimm_security_unlock",
        "drivers/nvdimm/security.c:__nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587879568,
      "name": "nvdimm_request_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
struct key * nvdimm_request_key(struct nvdimm * nvdimm)
```

```json
{
  "name": "nvdimm_request_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589229776,
      "name": "nvdimm_request_key",
      "external": false,
      "loc": "drivers/nvdimm/security.c:50",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:__nvdimm_security_unlock",
        "drivers/nvdimm/security.c:__nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589229776,
      "name": "nvdimm_request_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
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
struct key * nvdimm_request_key(struct nvdimm * nvdimm)
```

```json
{
  "name": "nvdimm_request_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590786816,
      "name": "nvdimm_request_key",
      "external": false,
      "loc": "drivers/nvdimm/security.c:50",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:__nvdimm_security_unlock",
        "drivers/nvdimm/security.c:__nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590786816,
      "name": "nvdimm_request_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
struct key * nvdimm_request_key(struct nvdimm * nvdimm)
```

```json
{
  "name": "nvdimm_request_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591128320,
      "name": "nvdimm_request_key",
      "external": false,
      "loc": "drivers/nvdimm/security.c:50",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:__nvdimm_security_unlock",
        "drivers/nvdimm/security.c:__nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591128320,
      "name": "nvdimm_request_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
struct key * nvdimm_request_key(struct nvdimm * nvdimm)
```

```json
{
  "name": "nvdimm_request_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591474000,
      "name": "nvdimm_request_key",
      "external": false,
      "loc": "drivers/nvdimm/security.c:50",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:__nvdimm_security_unlock",
        "drivers/nvdimm/security.c:__nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591474000,
      "name": "nvdimm_request_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
struct key * nvdimm_request_key(struct nvdimm * nvdimm)
```

```json
{
  "name": "nvdimm_request_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499468096,
      "name": "nvdimm_request_key",
      "external": false,
      "loc": "drivers/nvdimm/security.c:50",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_unlock",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499468096,
      "name": "nvdimm_request_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
struct key * nvdimm_request_key(struct nvdimm * nvdimm)
```

```json
{
  "name": "nvdimm_request_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292744352,
      "name": "nvdimm_request_key",
      "external": false,
      "loc": "drivers/nvdimm/security.c:50",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_unlock",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292744352,
      "name": "nvdimm_request_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
struct key * nvdimm_request_key(struct nvdimm * nvdimm)
```

```json
{
  "name": "nvdimm_request_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276688854,
      "name": "nvdimm_request_key",
      "external": false,
      "loc": "drivers/nvdimm/security.c:50",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_unlock",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276688854,
      "name": "nvdimm_request_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
struct key * nvdimm_request_key(struct nvdimm * nvdimm)
```

```json
{
  "name": "nvdimm_request_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586275088,
      "name": "nvdimm_request_key",
      "external": false,
      "loc": "drivers/nvdimm/security.c:50",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_unlock",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586275088,
      "name": "nvdimm_request_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
struct key * nvdimm_request_key(struct nvdimm * nvdimm)
```

```json
{
  "name": "nvdimm_request_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586093456,
      "name": "nvdimm_request_key",
      "external": false,
      "loc": "drivers/nvdimm/security.c:50",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_unlock",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586093456,
      "name": "nvdimm_request_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
struct key * nvdimm_request_key(struct nvdimm * nvdimm)
```

```json
{
  "name": "nvdimm_request_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586532576,
      "name": "nvdimm_request_key",
      "external": false,
      "loc": "drivers/nvdimm/security.c:50",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_unlock",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586532576,
      "name": "nvdimm_request_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
struct key * nvdimm_request_key(struct nvdimm * nvdimm)
```

```json
{
  "name": "nvdimm_request_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586644304,
      "name": "nvdimm_request_key",
      "external": false,
      "loc": "drivers/nvdimm/security.c:50",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_unlock",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586644304,
      "name": "nvdimm_request_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
struct key * nvdimm_request_key(struct nvdimm * nvdimm)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct key * nvdimm_request_key(struct nvdimm * nvdimm)
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
