# Struct: <code>PartitionBlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct PartitionBlock {
    __be32 pb_ID;
    __be32 pb_SummedLongs;
    __s32 pb_ChkSum;
    __u32 pb_HostID;
    __be32 pb_Next;
    __u32 pb_Flags;
    __u32[2] pb_Reserved1;
    __u32 pb_DevFlags;
    __u8[32] pb_DriveName;
    __u32[15] pb_Reserved2;
    __be32[17] pb_Environment;
    __u32[15] pb_EReserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct PartitionBlock {
    __be32 pb_ID;
    __be32 pb_SummedLongs;
    __s32 pb_ChkSum;
    __u32 pb_HostID;
    __be32 pb_Next;
    __u32 pb_Flags;
    __u32[2] pb_Reserved1;
    __u32 pb_DevFlags;
    __u8[32] pb_DriveName;
    __u32[15] pb_Reserved2;
    __be32[17] pb_Environment;
    __u32[15] pb_EReserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct PartitionBlock {
    __be32 pb_ID;
    __be32 pb_SummedLongs;
    __s32 pb_ChkSum;
    __u32 pb_HostID;
    __be32 pb_Next;
    __u32 pb_Flags;
    __u32[2] pb_Reserved1;
    __u32 pb_DevFlags;
    __u8[32] pb_DriveName;
    __u32[15] pb_Reserved2;
    __be32[17] pb_Environment;
    __u32[15] pb_EReserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct PartitionBlock {
    __be32 pb_ID;
    __be32 pb_SummedLongs;
    __s32 pb_ChkSum;
    __u32 pb_HostID;
    __be32 pb_Next;
    __u32 pb_Flags;
    __u32[2] pb_Reserved1;
    __u32 pb_DevFlags;
    __u8[32] pb_DriveName;
    __u32[15] pb_Reserved2;
    __be32[17] pb_Environment;
    __u32[15] pb_EReserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct PartitionBlock {
    __be32 pb_ID;
    __be32 pb_SummedLongs;
    __s32 pb_ChkSum;
    __u32 pb_HostID;
    __be32 pb_Next;
    __u32 pb_Flags;
    __u32[2] pb_Reserved1;
    __u32 pb_DevFlags;
    __u8[32] pb_DriveName;
    __u32[15] pb_Reserved2;
    __be32[17] pb_Environment;
    __u32[15] pb_EReserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct PartitionBlock {
    __be32 pb_ID;
    __be32 pb_SummedLongs;
    __s32 pb_ChkSum;
    __u32 pb_HostID;
    __be32 pb_Next;
    __u32 pb_Flags;
    __u32[2] pb_Reserved1;
    __u32 pb_DevFlags;
    __u8[32] pb_DriveName;
    __u32[15] pb_Reserved2;
    __be32[17] pb_Environment;
    __u32[15] pb_EReserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct PartitionBlock {
    __be32 pb_ID;
    __be32 pb_SummedLongs;
    __s32 pb_ChkSum;
    __u32 pb_HostID;
    __be32 pb_Next;
    __u32 pb_Flags;
    __u32[2] pb_Reserved1;
    __u32 pb_DevFlags;
    __u8[32] pb_DriveName;
    __u32[15] pb_Reserved2;
    __be32[17] pb_Environment;
    __u32[15] pb_EReserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct PartitionBlock {
    __be32 pb_ID;
    __be32 pb_SummedLongs;
    __s32 pb_ChkSum;
    __u32 pb_HostID;
    __be32 pb_Next;
    __u32 pb_Flags;
    __u32[2] pb_Reserved1;
    __u32 pb_DevFlags;
    __u8[32] pb_DriveName;
    __u32[15] pb_Reserved2;
    __be32[17] pb_Environment;
    __u32[15] pb_EReserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct PartitionBlock {
    __be32 pb_ID;
    __be32 pb_SummedLongs;
    __s32 pb_ChkSum;
    __u32 pb_HostID;
    __be32 pb_Next;
    __u32 pb_Flags;
    __u32[2] pb_Reserved1;
    __u32 pb_DevFlags;
    __u8[32] pb_DriveName;
    __u32[15] pb_Reserved2;
    __be32[17] pb_Environment;
    __u32[15] pb_EReserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct PartitionBlock {
    __be32 pb_ID;
    __be32 pb_SummedLongs;
    __s32 pb_ChkSum;
    __u32 pb_HostID;
    __be32 pb_Next;
    __u32 pb_Flags;
    __u32[2] pb_Reserved1;
    __u32 pb_DevFlags;
    __u8[32] pb_DriveName;
    __u32[15] pb_Reserved2;
    __be32[17] pb_Environment;
    __u32[15] pb_EReserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct PartitionBlock {
    __be32 pb_ID;
    __be32 pb_SummedLongs;
    __s32 pb_ChkSum;
    __u32 pb_HostID;
    __be32 pb_Next;
    __u32 pb_Flags;
    __u32[2] pb_Reserved1;
    __u32 pb_DevFlags;
    __u8[32] pb_DriveName;
    __u32[15] pb_Reserved2;
    __be32[17] pb_Environment;
    __u32[15] pb_EReserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct PartitionBlock {
    __be32 pb_ID;
    __be32 pb_SummedLongs;
    __s32 pb_ChkSum;
    __u32 pb_HostID;
    __be32 pb_Next;
    __u32 pb_Flags;
    __u32[2] pb_Reserved1;
    __u32 pb_DevFlags;
    __u8[32] pb_DriveName;
    __u32[15] pb_Reserved2;
    __be32[17] pb_Environment;
    __u32[15] pb_EReserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct PartitionBlock {
    __be32 pb_ID;
    __be32 pb_SummedLongs;
    __s32 pb_ChkSum;
    __u32 pb_HostID;
    __be32 pb_Next;
    __u32 pb_Flags;
    __u32[2] pb_Reserved1;
    __u32 pb_DevFlags;
    __u8[32] pb_DriveName;
    __u32[15] pb_Reserved2;
    __be32[17] pb_Environment;
    __u32[15] pb_EReserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct PartitionBlock {
    __be32 pb_ID;
    __be32 pb_SummedLongs;
    __s32 pb_ChkSum;
    __u32 pb_HostID;
    __be32 pb_Next;
    __u32 pb_Flags;
    __u32[2] pb_Reserved1;
    __u32 pb_DevFlags;
    __u8[32] pb_DriveName;
    __u32[15] pb_Reserved2;
    __be32[17] pb_Environment;
    __u32[15] pb_EReserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct PartitionBlock {
    __be32 pb_ID;
    __be32 pb_SummedLongs;
    __s32 pb_ChkSum;
    __u32 pb_HostID;
    __be32 pb_Next;
    __u32 pb_Flags;
    __u32[2] pb_Reserved1;
    __u32 pb_DevFlags;
    __u8[32] pb_DriveName;
    __u32[15] pb_Reserved2;
    __be32[17] pb_Environment;
    __u32[15] pb_EReserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct PartitionBlock {
    __be32 pb_ID;
    __be32 pb_SummedLongs;
    __be32 pb_ChkSum;
    __be32 pb_HostID;
    __be32 pb_Next;
    __be32 pb_Flags;
    __be32[2] pb_Reserved1;
    __be32 pb_DevFlags;
    __u8[32] pb_DriveName;
    __be32[15] pb_Reserved2;
    __be32[17] pb_Environment;
    __be32[15] pb_EReserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct PartitionBlock {
    __be32 pb_ID;
    __be32 pb_SummedLongs;
    __be32 pb_ChkSum;
    __be32 pb_HostID;
    __be32 pb_Next;
    __be32 pb_Flags;
    __be32[2] pb_Reserved1;
    __be32 pb_DevFlags;
    __u8[32] pb_DriveName;
    __be32[15] pb_Reserved2;
    __be32[17] pb_Environment;
    __be32[15] pb_EReserved;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct PartitionBlock {
    __be32 pb_ID;
    __be32 pb_SummedLongs;
    __s32 pb_ChkSum;
    __u32 pb_HostID;
    __be32 pb_Next;
    __u32 pb_Flags;
    __u32[2] pb_Reserved1;
    __u32 pb_DevFlags;
    __u8[32] pb_DriveName;
    __u32[15] pb_Reserved2;
    __be32[17] pb_Environment;
    __u32[15] pb_EReserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct PartitionBlock {
    __be32 pb_ID;
    __be32 pb_SummedLongs;
    __s32 pb_ChkSum;
    __u32 pb_HostID;
    __be32 pb_Next;
    __u32 pb_Flags;
    __u32[2] pb_Reserved1;
    __u32 pb_DevFlags;
    __u8[32] pb_DriveName;
    __u32[15] pb_Reserved2;
    __be32[17] pb_Environment;
    __u32[15] pb_EReserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct PartitionBlock {
    __be32 pb_ID;
    __be32 pb_SummedLongs;
    __s32 pb_ChkSum;
    __u32 pb_HostID;
    __be32 pb_Next;
    __u32 pb_Flags;
    __u32[2] pb_Reserved1;
    __u32 pb_DevFlags;
    __u8[32] pb_DriveName;
    __u32[15] pb_Reserved2;
    __be32[17] pb_Environment;
    __u32[15] pb_EReserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct PartitionBlock {
    __be32 pb_ID;
    __be32 pb_SummedLongs;
    __s32 pb_ChkSum;
    __u32 pb_HostID;
    __be32 pb_Next;
    __u32 pb_Flags;
    __u32[2] pb_Reserved1;
    __u32 pb_DevFlags;
    __u8[32] pb_DriveName;
    __u32[15] pb_Reserved2;
    __be32[17] pb_Environment;
    __u32[15] pb_EReserved;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct PartitionBlock {
    __be32 pb_ID;
    __be32 pb_SummedLongs;
    __s32 pb_ChkSum;
    __u32 pb_HostID;
    __be32 pb_Next;
    __u32 pb_Flags;
    __u32[2] pb_Reserved1;
    __u32 pb_DevFlags;
    __u8[32] pb_DriveName;
    __u32[15] pb_Reserved2;
    __be32[17] pb_Environment;
    __u32[15] pb_EReserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct PartitionBlock {
    __be32 pb_ID;
    __be32 pb_SummedLongs;
    __s32 pb_ChkSum;
    __u32 pb_HostID;
    __be32 pb_Next;
    __u32 pb_Flags;
    __u32[2] pb_Reserved1;
    __u32 pb_DevFlags;
    __u8[32] pb_DriveName;
    __u32[15] pb_Reserved2;
    __be32[17] pb_Environment;
    __u32[15] pb_EReserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct PartitionBlock {
    __be32 pb_ID;
    __be32 pb_SummedLongs;
    __s32 pb_ChkSum;
    __u32 pb_HostID;
    __be32 pb_Next;
    __u32 pb_Flags;
    __u32[2] pb_Reserved1;
    __u32 pb_DevFlags;
    __u8[32] pb_DriveName;
    __u32[15] pb_Reserved2;
    __be32[17] pb_Environment;
    __u32[15] pb_EReserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct PartitionBlock {
    __be32 pb_ID;
    __be32 pb_SummedLongs;
    __s32 pb_ChkSum;
    __u32 pb_HostID;
    __be32 pb_Next;
    __u32 pb_Flags;
    __u32[2] pb_Reserved1;
    __u32 pb_DevFlags;
    __u8[32] pb_DriveName;
    __u32[15] pb_Reserved2;
    __be32[17] pb_Environment;
    __u32[15] pb_EReserved;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>__s32 pb_ChkSum</code> ➡️ <code>__be32 pb_ChkSum</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32 pb_HostID</code> ➡️ <code>__be32 pb_HostID</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32 pb_Flags</code> ➡️ <code>__be32 pb_Flags</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32[2] pb_Reserved1</code> ➡️ <code>__be32[2] pb_Reserved1</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32 pb_DevFlags</code> ➡️ <code>__be32 pb_DevFlags</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32[15] pb_Reserved2</code> ➡️ <code>__be32[15] pb_Reserved2</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32[15] pb_EReserved</code> ➡️ <code>__be32[15] pb_EReserved</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
