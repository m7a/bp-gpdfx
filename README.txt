Build instructions for package `mdvl-gpdfx`.
Create a Debian package by invoking `ant package`.

See <https://github.com/yishilin14/gpdfx-ng> for the implementation downloaded
and used for creating the package.

Formerly, a repository called `bo-gpdfx` existed containing a slightly improved
version of the GTK-2.0 variant. It turned out, that this version would no longer
run on Debian 10+ due to the missing `python-poppler` package. It was thus
decided to move MDVL to the `gpdfx-ng` tool which does not need Ma_Sys.ma
specific changes anymore.

It is expected that there is no interest in the Ma_Sys.ma-changed GTK-2.0
version. Should there be any need for it, it can be uploaded on request, though.
