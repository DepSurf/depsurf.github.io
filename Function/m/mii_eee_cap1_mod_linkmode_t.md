# Function: <code>mii_eee_cap1_mod_linkmode_t</code>

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
void mii_eee_cap1_mod_linkmode_t(long unsigned int * adv, u32 val)
```

```json
{
  "name": "mii_eee_cap1_mod_linkmode_t",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591649688,
      "name": "mii_eee_cap1_mod_linkmode_t",
      "external": false,
      "loc": "include/linux/mdio.h:425",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active"
      ],
      "caller_func": [
        "drivers/net/phy/phy-c45.c:genphy_c45_read_eee_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_eee_adv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591645216,
      "name": "mii_eee_cap1_mod_linkmode_t",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
void mii_eee_cap1_mod_linkmode_t(long unsigned int * adv, u32 val)
```

```json
{
  "name": "mii_eee_cap1_mod_linkmode_t",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592390936,
      "name": "mii_eee_cap1_mod_linkmode_t",
      "external": false,
      "loc": "include/linux/mdio.h:426",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active"
      ],
      "caller_func": [
        "drivers/net/phy/phy-c45.c:genphy_c45_read_eee_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_eee_adv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592386336,
      "name": "mii_eee_cap1_mod_linkmode_t",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
void mii_eee_cap1_mod_linkmode_t(long unsigned int * adv, u32 val)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
