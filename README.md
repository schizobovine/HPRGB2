HPRGB2
======

Arduino Library for High Power RGB LED shield @ http://ledshield.wordpress.com

This supersedes the HPRGB_Shield_V2_Library-v1.2.1.zip.

Changes from V1.2.1:

1.  Adds higher resolution goToRGBHI routine. This uses 1024 CIE lab brightness corrected 12-bit values for slow, smooth dimming at low brighness values and in conjunction with slow speeds. The original goToRGB function uses only 256 12-bit values.

2.  Adds a higher resolution goToHSB10 routing which uses 768 vs. 256 values for Hue resulting in much smoother color fading at slow fading speeds compared to the goToHSB routine.
