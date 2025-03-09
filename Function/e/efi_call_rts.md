# Function: <code>efi_call_rts</code>

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
void efi_call_rts(struct work_struct * work)
```

```json
{
  "name": "efi_call_rts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587718800,
      "name": "efi_call_rts",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:166",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587718800,
      "name": "efi_call_rts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1706
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void efi_call_rts(struct work_struct * work)
```

```json
{
  "name": "efi_call_rts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_call_rts",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:178",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587997904,
      "name": "efi_call_rts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2290
    },
    {
      "addr": 18446744071588001852,
      "name": "efi_call_rts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void efi_call_rts(struct work_struct * work)
```

```json
{
  "name": "efi_call_rts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_call_rts",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:178",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588205424,
      "name": "efi_call_rts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2290
    },
    {
      "addr": 18446744071588209372,
      "name": "efi_call_rts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void efi_call_rts(struct work_struct * work)
```

```json
{
  "name": "efi_call_rts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_call_rts",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:178",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589072384,
      "name": "efi_call_rts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2246
    },
    {
      "addr": 18446744071589076396,
      "name": "efi_call_rts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void efi_call_rts(struct work_struct * work)
```

```json
{
  "name": "efi_call_rts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_call_rts",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:178",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589076112,
      "name": "efi_call_rts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1918
    },
    {
      "addr": 18446744071591611432,
      "name": "efi_call_rts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void efi_call_rts(struct work_struct * work)
```

```json
{
  "name": "efi_call_rts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_call_rts",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:178",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588962864,
      "name": "efi_call_rts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1743
    },
    {
      "addr": 18446744071591554646,
      "name": "efi_call_rts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void efi_call_rts(struct work_struct * work)
```

```json
{
  "name": "efi_call_rts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_call_rts",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:178",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589672400,
      "name": "efi_call_rts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1743
    },
    {
      "addr": 18446744071592674363,
      "name": "efi_call_rts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void efi_call_rts(struct work_struct * work)
```

```json
{
  "name": "efi_call_rts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_call_rts",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:178",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591176160,
      "name": "efi_call_rts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2180
    },
    {
      "addr": 18446744071594559599,
      "name": "efi_call_rts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void efi_call_rts(struct work_struct * work)
```

```json
{
  "name": "efi_call_rts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592899856,
      "name": "efi_call_rts",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:180",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592899856,
      "name": "efi_call_rts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1659
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void efi_call_rts(struct work_struct * work)
```

```json
{
  "name": "efi_call_rts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_call_rts",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:180",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593338400,
      "name": "efi_call_rts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1710
    },
    {
      "addr": 18446744071596847904,
      "name": "efi_call_rts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void efi_call_rts(struct work_struct * work)
```

```json
{
  "name": "efi_call_rts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_call_rts",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:216",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594093648,
      "name": "efi_call_rts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 852
    },
    {
      "addr": 18446744071597772853,
      "name": "efi_call_rts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
void efi_call_rts(struct work_struct * work)
```

```json
{
  "name": "efi_call_rts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501561080,
      "name": "efi_call_rts",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:178",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501561080,
      "name": "efi_call_rts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1132
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
void efi_call_rts(struct work_struct * work)
```

```json
{
  "name": "efi_call_rts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234069512,
      "name": "efi_call_rts",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:178",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3234069512,
      "name": "efi_call_rts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 948
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void efi_call_rts(struct work_struct * work)
```

```json
{
  "name": "efi_call_rts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_call_rts",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:178",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587819344,
      "name": "efi_call_rts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2290
    },
    {
      "addr": 18446744071587823292,
      "name": "efi_call_rts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void efi_call_rts(struct work_struct * work)
```

```json
{
  "name": "efi_call_rts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_call_rts",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:178",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587527248,
      "name": "efi_call_rts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2219
    },
    {
      "addr": 18446744071587531116,
      "name": "efi_call_rts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void efi_call_rts(struct work_struct * work)
```

```json
{
  "name": "efi_call_rts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_call_rts",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:178",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588159952,
      "name": "efi_call_rts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2290
    },
    {
      "addr": 18446744071588163900,
      "name": "efi_call_rts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void efi_call_rts(struct work_struct * work)
```

```json
{
  "name": "efi_call_rts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_call_rts",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:178",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588277360,
      "name": "efi_call_rts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2620
    },
    {
      "addr": 18446744071588281724,
      "name": "efi_call_rts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void efi_call_rts(struct work_struct * work)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void efi_call_rts(struct work_struct * work)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void efi_call_rts(struct work_struct * work)
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
