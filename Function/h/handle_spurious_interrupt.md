# Function: <code>handle_spurious_interrupt</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void handle_spurious_interrupt(u8 vector)
```

```json
{
  "name": "handle_spurious_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "handle_spurious_interrupt",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:2145",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:__sysvec_spurious_apic_interrupt",
        "arch/x86/kernel/apic/apic.c:__spurious_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579299280,
      "name": "handle_spurious_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071591202781,
      "name": "handle_spurious_interrupt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
void handle_spurious_interrupt(u8 vector)
```

```json
{
  "name": "handle_spurious_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "handle_spurious_interrupt",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:2142",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:__sysvec_spurious_apic_interrupt",
        "arch/x86/kernel/apic/apic.c:__spurious_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579346896,
      "name": "handle_spurious_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071592073786,
      "name": "handle_spurious_interrupt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
void handle_spurious_interrupt(u8 vector)
```

```json
{
  "name": "handle_spurious_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "handle_spurious_interrupt",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:2150",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:__sysvec_spurious_apic_interrupt",
        "arch/x86/kernel/apic/apic.c:__spurious_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579408256,
      "name": "handle_spurious_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    },
    {
      "addr": 18446744071593840281,
      "name": "handle_spurious_interrupt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
void handle_spurious_interrupt(u8 vector)
```

```json
{
  "name": "handle_spurious_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579489968,
      "name": "handle_spurious_interrupt",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:2184",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:__sysvec_spurious_apic_interrupt",
        "arch/x86/kernel/apic/apic.c:__spurious_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579489968,
      "name": "handle_spurious_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
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
void handle_spurious_interrupt(u8 vector)
```

```json
{
  "name": "handle_spurious_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579502224,
      "name": "handle_spurious_interrupt",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:2187",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:__sysvec_spurious_apic_interrupt",
        "arch/x86/kernel/apic/apic.c:__spurious_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579502224,
      "name": "handle_spurious_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
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
void handle_spurious_interrupt(u8 vector)
```

```json
{
  "name": "handle_spurious_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579532240,
      "name": "handle_spurious_interrupt",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic.c:2125",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:__sysvec_spurious_apic_interrupt",
        "arch/x86/kernel/apic/apic.c:__spurious_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579532240,
      "name": "handle_spurious_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void handle_spurious_interrupt(u8 vector)
```
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
