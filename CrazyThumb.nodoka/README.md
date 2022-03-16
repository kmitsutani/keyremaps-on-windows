CrazyThumb.nodoka
=================

This is a configuration for Nodoka, a key-mapping application for Windows.

Main cocepts of this configuration is as bellow:

* Do not idle thumb (in other words, do not leave thumb lazy).
  * Remap 変換／無変換(NFER/XFER) keys customized modifiser key (M0, M1 in Nodoka's term)
  * Draw Esc, Enter and Symbols etc to home position
* Because of layout consistency of corresponding parenthesises adopt 104-US layout
  * Start with 109-JP layout and re-define 104-US layout on that ('104on109.nodoka')

We can implement the almost same key re-mapping by XKB or Karabiner(except macOS, as of now) in above strategy.
The environment dependency of the keymapping provided by this storategy is not so high.
