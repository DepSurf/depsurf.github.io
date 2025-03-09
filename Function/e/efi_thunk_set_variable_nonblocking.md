# Function: <code>efi_thunk_set_variable_nonblocking</code>

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
efi_status_t efi_thunk_set_variable_nonblocking(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "efi_thunk_set_variable_nonblocking",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579425808,
      "name": "efi_thunk_set_variable_nonblocking",
      "external": false,
      "loc": "arch/x86/platform/efi/efi_64.c:835",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579425808,
      "name": "efi_thunk_set_variable_nonblocking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 718
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
efi_status_t efi_thunk_set_variable_nonblocking(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "efi_thunk_set_variable_nonblocking",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_thunk_set_variable_nonblocking",
      "external": false,
      "loc": "arch/x86/platform/efi/efi_64.c:838",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579441856,
      "name": "efi_thunk_set_variable_nonblocking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 703
    },
    {
      "addr": 18446744071579447266,
      "name": "efi_thunk_set_variable_nonblocking.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
efi_status_t efi_thunk_set_variable_nonblocking(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "efi_thunk_set_variable_nonblocking",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579445360,
      "name": "efi_thunk_set_variable_nonblocking",
      "external": false,
      "loc": "arch/x86/platform/efi/efi_64.c:849",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579445360,
      "name": "efi_thunk_set_variable_nonblocking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 820
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
efi_status_t efi_thunk_set_variable_nonblocking(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "efi_thunk_set_variable_nonblocking",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579468832,
      "name": "efi_thunk_set_variable_nonblocking",
      "external": false,
      "loc": "arch/x86/platform/efi/efi_64.c:662",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579468832,
      "name": "efi_thunk_set_variable_nonblocking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 968
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
efi_status_t efi_thunk_set_variable_nonblocking(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "efi_thunk_set_variable_nonblocking",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579465104,
      "name": "efi_thunk_set_variable_nonblocking",
      "external": false,
      "loc": "arch/x86/platform/efi/efi_64.c:634",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579465104,
      "name": "efi_thunk_set_variable_nonblocking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 938
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
efi_status_t efi_thunk_set_variable_nonblocking(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "efi_thunk_set_variable_nonblocking",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579467248,
      "name": "efi_thunk_set_variable_nonblocking",
      "external": false,
      "loc": "arch/x86/platform/efi/efi_64.c:637",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579467248,
      "name": "efi_thunk_set_variable_nonblocking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 909
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
efi_status_t efi_thunk_set_variable_nonblocking(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "efi_thunk_set_variable_nonblocking",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579532736,
      "name": "efi_thunk_set_variable_nonblocking",
      "external": false,
      "loc": "arch/x86/platform/efi/efi_64.c:637",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579532736,
      "name": "efi_thunk_set_variable_nonblocking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 909
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
efi_status_t efi_thunk_set_variable_nonblocking(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "efi_thunk_set_variable_nonblocking",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579620032,
      "name": "efi_thunk_set_variable_nonblocking",
      "external": false,
      "loc": "arch/x86/platform/efi/efi_64.c:638",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579620032,
      "name": "efi_thunk_set_variable_nonblocking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1008
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
efi_status_t efi_thunk_set_variable_nonblocking(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "efi_thunk_set_variable_nonblocking",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579732192,
      "name": "efi_thunk_set_variable_nonblocking",
      "external": false,
      "loc": "arch/x86/platform/efi/efi_64.c:646",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579732192,
      "name": "efi_thunk_set_variable_nonblocking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1008
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
efi_status_t efi_thunk_set_variable_nonblocking(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "efi_thunk_set_variable_nonblocking",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579778672,
      "name": "efi_thunk_set_variable_nonblocking",
      "external": false,
      "loc": "arch/x86/platform/efi/efi_64.c:652",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579778672,
      "name": "efi_thunk_set_variable_nonblocking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1008
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
efi_status_t efi_thunk_set_variable_nonblocking(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "efi_thunk_set_variable_nonblocking",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579813360,
      "name": "efi_thunk_set_variable_nonblocking",
      "external": false,
      "loc": "arch/x86/platform/efi/efi_64.c:667",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579813360,
      "name": "efi_thunk_set_variable_nonblocking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 814
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
efi_status_t efi_thunk_set_variable_nonblocking(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "efi_thunk_set_variable_nonblocking",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579441200,
      "name": "efi_thunk_set_variable_nonblocking",
      "external": false,
      "loc": "arch/x86/platform/efi/efi_64.c:849",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579441200,
      "name": "efi_thunk_set_variable_nonblocking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 820
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
efi_status_t efi_thunk_set_variable_nonblocking(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "efi_thunk_set_variable_nonblocking",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579370224,
      "name": "efi_thunk_set_variable_nonblocking",
      "external": false,
      "loc": "arch/x86/platform/efi/efi_64.c:849",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579370224,
      "name": "efi_thunk_set_variable_nonblocking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 800
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
efi_status_t efi_thunk_set_variable_nonblocking(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "efi_thunk_set_variable_nonblocking",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579441120,
      "name": "efi_thunk_set_variable_nonblocking",
      "external": false,
      "loc": "arch/x86/platform/efi/efi_64.c:849",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579441120,
      "name": "efi_thunk_set_variable_nonblocking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 820
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
efi_status_t efi_thunk_set_variable_nonblocking(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```

```json
{
  "name": "efi_thunk_set_variable_nonblocking",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579450448,
      "name": "efi_thunk_set_variable_nonblocking",
      "external": false,
      "loc": "arch/x86/platform/efi/efi_64.c:849",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579450448,
      "name": "efi_thunk_set_variable_nonblocking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 850
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
efi_status_t efi_thunk_set_variable_nonblocking(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
efi_status_t efi_thunk_set_variable_nonblocking(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
efi_status_t efi_thunk_set_variable_nonblocking(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
efi_status_t efi_thunk_set_variable_nonblocking(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
efi_status_t efi_thunk_set_variable_nonblocking(efi_char16_t * name, efi_guid_t * vendor, u32 attr, long unsigned int data_size, void * data)
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
