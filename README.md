# Windows Bluetooth A2DP Codec Inspector

This utility helps you inspect Windows Bluetooth A2DP Codec without installing the full Windows Performance Analyzer thing (or use xperf CLI or whatever.)

![Example Image](Assets/Example.png)

The usage should be self-explanatory.

# Build

Standard .NET 10 SDK is required.

**For single-file executable:**
```
dotnet publish -c Release -r win-x64
```
The executable will be at: `bin\Release\net10.0\win-x64\publish\BluetoothAudioCodecInspector.exe`

**For regular build:**
```
dotnet build -c Release
```

**Other platforms:**
- Windows ARM64: `dotnet publish -c Release -r win-arm64`
- Linux x64: `dotnet publish -c Release -r linux-x64`
- macOS (Intel): `dotnet publish -c Release -r osx-x64`
- macOS (Apple Silicon): `dotnet publish -c Release -r osx-arm64`

# License

MIT License

# Acknowledgements

- [How to Check Which Bluetooth A2DP Audio Codec Is Used on Windows](https://helgeklein.com/blog/how-to-check-which-bluetooth-a2dp-audio-codec-is-used-on-windows/)
