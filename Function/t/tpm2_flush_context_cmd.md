# Function: <code>tpm2_flush_context_cmd</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm2_flush_context_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584769269,
      "name": "tpm2_flush_context_cmd",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:609",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void tpm2_flush_context_cmd(struct tpm_chip * chip, u32 handle, unsigned int flags)
```

```json
{
  "name": "tpm2_flush_context_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584849344,
      "name": "tpm2_flush_context_cmd",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:411",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_flush_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_flush_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_del_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584849344,
      "name": "tpm2_flush_context_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
void tpm2_flush_context_cmd(struct tpm_chip * chip, u32 handle, unsigned int flags)
```

```json
{
  "name": "tpm2_flush_context_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585269264,
      "name": "tpm2_flush_context_cmd",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:411",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_flush_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_flush_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_del_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585269264,
      "name": "tpm2_flush_context_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
void tpm2_flush_context_cmd(struct tpm_chip * chip, u32 handle, unsigned int flags)
```

```json
{
  "name": "tpm2_flush_context_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585506272,
      "name": "tpm2_flush_context_cmd",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:408",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_flush_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_flush_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_del_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585506272,
      "name": "tpm2_flush_context_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void tpm2_flush_context_cmd(struct tpm_chip * chip, u32 handle, unsigned int flags)
```

```json
{
  "name": "tpm2_flush_context_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585629024,
      "name": "tpm2_flush_context_cmd",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:350",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_flush_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_flush_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_del_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585629024,
      "name": "tpm2_flush_context_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
    }
  ]
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
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void tpm2_flush_context_cmd(struct tpm_chip * chip, u32 handle, unsigned int flags)
```
</details>
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void tpm2_flush_context_cmd(struct tpm_chip * chip, u32 handle, unsigned int flags)
```
</details>
</li>
</ul>
