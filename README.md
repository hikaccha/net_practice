*This project has been created as part of the 42 curriculum by <hichikaw>.*

# NetPractice

## Description

NetPractice is a networking training project from the 42 curriculum.

The objective of this project is to understand the fundamentals of computer networking by solving a series of network configuration exercises. Through these exercises, I learned how devices communicate over a network and how to configure network parameters correctly.

The main topics covered in this project include:

- TCP/IP addressing
- IP addresses
- Subnet masks
- CIDR notation
- Default gateways
- Routers
- Switches
- Basic network troubleshooting
- Introduction to the OSI model

The project consists of 10 levels. Each level presents a misconfigured network that must be fixed in order to satisfy the required communication objectives.

---

## Instructions

### Launching the Training Interface

1. Download and extract the NetPractice project files.
2. Open a terminal in the extracted directory.
3. Run:

```bash
./run.sh
```

If the script does not work correctly, start a local web server manually:

```bash
python3 -m http.server 49242
```

Then open:

```text
http://localhost:49242
```

in your web browser.

---

### Completing the Exercises

- Solve each of the 10 levels.
- Adjust the network configuration until all requirements are satisfied.
- Use the **Check again** button to validate the configuration.

---

### Exporting Configurations

After successfully completing a level:

1. Click **Get my config**.
2. Save the exported configuration file.
3. Repeat the process for all 10 levels.

---

### Submission

The repository root must contain:

- README.md
- 10 exported configuration files (one file for each level)

---

## Networking Concepts Studied

### IP Address

An IP address uniquely identifies a device on a network.

Example:

```text
192.168.1.10
```

---

### Subnet Mask

A subnet mask separates the network portion of an IP address from the host portion.

Example:

```text
255.255.255.0
```

---

### CIDR Notation

CIDR notation provides a shorter representation of subnet masks.

Example:

```text
192.168.1.10/24
```

where `/24` corresponds to:

```text
255.255.255.0
```

---

### Default Gateway

A default gateway is the device used to reach destinations outside the local network.

Example:

```text
192.168.1.1
```

---

### Router

A router connects different networks and forwards packets between them.

Example:

```text
192.168.1.0/24
        ↓
      Router
        ↓
192.168.2.0/24
```

---

### Switch

A switch connects devices within the same local network and forwards frames based on MAC addresses.

---

### OSI Model

The OSI model divides network communication into seven layers:

1. Physical
2. Data Link
3. Network
4. Transport
5. Session
6. Presentation
7. Application

Understanding the OSI model helps identify where network problems occur.

---

## Resources

### Documentation

- TCP/IP Networking Fundamentals
- IPv4 Addressing and Subnetting Documentation
- OSI Model Overview
- Cisco Networking Basics
- Cloudflare Learning Center

### Useful References

- https://www.cloudflare.com/learning/
- https://www.cisco.com/
- https://en.wikipedia.org/wiki/OSI_model
- https://en.wikipedia.org/wiki/IPv4

### AI Usage

AI tools were used to:

- Clarify networking concepts
- Understand subnet masks and CIDR notation
- Review routing and gateway concepts
- Verify theoretical understanding

All generated explanations were reviewed and validated manually before being used.


# 日本語解説

## NetPracticeとは

NetPracticeは42カリキュラムにおけるネットワーク基礎学習プロジェクトです。

この課題では、IPアドレスやサブネットマスク、デフォルトゲートウェイ、ルーターなどの概念を理解し、ネットワーク設定の問題を解決することを目的としています。

全10レベルのネットワーク演習を通じて、コンピュータ同士がどのように通信しているのかを学びます。

---

## この課題で学んだこと

### IPアドレス

ネットワーク上の機器を識別するための住所です。

例：

192.168.1.10

---

### サブネットマスク

IPアドレスのうち、どこまでがネットワーク部分で、どこからがホスト部分なのかを判断するための値です。

例：

255.255.255.0

---

### CIDR表記

サブネットマスクを短く表現する方法です。

例：

192.168.1.10/24

この「/24」はサブネットマスク255.255.255.0を意味します。

---

### デフォルトゲートウェイ

異なるネットワークへ通信する際の出口となる機器です。

一般的にはルーターのIPアドレスが設定されます。

---

### ルーター

異なるネットワーク同士を接続し、パケットを転送する機器です。

---

### スイッチ

同じネットワーク内の機器同士を接続する機器です。

---

### OSI参照モデル

ネットワーク通信を7つの層に分けて考えるモデルです。

1. Physical Layer
2. Data Link Layer
3. Network Layer
4. Transport Layer
5. Session Layer
6. Presentation Layer
7. Application Layer

---

## AI利用について

本プロジェクトではAIを以下の目的で利用しました。

- サブネットマスクの理解
- CIDR表記の理解
- デフォルトゲートウェイの理解
- TCP/IPアドレッシングの学習
- ネットワーク関連用語の調査

AIから得た情報は、自身で検証し理解した上で利用しました。
