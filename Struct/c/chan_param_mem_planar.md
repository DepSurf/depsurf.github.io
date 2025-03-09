# Struct: <code>chan_param_mem_planar</code>

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
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct chan_param_mem_planar {
    u32 xv;
    u32 yv;
    u32 xb;
    u32 yb;
    u32 res1;
    u32 nsb;
    u32 lnpb;
    u32 ubo_l;
    u32 ubo_h;
    u32 vbo_l;
    u32 vbo_h;
    u32 res2;
    u32 fw;
    u32 fh_l;
    u32 fh_h;
    u32 res3;
    u32 eba0;
    u32 eba1;
    u32 bpp;
    u32 sl;
    u32 pfs;
    u32 bam;
    u32 res4;
    u32 npb;
    u32 res5;
    u32 sat;
    u32 res6;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct chan_param_mem_planar {
    u32 xv;
    u32 yv;
    u32 xb;
    u32 yb;
    u32 res1;
    u32 nsb;
    u32 lnpb;
    u32 ubo_l;
    u32 ubo_h;
    u32 vbo_l;
    u32 vbo_h;
    u32 res2;
    u32 fw;
    u32 fh_l;
    u32 fh_h;
    u32 res3;
    u32 eba0;
    u32 eba1;
    u32 bpp;
    u32 sl;
    u32 pfs;
    u32 bam;
    u32 res4;
    u32 npb;
    u32 res5;
    u32 sat;
    u32 res6;
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
struct chan_param_mem_planar {
    u32 xv;
    u32 yv;
    u32 xb;
    u32 yb;
    u32 res1;
    u32 nsb;
    u32 lnpb;
    u32 ubo_l;
    u32 ubo_h;
    u32 vbo_l;
    u32 vbo_h;
    u32 res2;
    u32 fw;
    u32 fh_l;
    u32 fh_h;
    u32 res3;
    u32 eba0;
    u32 eba1;
    u32 bpp;
    u32 sl;
    u32 pfs;
    u32 bam;
    u32 res4;
    u32 npb;
    u32 res5;
    u32 sat;
    u32 res6;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct chan_param_mem_planar {
    u32 xv;
    u32 yv;
    u32 xb;
    u32 yb;
    u32 res1;
    u32 nsb;
    u32 lnpb;
    u32 ubo_l;
    u32 ubo_h;
    u32 vbo_l;
    u32 vbo_h;
    u32 res2;
    u32 fw;
    u32 fh_l;
    u32 fh_h;
    u32 res3;
    u32 eba0;
    u32 eba1;
    u32 bpp;
    u32 sl;
    u32 pfs;
    u32 bam;
    u32 res4;
    u32 npb;
    u32 res5;
    u32 sat;
    u32 res6;
}
```
</details>
</li>
</ul>
