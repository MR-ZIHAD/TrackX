# TraceX

## Author
+ Rafi Vau (MR-ZIHAD)

## What is IP Tracing?
+ As IP addresses are automatically identified thanks to the handshake, IP address trackers can easily collect the data they need and record any further movements. This process of recording is usually done through a JavaScript code attached onto the website tracking IP addresses.

## Introduction
+ TraceX is used to track an ip address. TraceX is developed for Termux and Linux based systems. you can easily retrieve ip address information using TraceX. TraceX use ip-api to track ip address. IP tracking is the technology behind our website that will give you an easy way to lookup, find, track and trace any publicly accessible IP location in the world.

## Overview
+ This documentation is intended for developers who want to write applications that can query IP-API. We serve our data in multiple formats via a simple URL-based interface over HTTP, which enables you to use our data directly from a user's browser or from your server.

## Installation

+ `apt-get update -y`
+ `apt-get upgrade -y`
+ `apt-get install git -y`
+ `git clone https://github.com/MR-ZIHAD/TraceX.git/`
+ `cd TraceX`
+ `chmod +x *`
+ Now If you're using Termux then enter command `./setup_trmx` else just type command `./setup` and press ENTER.
+ When setup is complete then you can trace any types of IP address by command `tracex <Target IP>`

## Usages
```
$ tracex <Target IP>
$ tracex <site domain>
```

+ Example

```
$ tracex example.com
$ tracex 127.0.0.1
```
