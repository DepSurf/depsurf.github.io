# Function: <code>security_overwrite</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "security_overwrite",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586587908,
      "name": "security_overwrite",
      "external": false,
      "loc": "drivers/nvdimm/security.c:367",
      "file": "drivers/nvdimm/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int security_overwrite(struct nvdimm * nvdimm, unsigned int keyid)
```

```json
{
  "name": "security_overwrite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587370672,
      "name": "security_overwrite",
      "external": false,
      "loc": "drivers/nvdimm/security.c:367",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587370672,
      "name": "security_overwrite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
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
int security_overwrite(struct nvdimm * nvdimm, unsigned int keyid)
```

```json
{
  "name": "security_overwrite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587431360,
      "name": "security_overwrite",
      "external": false,
      "loc": "drivers/nvdimm/security.c:367",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587431360,
      "name": "security_overwrite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
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
int security_overwrite(struct nvdimm * nvdimm, unsigned int keyid)
```

```json
{
  "name": "security_overwrite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587313200,
      "name": "security_overwrite",
      "external": false,
      "loc": "drivers/nvdimm/security.c:367",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587313200,
      "name": "security_overwrite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 475
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
int security_overwrite(struct nvdimm * nvdimm, unsigned int keyid)
```

```json
{
  "name": "security_overwrite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587880032,
      "name": "security_overwrite",
      "external": false,
      "loc": "drivers/nvdimm/security.c:367",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587880032,
      "name": "security_overwrite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 469
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
int security_overwrite(struct nvdimm * nvdimm, unsigned int keyid)
```

```json
{
  "name": "security_overwrite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589230384,
      "name": "security_overwrite",
      "external": false,
      "loc": "drivers/nvdimm/security.c:367",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589230384,
      "name": "security_overwrite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
int security_overwrite(struct nvdimm * nvdimm, unsigned int keyid)
```

```json
{
  "name": "security_overwrite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590787456,
      "name": "security_overwrite",
      "external": false,
      "loc": "drivers/nvdimm/security.c:390",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590787456,
      "name": "security_overwrite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 413
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
int security_overwrite(struct nvdimm * nvdimm, unsigned int keyid)
```

```json
{
  "name": "security_overwrite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591128944,
      "name": "security_overwrite",
      "external": false,
      "loc": "drivers/nvdimm/security.c:390",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591128944,
      "name": "security_overwrite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
int security_overwrite(struct nvdimm * nvdimm, unsigned int keyid)
```

```json
{
  "name": "security_overwrite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591474624,
      "name": "security_overwrite",
      "external": false,
      "loc": "drivers/nvdimm/security.c:390",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591474624,
      "name": "security_overwrite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "security_overwrite",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499471052,
      "name": "security_overwrite",
      "external": false,
      "loc": "drivers/nvdimm/security.c:367",
      "file": "drivers/nvdimm/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "security_overwrite",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055292747620,
      "name": "security_overwrite",
      "external": false,
      "loc": "drivers/nvdimm/security.c:367",
      "file": "drivers/nvdimm/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "security_overwrite",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276690942,
      "name": "security_overwrite",
      "external": false,
      "loc": "drivers/nvdimm/security.c:367",
      "file": "drivers/nvdimm/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "security_overwrite",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586278388,
      "name": "security_overwrite",
      "external": false,
      "loc": "drivers/nvdimm/security.c:367",
      "file": "drivers/nvdimm/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "security_overwrite",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586096756,
      "name": "security_overwrite",
      "external": false,
      "loc": "drivers/nvdimm/security.c:367",
      "file": "drivers/nvdimm/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "security_overwrite",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586535876,
      "name": "security_overwrite",
      "external": false,
      "loc": "drivers/nvdimm/security.c:367",
      "file": "drivers/nvdimm/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "security_overwrite",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586647604,
      "name": "security_overwrite",
      "external": false,
      "loc": "drivers/nvdimm/security.c:367",
      "file": "drivers/nvdimm/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_security_store"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int security_overwrite(struct nvdimm * nvdimm, unsigned int keyid)
```
</details>
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
