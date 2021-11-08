# Wi-Fi Fine Timing Measurement

Wi-Fi Fine Timing Measurement (FTM) enables two stations to estimate the physical distance between them.

We provide tools to experiment with the protocol, and keep track of its support and security vulnerabilities.

## Hardware and Support

We confirmed support on hardware from a variety of vendors, and track its adoption rates in practice.

For more information, see [Wi-Fi FTM Hardware](HARDWARE.md) and [Wi-Fi FTM Survey](survey/).

## Security and Privacy

We identified vulnerabilities and weaknesses compromising the security and privacy of Wi-Fi FTM.

We keep track of these, together with any CVE Identifiers and vendor security updates.

For more information, see [Wi-Fi FTM Security and Privacy](SECURITY.md).

## Code

We provide a number of tools to experiment with the Wi-Fi FTM protocol.

For example, to modify the distance measured by an initiating station.

For more information, see [Wi-Fi FTM Tools](code/).

## Publication

This work was published at ACM Conference on Security and Privacy in Wireless and Mobile Networks (WiSec '21):

- [Here, There, and Everywhere: Security Analysis of Wi-Fi Fine Timing Measurement](https://dl.acm.org/doi/10.1145/3448300.3467828)

## Conclusion

Wi-Fi FTM is not secure, and we discourage its usage for security-sensitive applications.

We disclosed our findings to all vendors, and hope to contribute and push for more secure implementations.

#### Additional Resources
Want to learn more on Wi-Fi FTM? Consider the following resources:
- http://people.csail.mit.edu/bkph/ftmrtt
- https://source.android.com/devices/tech/connect/wifi-rtt
