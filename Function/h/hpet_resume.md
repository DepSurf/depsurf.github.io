# Function: <code>hpet_resume</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int hpet_resume(struct clock_event_device * evt, int timer)
```

```json
{
  "name": "hpet_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579247200,
      "name": "hpet_resume",
      "external": false,
      "loc": "arch/x86/kernel/hpet.c:348",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_legacy_resume",
        "arch/x86/kernel/hpet.c:hpet_msi_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579247200,
      "name": "hpet_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int hpet_resume(struct clock_event_device * evt, int timer)
```

```json
{
  "name": "hpet_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579246736,
      "name": "hpet_resume",
      "external": false,
      "loc": "arch/x86/kernel/hpet.c:348",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_msi_resume",
        "arch/x86/kernel/hpet.c:hpet_legacy_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579246736,
      "name": "hpet_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hpet_resume",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579259178,
      "name": "hpet_resume",
      "external": false,
      "loc": "arch/x86/kernel/hpet.c:348",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_msi_resume",
        "arch/x86/kernel/hpet.c:hpet_legacy_resume"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hpet_resume",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579257349,
      "name": "hpet_resume",
      "external": false,
      "loc": "arch/x86/kernel/hpet.c:348",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_legacy_resume"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hpet_resume",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579274134,
      "name": "hpet_resume",
      "external": false,
      "loc": "arch/x86/kernel/hpet.c:348",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_legacy_resume"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hpet_resume",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579285301,
      "name": "hpet_resume",
      "external": false,
      "loc": "arch/x86/kernel/hpet.c:349",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_legacy_resume"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hpet_resume",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579309045,
      "name": "hpet_resume",
      "external": false,
      "loc": "arch/x86/kernel/hpet.c:345",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_legacy_resume"
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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
int hpet_resume(struct clock_event_device * evt, int timer)
```
</details>
</li>
</ul>
