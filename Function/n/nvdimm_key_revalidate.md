# Function: <code>nvdimm_key_revalidate</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nvdimm_key_revalidate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586201531,
      "name": "nvdimm_key_revalidate",
      "external": false,
      "loc": "drivers/nvdimm/security.c:108",
      "file": "drivers/nvdimm/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nvdimm_key_revalidate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586438375,
      "name": "nvdimm_key_revalidate",
      "external": false,
      "loc": "drivers/nvdimm/security.c:139",
      "file": "drivers/nvdimm/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nvdimm_key_revalidate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586585444,
      "name": "nvdimm_key_revalidate",
      "external": false,
      "loc": "drivers/nvdimm/security.c:139",
      "file": "drivers/nvdimm/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
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
int nvdimm_key_revalidate(struct nvdimm * nvdimm)
```

```json
{
  "name": "nvdimm_key_revalidate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587371104,
      "name": "nvdimm_key_revalidate",
      "external": false,
      "loc": "drivers/nvdimm/security.c:139",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:__nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587371104,
      "name": "nvdimm_key_revalidate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
int nvdimm_key_revalidate(struct nvdimm * nvdimm)
```

```json
{
  "name": "nvdimm_key_revalidate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587431792,
      "name": "nvdimm_key_revalidate",
      "external": false,
      "loc": "drivers/nvdimm/security.c:139",
      "file": "drivers/nvdimm/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/security.c:__nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587431792,
      "name": "nvdimm_key_revalidate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
  "name": "nvdimm_key_revalidate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587314532,
      "name": "nvdimm_key_revalidate",
      "external": false,
      "loc": "drivers/nvdimm/security.c:139",
      "file": "drivers/nvdimm/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:__nvdimm_security_unlock"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nvdimm_key_revalidate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587881392,
      "name": "nvdimm_key_revalidate",
      "external": false,
      "loc": "drivers/nvdimm/security.c:139",
      "file": "drivers/nvdimm/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:__nvdimm_security_unlock"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nvdimm_key_revalidate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589232560,
      "name": "nvdimm_key_revalidate",
      "external": false,
      "loc": "drivers/nvdimm/security.c:139",
      "file": "drivers/nvdimm/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:__nvdimm_security_unlock"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nvdimm_key_revalidate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590789481,
      "name": "nvdimm_key_revalidate",
      "external": false,
      "loc": "drivers/nvdimm/security.c:139",
      "file": "drivers/nvdimm/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:__nvdimm_security_unlock"
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
  "name": "nvdimm_key_revalidate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591130985,
      "name": "nvdimm_key_revalidate",
      "external": false,
      "loc": "drivers/nvdimm/security.c:139",
      "file": "drivers/nvdimm/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:__nvdimm_security_unlock"
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
  "name": "nvdimm_key_revalidate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591476665,
      "name": "nvdimm_key_revalidate",
      "external": false,
      "loc": "drivers/nvdimm/security.c:139",
      "file": "drivers/nvdimm/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:__nvdimm_security_unlock"
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
  "name": "nvdimm_key_revalidate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499469040,
      "name": "nvdimm_key_revalidate",
      "external": false,
      "loc": "drivers/nvdimm/security.c:139",
      "file": "drivers/nvdimm/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
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
  "name": "nvdimm_key_revalidate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055292745664,
      "name": "nvdimm_key_revalidate",
      "external": false,
      "loc": "drivers/nvdimm/security.c:139",
      "file": "drivers/nvdimm/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
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
  "name": "nvdimm_key_revalidate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276689666,
      "name": "nvdimm_key_revalidate",
      "external": false,
      "loc": "drivers/nvdimm/security.c:139",
      "file": "drivers/nvdimm/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
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
  "name": "nvdimm_key_revalidate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586275924,
      "name": "nvdimm_key_revalidate",
      "external": false,
      "loc": "drivers/nvdimm/security.c:139",
      "file": "drivers/nvdimm/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
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
  "name": "nvdimm_key_revalidate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586094292,
      "name": "nvdimm_key_revalidate",
      "external": false,
      "loc": "drivers/nvdimm/security.c:139",
      "file": "drivers/nvdimm/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
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
  "name": "nvdimm_key_revalidate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586533412,
      "name": "nvdimm_key_revalidate",
      "external": false,
      "loc": "drivers/nvdimm/security.c:139",
      "file": "drivers/nvdimm/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
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
  "name": "nvdimm_key_revalidate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586645140,
      "name": "nvdimm_key_revalidate",
      "external": false,
      "loc": "drivers/nvdimm/security.c:139",
      "file": "drivers/nvdimm/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
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
int nvdimm_key_revalidate(struct nvdimm * nvdimm)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int nvdimm_key_revalidate(struct nvdimm * nvdimm)
```
</details>
</li>
</ul>
