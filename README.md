# batterymon

Monitors battery of Steelseries Arctis 7

## Notes

System.USB usage example <https://github.com/basvandijk/usb-example>

Battery info example <https://github.com/atagulalan/arctis-battery-percentage>
Vendor ID: 4152
Product ID: 0x12ad

Pass in args with `cabal run batterymon -- 4152 0x12ad`

## Systme requirements

Requires C libusb as noted in <https://hackage.haskell.org/package/bindings-libusb>
Requires libgmp devel libs

On Fedora, it'll be

```bash
sudo dnf install libusb-devel gmp-devel
```
