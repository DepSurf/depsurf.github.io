# Function: <code>get_sb_mode</code>

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
  "name": "get_sb_mode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579339825,
      "name": "get_sb_mode",
      "external": false,
      "loc": "arch/x86/kernel/ima_arch.c:10",
      "file": "arch/x86/kernel/ima_arch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ima_arch.c:arch_ima_get_secureboot"
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
  "name": "get_sb_mode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579355041,
      "name": "get_sb_mode",
      "external": false,
      "loc": "arch/x86/kernel/ima_arch.c:11",
      "file": "arch/x86/kernel/ima_arch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ima_arch.c:arch_ima_get_secureboot"
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
  "name": "get_sb_mode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579359377,
      "name": "get_sb_mode",
      "external": false,
      "loc": "arch/x86/kernel/ima_arch.c:11",
      "file": "arch/x86/kernel/ima_arch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ima_arch.c:arch_ima_get_secureboot"
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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
enum efi_secureboot_mode get_sb_mode()
```

```json
{
  "name": "get_sb_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_sb_mode",
      "external": false,
      "loc": "security/integrity/ima/ima_efi.c:14",
      "file": "security/integrity/ima/ima_efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_efi.c:arch_get_ima_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585433632,
      "name": "get_sb_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 18446744071594092295,
      "name": "get_sb_mode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
enum efi_secureboot_mode get_sb_mode()
```

```json
{
  "name": "get_sb_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586190688,
      "name": "get_sb_mode",
      "external": false,
      "loc": "security/integrity/ima/ima_efi.c:14",
      "file": "security/integrity/ima/ima_efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_efi.c:arch_get_ima_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586190688,
      "name": "get_sb_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
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
enum efi_secureboot_mode get_sb_mode()
```

```json
{
  "name": "get_sb_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586428416,
      "name": "get_sb_mode",
      "external": false,
      "loc": "security/integrity/ima/ima_efi.c:14",
      "file": "security/integrity/ima/ima_efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_efi.c:arch_get_ima_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586428416,
      "name": "get_sb_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
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
enum efi_secureboot_mode get_sb_mode()
```

```json
{
  "name": "get_sb_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586693568,
      "name": "get_sb_mode",
      "external": false,
      "loc": "security/integrity/ima/ima_efi.c:14",
      "file": "security/integrity/ima/ima_efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_efi.c:arch_get_ima_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586693568,
      "name": "get_sb_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_sb_mode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579355281,
      "name": "get_sb_mode",
      "external": false,
      "loc": "arch/x86/kernel/ima_arch.c:11",
      "file": "arch/x86/kernel/ima_arch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ima_arch.c:arch_ima_get_secureboot"
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
  "name": "get_sb_mode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579287553,
      "name": "get_sb_mode",
      "external": false,
      "loc": "arch/x86/kernel/ima_arch.c:11",
      "file": "arch/x86/kernel/ima_arch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ima_arch.c:arch_ima_get_secureboot"
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
  "name": "get_sb_mode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579355201,
      "name": "get_sb_mode",
      "external": false,
      "loc": "arch/x86/kernel/ima_arch.c:11",
      "file": "arch/x86/kernel/ima_arch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ima_arch.c:arch_ima_get_secureboot"
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
  "name": "get_sb_mode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579363649,
      "name": "get_sb_mode",
      "external": false,
      "loc": "arch/x86/kernel/ima_arch.c:11",
      "file": "arch/x86/kernel/ima_arch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ima_arch.c:arch_ima_get_secureboot"
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
enum efi_secureboot_mode get_sb_mode()
```
</details>
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
