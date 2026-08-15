# Transloader for TransImp

This is the OvationPro Transloader for Impression documents.

It was sourced from David Pilling's website: https://www.davidpilling.com/wiki/index.php/Impression

It required the inclusion of the OvationPro XL libraries, and I've included the two parts that it needs.

CI build works, although the image that is produced is different from that which was supplied - largely
due to the !Server binary not being present. I assume we only need the !Convert, as that's what is supplied
in the archive.

