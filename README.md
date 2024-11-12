# rd-rust

rd-rust is a blazing-fast, low-latency Remote Desktop application built in Rust. It is designed to provide a high-quality image with minimal delay, making it ideal for applications where responsiveness and clarity are essential.

## Project Goals

- **Low Latency**: Minimize delay between the host and client for a real-time experience.
- **High Quality**: Deliver clear, high-resolution images without compromising on speed.
- **Secure**: Ensure secure communication between the host and client.
- **Cross-Platform**: Support major operating systems including Windows, macOS, and Linux.


## Key Features

- **Real-Time Video Encoding**: Compresses frames with efficient encoding for fast transmission.
- **Low-Latency Networking**: Built with `QUIC` or WebSocket over `tokio` for low-latency, high-throughput data transfer.
- **Secure Communication**: Uses TLS encryption to secure data transmitted between the host and client.
- **Remote Input Control**: Capture and send keyboard and mouse inputs to control the host machine.
