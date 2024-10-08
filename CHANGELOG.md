# Changelog
## [v1.0.0] - 07/22/2024
- Remove unnecessary domain enumeration functions
- Remove domain enumeration flags from CLI
- Update install-tools script to properly install all dependencies on Debian 12

## [v0.4.2] - 05/24/2024
- Remove unnecessary and bloated .cache folder generated from vulnerability scans and default logins scans.

## [v0.4.1] - 04/29/2024
- Ensure .complete file is created after vulnerability scans complete. This is necessary for MESA-GUI to recognize when the vulnerability scans are done running. 

## [v0.4.0] - 04/26/2024
- Add ability to provide exclude file to full port scan operation

## [v0.3.0] - 04/24/2024
- Remove service enumeration checks from full port nmap scans

## [v0.2.0] - 04/22/2024
- Update vulnerability scans to scan for only critical, high, and medium vulnerabilites for time efficiency

## [v0.1.0] - 02/27/2024
- Initial commit