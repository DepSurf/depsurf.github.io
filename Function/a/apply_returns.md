# Function: <code>apply_returns</code>

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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void apply_returns(s32 * start, s32 * end)
```

```json
{
  "name": "apply_returns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apply_returns",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:538",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/module.c:module_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593824776,
      "name": "apply_returns.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 345
    },
    {
      "addr": 18446744071579163200,
      "name": "apply_returns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 630
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void apply_returns(s32 * start, s32 * end)
```

```json
{
  "name": "apply_returns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apply_returns",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:610",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/module.c:module_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595959348,
      "name": "apply_returns.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579215664,
      "name": "apply_returns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 876
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
void apply_returns(s32 * start, s32 * end)
```

```json
{
  "name": "apply_returns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apply_returns",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:719",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/module.c:module_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596476717,
      "name": "apply_returns.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579220960,
      "name": "apply_returns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1011
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
void apply_returns(s32 * start, s32 * end)
```

```json
{
  "name": "apply_returns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apply_returns",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:804",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/module.c:module_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597372502,
      "name": "apply_returns.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579250512,
      "name": "apply_returns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1002
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void apply_returns(s32 * start, s32 * end)
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
