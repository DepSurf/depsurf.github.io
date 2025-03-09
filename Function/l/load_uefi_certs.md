# Function: <code>load_uefi_certs</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int load_uefi_certs()
```

```json
{
  "name": "load_uefi_certs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595270338,
      "name": "load_uefi_certs",
      "external": false,
      "loc": "kernel/modsign_uefi.c:61",
      "file": "kernel/modsign_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595270338,
      "name": "load_uefi_certs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 673
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
int load_uefi_certs()
```

```json
{
  "name": "load_uefi_certs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595516110,
      "name": "load_uefi_certs",
      "external": false,
      "loc": "kernel/modsign_uefi.c:61",
      "file": "kernel/modsign_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595516110,
      "name": "load_uefi_certs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 673
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
int load_uefi_certs()
```

```json
{
  "name": "load_uefi_certs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596464815,
      "name": "load_uefi_certs",
      "external": false,
      "loc": "certs/load_uefi.c:140",
      "file": "certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596464815,
      "name": "load_uefi_certs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 526
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
int load_uefi_certs()
```

```json
{
  "name": "load_uefi_certs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602791653,
      "name": "load_uefi_certs",
      "external": false,
      "loc": "certs/load_uefi.c:140",
      "file": "certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602791653,
      "name": "load_uefi_certs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 526
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
int load_uefi_certs()
```

```json
{
  "name": "load_uefi_certs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602965256,
      "name": "load_uefi_certs",
      "external": false,
      "loc": "certs/load_uefi.c:149",
      "file": "certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602965256,
      "name": "load_uefi_certs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 578
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision ❓</summary>

```c
int load_uefi_certs()
```

```json
{
  "name": "load_uefi_certs",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604762863,
      "name": "load_uefi_certs",
      "external": false,
      "loc": "certs/load_uefi.c:140",
      "file": "certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604861214,
      "name": "load_uefi_certs",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:150",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604762863,
      "name": "load_uefi_certs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 528
    },
    {
      "addr": 18446744071604861214,
      "name": "load_uefi_certs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 578
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
int load_uefi_certs()
```

```json
{
  "name": "load_uefi_certs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604966938,
      "name": "load_uefi_certs",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:150",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604966938,
      "name": "load_uefi_certs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 583
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
int load_uefi_certs()
```

```json
{
  "name": "load_uefi_certs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605002454,
      "name": "load_uefi_certs",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:80",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605002454,
      "name": "load_uefi_certs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 737
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
int load_uefi_certs()
```

```json
{
  "name": "load_uefi_certs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609282785,
      "name": "load_uefi_certs",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:75",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609282785,
      "name": "load_uefi_certs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 662
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
int load_uefi_certs()
```

```json
{
  "name": "load_uefi_certs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612352080,
      "name": "load_uefi_certs",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:134",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612352080,
      "name": "load_uefi_certs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 486
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
int load_uefi_certs()
```

```json
{
  "name": "load_uefi_certs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614493326,
      "name": "load_uefi_certs",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:149",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614493326,
      "name": "load_uefi_certs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 566
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
int load_uefi_certs()
```

```json
{
  "name": "load_uefi_certs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615440509,
      "name": "load_uefi_certs",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:149",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615440509,
      "name": "load_uefi_certs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 560
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
int load_uefi_certs()
```

```json
{
  "name": "load_uefi_certs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617238696,
      "name": "load_uefi_certs",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:176",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617238696,
      "name": "load_uefi_certs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 617
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
int load_uefi_certs()
```

```json
{
  "name": "load_uefi_certs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627952784,
      "name": "load_uefi_certs",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:177",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627952784,
      "name": "load_uefi_certs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 695
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
int load_uefi_certs()
```

```json
{
  "name": "load_uefi_certs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619716080,
      "name": "load_uefi_certs",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:177",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619716080,
      "name": "load_uefi_certs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 695
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
int load_uefi_certs()
```

```json
{
  "name": "load_uefi_certs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071622023344,
      "name": "load_uefi_certs",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:177",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071622023344,
      "name": "load_uefi_certs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 695
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
int load_uefi_certs()
```

```json
{
  "name": "load_uefi_certs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336511046836,
      "name": "load_uefi_certs",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:80",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336511046836,
      "name": "load_uefi_certs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 724
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
int load_uefi_certs()
```

```json
{
  "name": "load_uefi_certs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243528488,
      "name": "load_uefi_certs",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:80",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3243528488,
      "name": "load_uefi_certs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 736
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int load_uefi_certs()
```

```json
{
  "name": "load_uefi_certs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604907914,
      "name": "load_uefi_certs",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:80",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604907914,
      "name": "load_uefi_certs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 737
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
int load_uefi_certs()
```

```json
{
  "name": "load_uefi_certs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604876966,
      "name": "load_uefi_certs",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:80",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604876966,
      "name": "load_uefi_certs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 737
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
int load_uefi_certs()
```

```json
{
  "name": "load_uefi_certs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604985086,
      "name": "load_uefi_certs",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:80",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604985086,
      "name": "load_uefi_certs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 737
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
int load_uefi_certs()
```

```json
{
  "name": "load_uefi_certs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605006624,
      "name": "load_uefi_certs",
      "external": false,
      "loc": "security/integrity/platform_certs/load_uefi.c:80",
      "file": "security/integrity/platform_certs/load_uefi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605006624,
      "name": "load_uefi_certs",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 737
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
int load_uefi_certs()
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int load_uefi_certs()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int load_uefi_certs()
```
</details>
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
