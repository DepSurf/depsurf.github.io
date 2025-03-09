# Function: <code>sgx_encl_release</code>

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
void sgx_encl_release(struct kref * ref)
```

```json
{
  "name": "sgx_encl_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579262160,
      "name": "sgx_encl_release",
      "external": true,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:399",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_release",
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_release",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_free",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579262160,
      "name": "sgx_encl_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 434
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
void sgx_encl_release(struct kref * ref)
```

```json
{
  "name": "sgx_encl_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579267072,
      "name": "sgx_encl_release",
      "external": true,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:391",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_release",
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_release",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_free",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579267072,
      "name": "sgx_encl_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 434
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
void sgx_encl_release(struct kref * ref)
```

```json
{
  "name": "sgx_encl_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579308864,
      "name": "sgx_encl_release",
      "external": true,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:432",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_release",
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_release",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_free",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579308864,
      "name": "sgx_encl_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 439
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
void sgx_encl_release(struct kref * ref)
```

```json
{
  "name": "sgx_encl_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579366048,
      "name": "sgx_encl_release",
      "external": true,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:533",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_release",
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_release",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_free",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579366048,
      "name": "sgx_encl_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 453
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
void sgx_encl_release(struct kref * ref)
```

```json
{
  "name": "sgx_encl_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579439040,
      "name": "sgx_encl_release",
      "external": true,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:680",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_release",
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_release",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_free",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579439040,
      "name": "sgx_encl_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 761
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
void sgx_encl_release(struct kref * ref)
```

```json
{
  "name": "sgx_encl_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579451136,
      "name": "sgx_encl_release",
      "external": true,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:680",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_release",
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_release",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_free",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579451136,
      "name": "sgx_encl_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 759
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
void sgx_encl_release(struct kref * ref)
```

```json
{
  "name": "sgx_encl_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579481056,
      "name": "sgx_encl_release",
      "external": true,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:700",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_release",
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_release",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_free",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579481056,
      "name": "sgx_encl_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 759
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
void sgx_encl_release(struct kref * ref)
```
</details>
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
