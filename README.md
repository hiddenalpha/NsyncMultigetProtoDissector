
Nsync Multiget Dissector
========================

Wireshark dissector for the nsync multiget protocol.




## Usage

- Quit Wireshark.
- Create "C:/Users/%USERNAME%/AppData/Roaming/Wireshark/init.lua".
- Add a line like: `dofile "C:/absolute/path/to/NsyncMultiget.lua"`.
- Launch Wireshark.

Nsync Multiget messages should now be visible in decoded form in the package info tree.




## MultiGet Protocol

See [specification](https://gitit.post.ch/projects/ISA/repos/nsync/browse/src/main/java/org/swisspush/nsync/multiget/README.md) (proprietary bleh...)


