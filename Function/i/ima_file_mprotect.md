# Function: <code>ima_file_mprotect</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int ima_file_mprotect(struct vm_area_struct * vma, long unsigned int prot)
```

```json
{
  "name": "ima_file_mprotect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584178080,
      "name": "ima_file_mprotect",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:408",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:security_file_mprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584178080,
      "name": "ima_file_mprotect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
int ima_file_mprotect(struct vm_area_struct * vma, long unsigned int prot)
```

```json
{
  "name": "ima_file_mprotect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584297072,
      "name": "ima_file_mprotect",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:414",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:security_file_mprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584297072,
      "name": "ima_file_mprotect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
int ima_file_mprotect(struct vm_area_struct * vma, long unsigned int prot)
```

```json
{
  "name": "ima_file_mprotect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584331056,
      "name": "ima_file_mprotect",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:414",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:security_file_mprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584331056,
      "name": "ima_file_mprotect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
int ima_file_mprotect(struct vm_area_struct * vma, long unsigned int prot)
```

```json
{
  "name": "ima_file_mprotect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584718768,
      "name": "ima_file_mprotect",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:431",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:security_file_mprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584718768,
      "name": "ima_file_mprotect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 378
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
int ima_file_mprotect(struct vm_area_struct * vma, long unsigned int prot)
```

```json
{
  "name": "ima_file_mprotect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585393648,
      "name": "ima_file_mprotect",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:433",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:security_file_mprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585393648,
      "name": "ima_file_mprotect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 480
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
int ima_file_mprotect(struct vm_area_struct * vma, long unsigned int prot)
```

```json
{
  "name": "ima_file_mprotect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586146464,
      "name": "ima_file_mprotect",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:438",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:security_file_mprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586146464,
      "name": "ima_file_mprotect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 478
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
int ima_file_mprotect(struct vm_area_struct * vma, long unsigned int prot)
```

```json
{
  "name": "ima_file_mprotect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586384560,
      "name": "ima_file_mprotect",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:454",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:security_file_mprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586384560,
      "name": "ima_file_mprotect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
int ima_file_mprotect(struct vm_area_struct * vma, long unsigned int prot)
```

```json
{
  "name": "ima_file_mprotect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586649408,
      "name": "ima_file_mprotect",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:468",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/security.c:security_file_mprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586649408,
      "name": "ima_file_mprotect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 590
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int ima_file_mprotect(struct vm_area_struct * vma, long unsigned int prot)
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
