### fax_analysis_server

## Overview

This is a server app that will help to investigate problems in fax calls.

This is a work in progress. There is nothing to see here yet.

## Converting pdf to tiff appropriate for faxing

Something like this should work:

```
gs -q -sDEVICE=tiffg4 -dBATCH -dPDFFitPage -dNOPAUSE -sOutputFile=out.tiff in.pdf
```

Ref:
https://itgala.xyz/how-to-generate-a-fax-compatible-multi-page-tiff-from-a-pdf/

