# uPow Standalone Block Miners

This repository contains the standalone miners for the uPow blockchain, compatible with multiple operating systems and architectures. These miners allow users to mine blocks on the uPow blockchain individually, without the need for joining a mining pool.

## Supported Platforms

- Linux (ARM64, 32-bit, and 64-bit)
- macOS (AMD64 and ARM64)
- Windows (32-bit and 64-bit)

## Prerequisites

Before you begin, ensure you have:

- A uPow wallet address.
- An internet connection.
- A computer with one of the supported operating systems.

## Installation

1. Download the appropriate miner for your operating system.
2. Move the downloaded file to a directory of your choice.
3. Open a terminal (Linux/macOS) or command prompt (Windows)

## Running the Miner

### Linux

For **ARM64**:

```bash
./stand-alone-miner-linux-arm64 -address <wallet_address> -workers 4
```

For **32-bit** systems:

```bash
./stand-alone-miner-linux32 -address <wallet_address> -workers 4
```

For **64-bit** systems:

```bash
./stand-alone-miner-linux64 -address <wallet_address> -workers 4
```

### macOS

For **AMD64**:

```bash
./stand-alone-miner-macos-amd64 -address <wallet_address> -workers 4
```

For **ARM64** (M1/M2 chips):

```bash
./stand-alone-miner-macos-arm64 -address <wallet_address> -workers 4
```

### Windows

For **32-bit** systems:

```cmd
stand-alone-miner-win32.exe -address <wallet_address> -workers 4
```

For **64-bit** systems:

```cmd
stand-alone-miner-win64.exe -address <wallet_address> -workers 4
```

## Configuration

- `<wallet_address>`: Replace this with your actual uPow blockchain address.
- `workers`: This is the number of worker threads you want to allocate for mining. Adjust this based on your CPU's capability for optimal performance.
