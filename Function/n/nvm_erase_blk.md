# Function: <code>nvm_erase_blk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int nvm_erase_blk(struct nvm_dev * dev, struct nvm_block * blk)
```

```json
{
  "name": "nvm_erase_blk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584360832,
      "name": "nvm_erase_blk",
      "external": true,
      "loc": "drivers/lightnvm/core.c:207",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584360832,
      "name": "nvm_erase_blk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int nvm_erase_blk(struct nvm_dev * dev, struct nvm_block * blk)
```

```json
{
  "name": "nvm_erase_blk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584694976,
      "name": "nvm_erase_blk",
      "external": true,
      "loc": "drivers/lightnvm/core.c:205",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584694976,
      "name": "nvm_erase_blk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int nvm_erase_blk(struct nvm_tgt_dev * tgt_dev, struct ppa_addr * p, int flags)
```

```json
{
  "name": "nvm_erase_blk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584881472,
      "name": "nvm_erase_blk",
      "external": true,
      "loc": "drivers/lightnvm/core.c:269",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584881472,
      "name": "nvm_erase_blk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
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
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct nvm_tgt_dev * tgt_dev</code>
</li>
<li>
<b>Param added. </b>
<code>struct ppa_addr * p</code>
</li>
<li>
<b>Param added. </b>
<code>int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>struct nvm_dev * dev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct nvm_block * blk</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int nvm_erase_blk(struct nvm_tgt_dev * tgt_dev, struct ppa_addr * p, int flags)
```
</details>
</li>
</ul>
