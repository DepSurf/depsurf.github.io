# Function: <code>load_moklist_certs</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int load_moklist_certs()
```

```json
{
  "name": "load_moklist_certs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612351758,
      "name": "load_moklist_certs",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:81",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612351758,
      "name": "load_moklist_certs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 322
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
int load_moklist_certs(const bool load_db)
```

```json
{
  "name": "load_moklist_certs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614492911,
      "name": "load_moklist_certs",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:82",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614492911,
      "name": "load_moklist_certs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 415
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
int load_moklist_certs(const bool load_db)
```

```json
{
  "name": "load_moklist_certs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615440097,
      "name": "load_moklist_certs",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:82",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615440097,
      "name": "load_moklist_certs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 412
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
int load_moklist_certs(const bool load_db)
```

```json
{
  "name": "load_moklist_certs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617238262,
      "name": "load_moklist_certs",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:109",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617238262,
      "name": "load_moklist_certs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 434
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
int load_moklist_certs(const bool load_db)
```

```json
{
  "name": "load_moklist_certs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627952304,
      "name": "load_moklist_certs",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:110",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627952304,
      "name": "load_moklist_certs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 455
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
int load_moklist_certs(const bool load_db)
```

```json
{
  "name": "load_moklist_certs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619715600,
      "name": "load_moklist_certs",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:110",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619715600,
      "name": "load_moklist_certs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 461
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
int load_moklist_certs(const bool load_db)
```

```json
{
  "name": "load_moklist_certs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071622022864,
      "name": "load_moklist_certs",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:110",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071622022864,
      "name": "load_moklist_certs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 461
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int load_moklist_certs()
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const bool load_db</code>
</li>
</ul>
</details>
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
