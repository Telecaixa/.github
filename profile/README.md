> [!WARNING]  
> This project is currently under construction. Changes and updates will be applied in the future.

<p align="center">
  <img src="https://github.com/user-attachments/assets/e041ccb0-65be-4d86-8fd4-2269b500bc68" alt="Frame_151-removebg-preview" width="300">
</p>

<p align="center">Televiu is a simple and intuitive TV player for M3U playlists, designed for kiosk environments.</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="License"></a>
</p>

## Features

- Seamless playback of M3U playlists
- Minimalist and user-friendly interface
- Designed for dedicated TV playback
- Supports devices like Raspberry Pi and OrangePi
- Remote upload and management of M3U playlists
- Control using infrared sensor

## How it works

```mermaid
sequenceDiagram
    participant User as Smartphone
    participant System as Televiu
    participant Server as Server (for playlist storage)

    System->>System: Configure Wi-Fi
    System->>User: Display QR code for M3U upload
    User->>Server: Upload M3U playlist
    Server->>User: Confirm playlist upload
    Server->>System: Provide new playlist
    System->>System: Load new playlist
    System->>User: Playlist successfully loaded
```

## About

Televiu is an open-source project aimed at providing a straightforward media player experience without unnecessary complexity.

## License

This project is licensed under the [MIT License](LICENSE).
