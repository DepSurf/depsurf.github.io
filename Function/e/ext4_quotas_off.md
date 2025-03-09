# Function: <code>ext4_quotas_off</code>

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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ext4_quotas_off(struct super_block * sb, int type)
```

```json
{
  "name": "ext4_quotas_off",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585144481,
      "name": "ext4_quotas_off",
      "external": false,
      "loc": "fs/ext4/super.c:1173",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_put_super"
      ],
      "caller_func": [
        "fs/ext4/super.c:__ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585092864,
      "name": "ext4_quotas_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ext4_quotas_off(struct super_block * sb, int type)
```

```json
{
  "name": "ext4_quotas_off",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585377345,
      "name": "ext4_quotas_off",
      "external": false,
      "loc": "fs/ext4/super.c:1194",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_put_super"
      ],
      "caller_func": [
        "fs/ext4/super.c:__ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585324624,
      "name": "ext4_quotas_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
void ext4_quotas_off(struct super_block * sb, int type)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
